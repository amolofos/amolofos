# kafetzis.dev

## Development

1. Run website in development

    * Build development docker

        ```bash
        docker build \
          -f docker/Dockerfile \
          --target build \
          --progress plain \
          -t kafetzis.dev-build \
          .
        ```

    * Run serve at `http://0.0.0.0:1111`

      ```bash
      docker rm -f kafetzis.dev && \
      docker run \
        --rm \
        --name kafetzis.dev-build \
        -p 1111:1111 \
        -v ./src/:/project/ \
        kafetzis.dev-build \
        serve -i 0.0.0.0
      ```

2. Run website in production

    * Build production docker

        ```bash
        docker build \
          -f docker/Dockerfile \
          -t kafetzis.dev \
          --progress plain \
          .
        ```

    * Run webserver at `https://127.0.0.1:8080`

        ```bash
        docker rm -f kafetzis.dev && \
        docker run \
          --rm \
          --name kafetzis.dev \
          -p 8080:80 \
          kafetzis.dev
        ```

## First time setup

What did we do when we first created this repository?

1. Install zola

    ```bash
    wget https://github.com/barnumbirr/zola-debian/releases/download/v0.18.0-1/zola_0.18.0-1_amd64_bullseye.deb
    sudo dpkg -i zola_0.18.0-1_amd64_bullseye.deb
    ```

2. Initialise website

    ```bash
    zola init src
    ```

3. Install theme

    ```bash
    git submodule add git@github.com:Speyll/anemone.git src/themes/anemone
    ```

## Dependencies

* Theme from [Speyll/anemone](https://github.com/Speyll/anemone)

## License

See [MIT License](LICENSE) document.
