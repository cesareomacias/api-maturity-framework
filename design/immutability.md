---
description: >-
  Immutability in API design ensures that once a contract is published, it
  remains unchanged, promoting stability and backward compatibility across
  versions.
icon: memo
---

# Immutability

<details>

<summary>Crawl</summary>

* The API contract is not treated as immutable; versions are never formally published and may undergo changes at any time.

</details>

<details>

<summary>Walk</summary>

* Although a first version was published, newer versions remain in development and are never formally published

</details>

<details>

<summary>Run</summary>

* All API versions are formally published.&#x20;
* [Semantic versioning](https://semver.org/) is strictly followed
* Non-breaking changes are released as minor versions:

> e.g., (1.11 → 1.12)

* Breaking changes are released as major versions:

> (e.g., 1.12 → 2.1).&#x20;

* However, previous versions are not maintained under an SLA and are decommissioned after a deprecation period without guaranteed support.

</details>

<details>

<summary>Fly</summary>

* API contract versions are immutable.&#x20;
* Any new version is first designed and agreed upon with stakeholders to ensure backward compatibility.&#x20;
* Non-breaking changes are released as minor versions, while breaking changes are released as major versions.&#x20;
* Previous versions are maintained under an SLA for a defined period before being decommissioned following a formal deprecation process.

</details>
