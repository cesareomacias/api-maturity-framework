---
description: >-
  An API contract is a document that details how an API works, including its
  endpoints, request, response formats, and authentication methods.
icon: memo
---

# Contract

<details>

<summary>Crawl</summary>

* The API uses an auto-generated contract.
* The API design is still database centric.
* Error handling is missing, with error messages being used but always returning the same response status code (usually 200 OK).
* HTTP methods are not used appropriately:

> e.g. using POST to retrieve data by sending a query in the request body

</details>

<details>

<summary>Walk</summary>

* The API uses an auto-generated contract, but it is stored only in the API repository tool.
* OpenAPI/AsyncAPI specifications are managed via SwaggerHub. The rest of artifacts are stored in Apicurio Registry.
* The API design remains database centric.
* The definition of commands in the API paths is present, not resource oriented, and/or using always the same HTTP method.

> - GET - getXXXX
> - POST - updateXXX
> - POST - deleteXXX

* Schema definitions are either missing or overly ad hoc:

> e.g. generic structures such as `"requestObject"` or `"responseObject"`

</details>

<details>

<summary>Run</summary>

* The API contract is designed using specific tools.

> e.g. SwaggerHub for OpenAPI and AsyncAPI

* OpenAPI/AsyncAPI specifications are managed via SwaggerHub. The rest of artifacts are stored in Apicurio Registry.
* REST APIs:
  * The API design is focused on resources.
  * There are real-like examples of request/response.
  * The schema definition is clear.
  * Hypermedia is used in all responses.
* Event Driven APIs:
  * Appropriate protocol like Kafka, AMQP, MQTT or HTTP is implemented.
  * The schema definition is clear.

</details>

<details>

<summary>Fly</summary>

* API contract first approach is followed strictly.
* Any change starts designing in the specific tool:
  * OpenAPI/AsyncAPI → SwaggerHub
  * Rest of artifacts → Apicurio Registry
* The tool to auto-generate code from contract to services is used to generate a new version of the service.
* The API design is focused on resources (RESTful).
* The API Is focused on events (AsyncAPI).
* Schemas and object definition are matching with terms in the [adidas Enterprise Data Catalog](https://adidas.collibra.com/dashboard).
* The correct API style is chosen for the right scenario, according of the purpose and technical context of the API: REST, gRPC, GraphQL, RPC, etc.

</details>
