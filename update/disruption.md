---
description: >-
  Plan and manage API disruptions to minimize impact, ensuring clear
  communication and support for consumers during transition
icon: memo
---

# Disruption

<details>

<summary>Crawl</summary>

* A minor or major change in the API implementation can cause a contract breach.&#x20;
* No prior warning was given.
* The API contract version number remained unchanged.

</details>

<details>

<summary>Walk</summary>

* A major change in the API can cause a contract breach.
* Minor changes do not impact consumers.&#x20;
* No prior warning was given.
* The API contract retained the same major version number.

</details>

<details>

<summary>Run</summary>

* The pipeline enforces compatibility with the latest API contract version, preventing incompatible changes.&#x20;

</details>

<details>

<summary>Fly</summary>

* No changes, whether minor or major, are allowed to break the API contract.&#x20;

- If a violation occurs, an issue ticket is automatically created.

</details>
