---
description: >-
  Contract testing in the development phase ensures that both providers and
  consumers adhere to the agreed API contract.
icon: memo
---

# Contract Testing

<details>

<summary>Crawl</summary>

* There is not contract testing

</details>

<details>

<summary>Walk</summary>

* The contract testing is covered with acceptance testing

</details>

<details>

<summary>Run</summary>

* Specific tools are used for contract testing, as part of the pipelines

> e.g. Pact

</details>

<details>

<summary>Fly</summary>

* All versions are tested
* Any contract breach will stop the pipeline
* Pact is used for bidirectional contract testing, ensuring that when a new version is deployed, no consumer is negatively impacted

</details>
