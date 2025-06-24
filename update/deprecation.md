---
description: >-
  Communicate deprecation plans clearly, providing timelines and alternatives to
  help consumers transition smoothly from outdated API versions
icon: memo
---

# Deprecation

<details>

<summary>Crawl</summary>

* Methods or parameters are removed without notifying consumers, causing potential disruptions.
* No SLA is defined for the API, leaving consumers without guarantees on availability or support.
* Deprecated API versions lack advance warning, leading to unexpected breaks.
* There isn't prior notice for the decommissioning of API versions, risking service interruptions.

</details>

<details>

<summary>Walk</summary>

* Consumers are notified in advance about changes scheduled for removal within a specific timeframe.
* No SLA is currently defined for the API.
* Deprecation of API versions is clearly indicated in both documentation and the API contract.
* No warnings are provided for the decommissioning of API versions.

</details>

<details>

<summary>Run</summary>

* An SLA for the API is established, including a clearly defined deprecation period with advance warnings documented in the API contract and/or related materials.
* Decommissioning is coordinated and agreed upon with API consumers well in advance.

</details>

<details>

<summary>Fly</summary>

* The API SLA includes terms governing the decommissioning of API versions.
* Consumers receive timely warnings according to a defined schedule.
* Feedback from consumers is actively considered during the process.

</details>
