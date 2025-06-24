---
description: >-
  Authorization determines the permissions and access levels granted to
  authenticated users, ensuring they can only perform allowed actions
icon: memo
---

# Authorization

<details>

<summary>Crawl</summary>

* Authorization is not applied because authentication is not required.
* All users are treated the same, despite the existence of distinct scopes and clearly defined user groups.

</details>

<details>

<summary>Walk</summary>

* Authentication is in place, but all consumers are authorized to access all resources.

</details>

<details>

<summary>Run</summary>

* Each consumer can access only their specific assigned resources.

</details>

<details>

<summary>Fly</summary>

* Clients must use different consumers or credentials depending on the required level of access, this means there is no _magic_ consumer with unrestricted access to all resources.

</details>
