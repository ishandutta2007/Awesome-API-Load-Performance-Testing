# Awesome API Load & Performance Testing

A curated list of awesome API load, performance, stress, and scalability testing tools, platforms, and resources.

---

## Sector Overview & Market Dynamics

The global load and performance testing market is estimated at **$1.4B to $1.65B**, with forecasts projecting growth beyond **$5B to $7.5B** driven by cloud migrations, microservices architectures, and shift-left continuous testing in CI/CD pipelines.

The sector is **moderately fragmented** rather than a winner-take-all monopoly: while open-source tools (Apache JMeter, Locust, k6) anchor ubiquitous grassroots usage, commercial market share is distributed across legacy enterprise testing platforms (Tricentis, Perforce/BlazeMeter), developer-centric observability and API platforms (Grafana Labs, Postman), and agile SaaS testing providers (Artillery, Gatling, OctoPerf).

---

## SaaS & Cloud Platforms

The table below lists notable SaaS and managed performance testing platforms, sorted in descending order by parent company scale (valuation / annual revenue).

| Product | Parent / Company | Company Scale (Valuation / Revenue) | Starting Paid Pricing | Free Tier / Free Trial Limits | Key Capabilities |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Grafana Cloud k6** | Grafana Labs | **$6.0B valuation** (~$600M ARR) | **$0.15 / VUh** (Pro plan pay-as-you-go above included monthly quota) | **500 VUh / month** forever free, 14-day metric retention, max 50 concurrency | Developer-centric JavaScript scripting, distributed multi-region cloud execution, native Grafana dashboards. |
| **Postman Performance Testing** | Postman, Inc. | **$5.6B valuation** (~$313M ARR) | **$0.04 / VUh** for cloud-hosted runs (or $14/user/mo billed annually for Basic Team) | **Free forever** with unlimited local VU execution via Desktop App / CLI; 1 seat on Free plan | Integrated API client collections, automated load test runs, cloud or local execution. |
| **Tricentis NeoLoad** | Tricentis | **$4.5B valuation** (~$500M ARR) | **~$20,000 / year** (Professional tier custom licensing quote) | **14-day free trial** strictly capped at **10 Virtual Users (VUs)** | Enterprise end-to-end performance testing, codeless test design, deep APM and CI/CD integrations. |
| **BlazeMeter** | Perforce Software | **~$1.1B valuation** (~$280M–$750M revenue) | **$99 / month** ($1,188 billed annually for Basic tier, 1,000 VUs) | **10 tests / month**, max 50 VUs, max 20 minutes duration, 1 shared generator | Multi-engine cloud runner (JMeter, Selenium, Taurus, Locust), real-time reporting, mock services. |
| **Artillery Cloud** | Artillery | **~$1M ARR** (Seed / privately held) | **$199 / month** (Team tier, up to 25 distributed cloud workers) | **30 test reports / month**, max 5 distributed workers, 30 min duration, 2 seats | Serverless distributed load testing on AWS/Azure, YAML/JS test scripts, high socket concurrency. |
| **Gatling Enterprise** | GatlingCorp | **Bootstrapped / SMB scale** (Privately held) | **€89 / month** (Basic / Starter tier billed annually, up to 60k VUs) | **14-day free trial** with restricted load generator credits and community support | Asynchronous Akka/Netty engine, Scala/Java/Kotlin DSL, detailed real-time reporting. |
| **OctoPerf** | OctoPerf | **Boutique commercial** (Privately held) | **$99 / test** on-demand (or subscription plans starting at **$999 / month**) | **Free forever** up to **50 concurrent VUs**, 20 min test duration, 1 parallel test | Full web UI wrapper for Apache JMeter scripts, multi-cloud load injection, correlation engine. |
| **Loader.io** | SendGrid / Twilio (Legacy) | **Micro-SaaS scale** (~$150k ARR) | **$99.95 / month** (Pro tier, up to 100,000 clients, 10 min duration) | **10,000 clients / test**, 1-minute max duration, up to 2 URLs, 1 target host | Simple web-based stress testing, fast DNS verification, straightforward API endpoint checks. |

---

## Open Source Frameworks

| Project | GitHub Stars | License | Scripting Language | Core Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **[k6](https://github.com/grafana/k6)** | ~32k | AGPL-3.0 | JavaScript / ES6 | Go-powered CLI engine, modern JS/TypeScript developer experience, gRPC/HTTP/WebSocket/Browser support, thresholds. |
| **[Locust](https://github.com/locustio/locust)** | ~28k | MIT | Python | Code-as-tests in pure Python, lightweight coroutines (gevent), built-in interactive web UI and distributed worker mode. |
| **[Apache JMeter](https://github.com/apache/jmeter)** | ~9.6k | Apache-2.0 | GUI / Java / Groovy | The industry standard for protocol load testing (HTTP, JDBC, LDAP, JMS, SOAP), extensive plugin ecosystem. |
| **[Gatling](https://github.com/gatling/gatling)** | ~7k | Apache-2.0 | Java / Kotlin / Scala | High-performance asynchronous non-blocking engine built on Akka and Netty, expressive DSL, automated HTML reports. |
| **[Artillery (Core CLI)](https://github.com/artilleryio/artillery)** | ~8k | MPL-2.0 | YAML / JavaScript | Cloud-native load testing CLI, serverless AWS Lambda/Fargate execution, WebSocket/HTTP/Socket.io support. |

---

## Contributing

Contributions are welcome! Please read the contribution guidelines before submitting a pull request.
