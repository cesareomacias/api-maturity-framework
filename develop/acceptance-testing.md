---
description: >-
  Acceptance testing verifies that the system meets defined business
  requirements, ensuring functionality aligns with stakeholder expectations
  before release.
icon: memo
---

# Acceptance Testing

<details>

<summary>Crawl</summary>

* There are some acceptance tests that are executed as part of the pipeline

</details>

<details>

<summary>Walk</summary>

* Every feature begins with a User Story, which is linked to specific acceptance tests
* A test report is generated for each delivery version
* Behavior driven development (BDD) is used to define acceptance criteria through executable tests
* The company uses specific tools to link User Stories and tests: Jira and Xray.

</details>

<details>

<summary>Run</summary>

* Acceptance tests are sufficient to determine whether to proceed to the next stage of the pipeline in continuous delivery/deployment
* Contract testing is included as part of the acceptance testing process

</details>

<details>

<summary>Fly</summary>

* A failed feature test will automatically create a defect issue in the current sprint
* Non-functional requirements (NFRs) are tested as part of the acceptance testing

</details>
