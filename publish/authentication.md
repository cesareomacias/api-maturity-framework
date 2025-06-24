---
description: Authentication verifies the identity of the consumers accessing an API
icon: memo
---

# Authentication

<details>

<summary>Crawl</summary>

* The API has no authentication measures, uses a single API key shared by all consumers.
* The API key is never rotated.

</details>

<details>

<summary>Walk</summary>

* The API is protected by an individual API key assigned to each consumer.
* Credential rotation occurs approximately every three months.
* The security model is clearly defined in the API contract.

</details>

<details>

<summary>Run</summary>

* The API is secured through centralized authentication against a corporate Identity Provider&#x20;

> e.g. OpenID Connect via Adidas Entra ID.

* All consumers are properly identified, and each has their own credentials.
* The security model is defined within the API contract.
* The API contract provides information on how to obtain or renew credentials before they expire.
* You have followed the [API Security Decision Flow.](https://confluence.tools.3stripes.net/display/API2/API+Security+Decision+Flow)

</details>

<details>

<summary>Fly</summary>

* Credentials are rotated at least every three months.

</details>
