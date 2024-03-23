# https://www.getzola.org/documentation/deployment/docker-image/
#
# -----------------------------------------------------------------------------
# Build image
# -----------------------------------------------------------------------------
FROM ghcr.io/getzola/zola:v0.18.0 as build

ENV \
  BUILD_DIR="/project"

COPY ./src/. $BUILD_DIR

WORKDIR $BUILD_DIR
RUN ["zola", "build"]


# -----------------------------------------------------------------------------
# Webserver image
# -----------------------------------------------------------------------------
FROM ghcr.io/static-web-server/static-web-server:2 as webserver

ENV \
  BUILD_DIR="/project" \
  RUNTIME_DIR="/public"

WORKDIR /

COPY \
  ./LICENSE \
  ./README.md \
  $RUNTIME_DIR

COPY --from=build $BUILD_DIR/public $RUNTIME_DIR
