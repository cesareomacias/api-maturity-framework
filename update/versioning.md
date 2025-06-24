---
description: >-
  Implement versioning strategies to manage API changes, ensuring backward
  compatibility and smooth transitions for consumers
icon: memo
---

# Versioning

<details>

<summary>Crawl</summary>

* Versioning is tied to the API service release cycle.

</details>

<details>

<summary>Walk</summary>

* There is a versioning policy in place for the API contract:

> e.g. _major_._minor_._patch_

</details>

<details>

<summary>Run</summary>

* Each change is versioned according to a strict policy that follows semantic versioning principles.&#x20;
* The repository is tagged accordingly to reflect these versions.&#x20;
* SonarQube tracks and maintains quality metrics for every version.&#x20;
* SLAs for older versions and ongoing maintenance are clearly defined and enforced.

</details>

<details>

<summary>Fly</summary>

* Throughout the API lifecycle, we properly maintain multiple major and minor versions without breaking the contract or compromising immutability.&#x20;
* SLAs for older versions and maintenance are communicated to consumers, alongside a clear plan for deprecation and decommissioning.

</details>
