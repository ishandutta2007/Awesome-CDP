# Awesome-CDP

## Top Customer Data Platform (CDP) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Customer Data Unification, Identity Resolution, Audience Segmentation & Data Activation*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Data Platforms (CDPs)**. These tools help organizations collect, unify, and activate customer data across channels, creating a single customer view for marketing, analytics, and personalization.



**Examples** include Segment, mParticle, Treasure Data, Tealium, Zeotap, ActionIQ, Blueshift, Hightouch, RudderStack, and Lytics (the category leaders).



**Open-source emphasis**: The open-source CDP ecosystem is **concentrated in the warehouse-native and data pipeline segment**. **RudderStack** is the most prominent open-source alternative to Segment, with 4,400+ stars and a privacy-focused architecture that routes data directly to your warehouse . **Tracardi** offers an API-first, self-hosted CDP . **LEO CDP** provides an AI-first framework for building custom CDP infrastructure . Note that **Zeotap's Open CDP** (launched September 2026) is a commercial offering that runs on open-source compute and customer-owned lakehouse, but is not itself open-source . This section focuses on truly open-source, self-hostable solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Segment](https://segment.com/)**

  The CDP category pioneer (now Twilio Segment). Developer-first event collection and routing with 450+ connectors. Strong schema governance via Protocols and identity resolution via Unify. MTU-based pricing escalates sharply at scale, with enterprise contracts exceeding $500K annually .



- **[mParticle](https://www.mparticle.com/)**

  Mobile-first CDP known for low total cost of ownership and strong mobile SDKs. Acquired by Rokt in January 2025 for $300M, repositioning toward enterprise with GenAI roadmap .



- **[Treasure Data](https://www.treasuredata.com/)**

  Hybrid CDP supporting both Complete Mode and Composable Mode. Sub-second latency for profile lookups. Pricing is notably high, with Gartner reporting sample scenarios nearly double the second-highest response .



- **[Tealium](https://tealium.com/)**

  CDP with deep tag management heritage and 1,200+ prebuilt integrations. Strong in regulated verticals with HIPAA-compliant private cloud. Dropped from Gartner Leader to Challenger in 2026 amid slowing ARR growth .



- **[Zeotap](https://zeotap.com/)**

  AI-powered CDP with flexible deployment across packaged, composable, and hybrid models. Launched **Open CDP** (September 2026) enabling deployment on customer-owned lakehouse with Apache Spark and Iceberg tables for data sovereignty .



- **[ActionIQ](https://www.actioniq.com/)**

  Enterprise CDP acquired by Uniphore in late 2024. Strong warehouse-native architecture with zero-copy querying and granular segmentation. Strategic direction uncertain under new ownership .



- **[Blueshift](https://blueshift.com/)**

  SmartHub CDP with AI-powered cross-channel marketing. Combines customer data unification with journey orchestration and predictive segmentation.



- **[Hightouch](https://hightouch.com/)**

  Composable, warehouse-native CDP leader in Gartner 2026. Eliminates data replication latency and cost by activating data directly from the warehouse. Positions data engineering as customer responsibility .



- **[RudderStack](https://rudderstack.com/)**

  Open-source core with commercial cloud offering. See Open-Source section below for details.



- **[Lytics](https://lytics.com/)**

  Composable CDP acquired by Contentstack (completed late 2024). Focuses on customer data activation integrated with content management.



## Open-Source GitHub Projects



- **[RudderStack](https://github.com/rudderlabs/rudder-server)**

  The most mature open-source CDP. Privacy and security focused Segment-alternative written in Go. **4,400+ stars** . Warehouse-first architecture routes event data directly to your data warehouse without storing it on RudderStack's infrastructure. Supports 200+ destinations, Python/JavaScript transformations, reverse ETL, and cloud/device mode. **Key limitations**: No marketer self-service (requires data engineers for audience building), steep learning curve, no native identity graph, limited RBAC . **MIT / Open source**.



- **[Tracardi](https://github.com/tracardi/tracardi)**

  Composable API-first CDP for companies needing an inexpensive, self-hosted solution. **566+ stars**, Python-based . API-first architecture with ElasticSearch backend. Open-source license (other). Active development.



- **[LEO CDP](https://github.com/trieu/leo-cdp-framework)**

  Open-source AI-first CDP framework for building customizable, self-hosted CDP infrastructure. Features omnichannel data collection, real-time Customer 360, ML-based segmentation (RFM, CLV, churn prediction), behavioral tracking, and agentic AI/LLM-powered personalization. Docker/Kubernetes support, Prometheus/Grafana monitoring, RBAC, audit logs. **Open source** .



### Additional Strong Open-Source Options



- **Warehouse-Native Alternatives**: **Census** and **Hightouch** (commercial but composable), **Grouparoo** (open-source reverse ETL, now archived).

- **ELT/Ingestion**: **Airbyte** (600+ connectors, open-source ELT for data ingestion, 21,000+ stars), **Meltano** (open-source ELT).

- **Customer Data Framework**: **Pimcore Customer Data Framework** (PHP, 82 stars) adds customer data management to Pimcore PIM/MDM .



**Frameworks for building custom systems**: Combine **RudderStack** for event collection and warehouse routing, **Tracardi** for API-first profile management, and **LEO CDP** for AI-powered segmentation. Add **Airbyte** for ELT ingestion and your existing data warehouse (Snowflake, BigQuery, Redshift) as the storage layer.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- CDPs handle sensitive customer data; ensure compliance with GDPR, CCPA, and relevant data protection regulations.

- **Open-source reality**: **RudderStack** is the only production-grade open-source CDP with significant adoption, but it requires data engineering ownership and lacks marketer-friendly UI . **Tracardi** and **LEO CDP** are viable for technical teams building custom solutions. For marketing-led organizations requiring self-service audience building, commercial platforms (Segment, Hightouch, Tealium) remain the primary choice.
