---
description: >-
  Clean Architecture promotes a clear separation of concerns, organizing code
  into well-defined layers to improve maintainability, testability, and
  independence
icon: memo
---

# Clean Architecture

<details>

<summary>Crawl</summary>

* There are not different layers
* The application is center in the Framework.

</details>

<details>

<summary>Walk</summary>

* There is a level of independence from the database
* The layers are well-defined but remain strongly dependent on the framework used.

</details>

<details>

<summary>Run</summary>

* Framework Independence:
  * The architecture does not rely on any specific library or feature-rich framework.&#x20;
  * This allows frameworks to be used as tools rather than forcing the system to conform to their constraints.
* Testability: Business rules can be tested independently of the User Interface (UI), database, web server, or any other external components.

</details>

<details>

<summary>Fly</summary>

*   User Interface independence:

    * The user interface (UI) can be changed easily without affecting the rest of the system

    > e.g. A web UI could be replaced with a console UI without impacting the business rules.
* Database Independence:
  * You can switch databases, without affecting the core business logic
  * The business rules remain completely decoupled from the database technology

</details>
