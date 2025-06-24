---
description: >-
  Correctness in API design means ensuring that the contract accurately reflects
  intended behavior, data structures, and edge cases from the start.
icon: memo
---

# Correctness

<details>

<summary>Crawl</summary>

* The API does not adhere to the Adidas API guidelines in any aspect.

</details>

<details>

<summary>Walk</summary>

* The API contract partially follows the API guidelines.&#x20;
* Consumers are properly identified.
* There are no errors reported in the API contract ([Spectral](https://adidas.gitbook.io/api-guidelines#validating-your-api-specification-against-openapi-and-async-rules)).

</details>

<details>

<summary>Run</summary>

* The API contract:
  * Fully complies with the API guidelines and established standards.&#x20;
  * Adheres to the security policy.
  * Follows proper API versioning practices.
  * Ensures unambiguous consumer identification.&#x20;
  * Required metadata—such as security settings, rate limiting plans, API owners, and LeanIX IDs—is correctly applied to the contract and all resources.&#x20;
  * There are no errors reported in the API contract ([Spectral](https://adidas.gitbook.io/api-guidelines#validating-your-api-specification-against-openapi-and-async-rules)).

</details>

<details>

<summary>Fly</summary>

* The API contract:
  * Fully adheres to the API guidelines and standards.
  * Complies with the security policy.
  * Follows established versioning practices.
  * It ensures unambiguous consumer identification.
  * Includes all required metadata—such as security settings, rate limiting plans, API owners, and LeanIX IDs—across the contract and its resources.&#x20;
  * There are no errors reported in the API contract ([Spectral](https://adidas.gitbook.io/api-guidelines#validating-your-api-specification-against-openapi-and-async-rules)).
* The API informs their consumers about changes, fix, new feature and deprecations.

</details>
