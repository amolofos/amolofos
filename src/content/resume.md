+++
title = "Resume"
+++

<div style="align-items: right;">
Download as pdf <a style="display: inline-block;" href="https://github.com/amolofos/CVKafetzisDimitris/releases/download/v1.0.54/DimitrisKafetzis-cv-en-oneColumn.v1.0.54.pdf" target="blank"><img src="icons8-pdf-12.png" alt="cv" title="cv"></a>
</div>

<div style="text-align: center;">
  <p style="font-size: 3em;">Dimitrios Andreas Kafetzis</p>

  <p style="font-size: 1.5em;">Site Reliability and Platform Engineering</p>
</div>

<div style="display: flex; align-items: center; justify-content: center;">

  <ul style="list-style: none; text-align: center;">
    <li style="display: inline-block;"><a href="mailto:dimitris@kafetzis.dev" target="blank"><img src="email_icon.png" alt="email" title="mailto:dimitris@kafetzis.dev"></a></li>
    <li style="display: inline-block;"><a href="https://www.linkedin.com/in/kafetzisd" target="blank"><img src="icons8-linkedin.svg" alt="LinkedIn: kafetzisd" title="LinkedIn: kafetzisd"></a></li>
    <li style="display: inline-block;"><a href="https://github.com/amolofos" target="blank"><img src="icons8-github.svg" alt="Github: amolofos" title="Github: amolofos"></a></li>
    <li style="display: inline-block;"><a href="https://github.com/amolofos/CVKafetzisDimitris/releases/download/v1.0.54/DimitrisKafetzis-cv-en-oneColumn.v1.0.54.pdf" target="blank"><img src="pdf_icon.png" alt="cv as pdf" title="cv as pdf"></a></li>

  </ul>
</div>

<div style="text-align: center;">
My experience spans across 12 YoE designing and building heavily transactional, distributed, relational database backed systems. The last 4 years I have made a shift on the SRE problem domain.
</div>

----

## WORK EXPERIENCE

<!-- You have to wrap the "left" and "right" half of these headings in spans by
hand -->
### <span>Senior Site Reliability Engineer (SRE) | Platform Reliability Engineer</span>
<span>Sept 2024 - Present</br>
Adyen - Singapore</span>

Joined as a member of the global SRE team.

- Eased the onboarding by structuring and writing an intro-to-platform course.

### <span>Site Reliability Engineer (SRE) | Platform Engineer</span>
<span>Nov 2022 - Aug 2024</br>
VegaSolutions / TokkaLabs / Native / RangeProtocol - Singapore</span>

Joined as the first dedicated SRE/Platform engineer under Vega Solutions bulding a platform to support multiple tenants. The last months of my journey with these companies, June - August 2024, my employment moved under Tokka Labs.

- Designed and implemented new system architecture (AWS -> AWS) improving externally exposed service latency below 500ms (from ~1s) and supporting multiple regions (provisioning a new region with full services takes less than 2 days).
- Introduced shared services such as SSO, Vault eliminating the need for different accounts per service.
- Created template integrations for instrumenting nodejs and python services against Prometheus, Grafana and Jaeger improving visibility and allowing engineers to investigate production issues in a matter of minutes.
- Refactored helm templates and value files by introducing separation and hierarchy simplifying them and easing their maintenance. This allowed application engineers to automatically generate them and reduce the introduction of new services from a couple of days to a few minutes.
- Pushed for a cloud native architecture by provisioning databases inside k8s and advocating for k8s only deployments. Succeeded in deploying small mysql, postgres/timescale and redis clusters in k8s.

### <span>Site Reliability Engineer (SRE)</span>
<span>Sept 2021 - Oct 2022 (1yr 1mo)</br>
Bytedance - Global E-commerce TikTok - Singapore</span>

Joined the newly formed SRE team supporting the Global E-commerce function of TikTok.

- Implemented a Kubernetes sidecar measuring the availability SLI of more than 200 HTTP services.
- Analysed SLI based alerts and pushed for adoption of error budget burn rate approach.
- Designed and implemented the MVP version of an incident record tool aiming to reduce the manual bookkeeping activities during oncall cases and build a knowledge base based on them.

### <span>Principal Integration Engineer | Site Reliability Engineer</span>
<span>Aug 2020 - Sep 2021 (1 yr 2 mos)</br>
OpenBet - Singapore</span>

- Defined the initial process for an SRE rota across two teams located in multiple locations.
- Updated existing Grafana dashboards and created new ones to visualise our production problems across the stack (haproxy, applications, database).

### <span>Principal Software Engineer</span>.
<span>Sep 2018 - Jul 2020 (1 yr 11 mos)</br>
OpenBet - Singapore</span>

- Led a team of 3 engineers with the goal to harden the funding flow ensuring eWallet integrity resulting in a drop of 1 incident per week to 1 per year.
- Enhanced the performance of slow database queries bring the number of production incidents due to human design error down to zero (0).
- Investigated more than 20 high profile production issues and presented 4 sensitive incidents to C level stakeholders.
- Migrated 80 million lottery bets to renewed, more robust data model.

### <span>Senior Software Engineer</span>
<span>Oct 2015 - Aug 2018 (2 yrs 11 mos)</br>
OpenBet - Singapore</span>

- Coordinated development of cross functional features amongst teams of different locations with a goal to rollout our solution to a new tier 1 customer.
- Owned the data migration into the new platform including 100 million rows of transaction history and user activity and completed in under 3 hours.
- Designed distributed queries for Informix database materialising the reporting needs of the Finance and Trading departments.
- Influenced the release process from code to production increasing the delivery capacity of the team.
- Rewrote the ansible deployment scripts reducing to zero the release introduced incidents.

### <span>Software Engineer</span>
<span>Nov 2012 - Sep 2015 (2 yrs 11 mos)</br>
Rizariou 10, Chalandri, Greece</span>

- Wrote and performed the extraction of one billion rows during uptime and no impact to operations.
- Integrated with Paypal & Safecharge payment providers tokenizing credit card information removing the need for PCI compliance.

## EDUCATION
I have not completed tertiary education.

Attended Electrical Engineering and Computer Science, University of Patras, Greece during the period of Sep 2003 - Jul 2009.
