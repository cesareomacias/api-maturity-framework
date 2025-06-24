---
description: >-
  Load testing evaluates an API's performance under expected and peak conditions
  to ensure reliability and scalability
icon: memo
---

# Load Testing

<details>

<summary>Crawl</summary>

* Load tests are performed occasionally.

</details>

<details>

<summary>Walk</summary>

* Load tests are executed before any deployment to production is allowed.

</details>

<details>

<summary>Run</summary>

* Load tests are consistently executed either at every stage or at specific stages of the delivery pipeline.&#x20;
* A report is generated for each new version of the API, and the results are used to guide proper service scaling.

</details>

<details>

<summary>Fly</summary>

* Any unexpected behavior detected during load testing will halt the pipeline from progressing to the next stage.&#x20;
* [Rate limiting plans](https://confluence.tools.3stripes.net/display/API2/API+Security+-+Rate+Limit+Plan+for+APIs) are defined based on load test results.
* Any deviations from expected performance or discrepancies compared to previous reports will trigger the creation of an issue ticket.

</details>
