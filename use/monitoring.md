---
description: >-
  Monitoring continuously tracks API performance, availability, and usage,
  identifying issues and ensuring optimal operation through real-time
  observation and analysis
icon: memo
---

# Monitoring

<details>

<summary>Crawl</summary>

* The API owner uses the default [monitoring tools provided by the API Platform](https://confluence.tools.3stripes.net/display/public/API2/How+to+Monitor+APIs), based on the HOLMES Observability Platform, including:
  * Kibana&#x20;
  * Grafana
  * Instana

</details>

<details>

<summary>Walk</summary>

* The API owner actively uses the monitoring tools provided by the API Platform to understand the API behavior.
* They are aware of average request traffic and can identify anomalies in API usage.

</details>

<details>

<summary>Run</summary>

* The API owner monitors the API beyond the default tools provided by the API Platform, adding service-specific metrics to Instana and Grafana.
* The API also integrates sanity check tools with alerting platforms offered by the Observability Platform, such as Opsgenie.

</details>

<details>

<summary>Fly</summary>

* The API owner maintains up-to-date information on API usage and can compare historical data to anticipate future trends.
* Alerts are configured to notify about unexpected behaviors.
* Periodic usage patterns are incorporated into the rate limiting plan, enabling the API to scale appropriately.
* Sanity checks quickly detect issues to escalate incidents promptly.
* The API owner understands the resource requirements needed to ensure smooth traffic flow and minimize errors.

</details>
