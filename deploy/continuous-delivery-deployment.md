---
description: >-
  It automates the release of API updates, ensuring rapid, reliable, and
  consistent delivery to production environments
icon: memo
---

# Continuous Delivery/Deployment

<details>

<summary>Crawl</summary>

* Services are deployed to production only after completing a defined process that includes manual acceptance testing along with automated acceptance tests.

</details>

<details>

<summary>Walk</summary>

* Services are deployed at every stage through a pipeline, but progression to the next stage is decided manually.&#x20;
* Acceptance tests are executed as part of this pipeline.&#x20;
* Only in the development environment does deployment happen automatically when a pull request is merged into the developer branch.

</details>

<details>

<summary>Run</summary>

* Within a microservice architecture, new features or hotfixes are automatically delivered as new versions after passing all quality gates, acceptance tests, and load tests.&#x20;
* Deployment to production, however, is ultimately decided manually.

</details>

<details>

<summary>Fly</summary>

* As part of a microservice architecture, every new feature or hotfix is automatically deployed to production.&#x20;
* The process is well-established and trusted, alleviating concerns about production deployments.

</details>
