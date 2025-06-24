---
description: >-
  Discoverability ensures APIs are easily found and understood by developers,
  promoting efficient integration and usage through clear documentation and
  metadata
icon: memo
---

# Discoverability

<details>

<summary>Crawl</summary>

* There is no defined user journey for discovering the API.
* Consumers MUST contact the API owner directly to obtain information about it.

</details>

<details>

<summary>Walk</summary>

* Potential consumers use the API Registries ([SwaggerHub](https://design.api.3stripes.io/main) and/or [Apicurio](https://apicurio.api.3stripes.io/ui/artifacts)) to discover available APIs.
* The consumers still require ongoing guidance from the API owner to get started with the API.

</details>

<details>

<summary>Run</summary>

* Consumers can discover APIs through the following sources:
  * [SwaggerHub](https://design.api.3stripes.io/main)
  * [Apicurio Registry](https://apicurio.api.3stripes.io/ui/artifacts)
  * [Collibra](https://adidas.collibra.com/apps/) (Enterprise Data Catalog)
* The API owner provides all necessary information for onboarding, including how to obtain credentials for new consumers and relevant contact details.
* The API contract in SwaggerHub is well-designed, free of design issues, and easy for new consumers to understand.

</details>

<details>

<summary>Fly</summary>

* The API implements HAL for auto-discovery of related resources.
* The consumers only need to use the adidas API Service Hub to obtain all necessary information to start using the API.

</details>
