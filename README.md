# Awesome-API-Load-Performance-Testing

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **several entries in your list have no usable data**, and one pricing figure is dangerously misleading.

## The data problems

**"Postman Performance Testing"** exists as a feature (App, CLI, or Cloud runs; cloud requires a minimum of 10 virtual users) , but **no pricing for the performance feature itself** was surfaced. Postman's general plans are separate. Mark it "quote-only" or omit pricing.

**k6's "$0.15/month" figure is wrong.** That is **$0.15 per Virtual User Hour (VUh)** . A 100-VU test for one hour costs **$15**, not $0.15. Toolradar's own page misstates it as a monthly starting price . Do not repeat that error.

**Gatling Enterprise "€89/month"** is the Starter pack, billed annually . The Community Edition is free and self-hosted.

**NeoLoad "$20,000/year"** comes from a Software Advice comparison page , not NeoLoad's own pricing. Treat as indicative.

**OctoPerf "$649 one time"** comes from Software Advice . No plan information was available. Do not present it as a confirmed price.

**Loader.io** pricing page returned no plan figures—only FAQ text . Mark as "free plan available; paid tiers not surfaced."

**BlazeMeter** pricing is usable: Basic **$99/year** (1,000 concurrent users, 200 tests/year), Pro **$499/year** (5,000 concurrent users, 80,000 VUh/year), Unleashed quote-only .

**Artillery** pricing is usable: Free, Team **$199/month**, Business **$499/month** .

**Locust** appears only in a GitHub topics index —**no star count for the main repo was surfaced**, only secondary projects.

**Apache JMeter** README confirms it is open source and covers HTTP, SOAP/REST, FTP, JDBC, LDAP, JMS, SMTP, TCP, and more, with CLI/headless mode and HTML reports . **No star count.**

## What I recommend

**The open-source section is strong on substance but missing star counts:**

| Project | License | Verified feature detail |
|---|---|---|
| **k6** | Free OSS | JavaScript scripting, HTTP/WebSocket/gRPC/Browser, thresholds, scenarios, extensions, CI/Kubernetes  |
| **Apache JMeter** | Apache | Multi-protocol, headless mode, HTML reports, pluggable samplers  |
| **Gatling** | Free Community Edition | Self-hosted, extensible  |
| **Locust** | Open source | Python-based, active ecosystem  |

**The SaaS section has usable pricing for BlazeMeter and Artillery**, plus per-VUh pricing for k6 Cloud and a Starter tier for Gatling Enterprise. Postman, Loader.io, NeoLoad, and OctoPerf should be marked "quote-only" or "pricing not surfaced."

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not repeat the "$0.15/month" error for k6, fabricate star counts, or present Software Advice figures as vendor-confirmed pricing.
