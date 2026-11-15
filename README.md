# Awesome-Enterprise-Data-Governance-Information-Management

# Top Enterprise Data Governance & Information Management Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Data Catalogs, Policy Enforcement & Self-Hosted Metadata Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Data Governance & Information Management**. These tools help organizations discover, catalog, classify, and govern data assets—ensuring the right people access the right data while maintaining compliance and enabling AI initiatives with trusted data.

**Examples** include Collibra, Alation, Microsoft Purview, Informatica, Ataccama, Privacera (Trust3 AI), Securiti, BigID, Apache Atlas, and DataHub (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted metadata management, open-source data catalogs, and community-driven governance—ideal for organizations seeking data sovereignty and avoiding per-asset or per-user enterprise licensing. The open-source landscape is anchored by **Apache Atlas** (the Hadoop-era standard for metadata and lineage) and **DataHub** (LinkedIn's modern, real-time metadata platform), with **OpenMetadata** providing a unified alternative .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Collibra](https://www.collibra.com/)** | **The enterprise standard for governed data foundations.** Centralizes policies, automates workflows, and creates a single source of truth for business terminology. Features AI-driven stewardship (auto-generating descriptions and classifying assets), embedded Slack/Teams collaboration, and a Data Helpdesk for issue tracking . **Positioned for data-intensive organizations needing long-term scalable governance**—the company itself notes it is "not the cheapest or fastest-to-implement solution" . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Alation](https://www.alation.com/)** | **Pioneer of the data catalog market with an Agentic Platform for AI.** Agents automate documentation, resolve incomplete metadata, and apply governance policies. **AI Agent SDK with Anthropic MCP support** lets organizations build custom agents on top of Alation's metadata graph. **40% of the Fortune 100** are customers . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Microsoft Purview](https://www.microsoft.com/en-us/security/business/microsoft-purview)** | Integrated data governance with **Data Map** (scanning, classification, lineage) and **Unified Catalog** (governance domains, data products, CDEs). **Pricing model**: pay-as-you-go based on governed assets (~$0.0165/asset/day); **Data Map and scanning are free if Unified Catalog governance features are not used** . | Pay-as-you-go (~$0.0165/governed asset/day); Data Map free without Unified Catalog | No free tier for governed assets; Data Map scanning free |
| **[Informatica Cloud Data Governance](https://www.informatica.com/)** | Enterprise data governance and catalog within the IDMC platform. **Consumption-based IPU (Informatica Processing Unit) pricing**—no public dollar starting price; quote required based on sources and expected usage . | Quote-only (IPU consumption-based) | No free tier; demo via sales |
| **[Ataccama ONE](https://www.ataccama.com/)** | Unified platform for the data trust lifecycle. **Pricing determined by three dimensions**: named users (consumer/viewer users are **unlimited at every tier**), data objects managed, and **active DQ configurations** (executed at least once in 90 days). **Limits are soft**—exceeding them doesn't interrupt operations or trigger retroactive charges . | Quote-only (tiered by users, data objects, active DQ configs) | No free tier; demo via sales |
| **[Privacera (Trust3 AI)](https://privacera.com/)** | **Agentic platform for data and AI governance.** Positions itself as the "Trust layer" bridging traditional data governance and AI policy enforcement. Trust agents govern data and AI with enterprise-grade security . | Quote-only | No free tier; demo via sales |
| **[Securiti](https://securiti.ai/)** | Unified Data Command Center for data security, privacy, governance, and AI safety. **Self-serve pricing available**: Pro **$299/month** (was $3,588/year, now $3,050/year); Business **$599/month** (was $7,188/year, now $6,110/year) . | Pro: **$299/month** (annual $3,050); Business: **$599/month** (annual $6,110) | **Free tier** available for small businesses |
| **[BigID](https://bigid.com/)** | Data intelligence platform for discovery, classification, and privacy compliance across 100+ sources. **C4 Discovery Foundation Package required** for any additional applications: **$525,000 one-time** (3-year term, >100 data sources). Purview integration: **$35,000/year** . | **$525,000** (C4 Foundation, 3-year) | No free tier; enterprise sales only |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Apache Atlas](https://github.com/apache/atlas)** | [![Stars](https://img.shields.io/github/stars/apache/atlas?style=social&color=white)](https://github.com/apache/atlas/stargazers) | **The longest-standing open-source metadata and governance platform.** Built for Hadoop-era data platforms with **data classification, centralized auditing, search/lineage, and a security/policy engine** . Created by engineers from Aetna, JPMorgan Chase, Merck, SAS, Schlumberger, and Target; now used across industries for compliance on individual data platforms. **Integration with Apache Ranger** adds tag-based access control. **Trade-offs**: focused on Hadoop ecosystem; UI is dated compared to modern catalogs . **Best for organizations with existing Hadoop investments** needing a proven metadata backbone. |
| **[DataHub](https://github.com/datahub-project/datahub)** | [![Stars](https://img.shields.io/github/stars/datahub-project/datahub?style=social&color=white)](https://github.com/datahub-project/datahub/stargazers) | **LinkedIn's modern open-source metadata platform—the leading alternative to commercial catalogs.** Real-time metadata ingestion, **search, lineage, and governance** across databases, warehouses, and BI tools. **API-first design** with GraphQL and REST. Active community and rapid development cadence. **Trade-offs**: operational complexity (Kafka, Elasticsearch, Neo4j dependencies); best suited for organizations with platform engineering capacity . **Best for teams wanting a modern, actively-developed catalog** without per-asset licensing. |
| **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)** | [![Stars](https://img.shields.io/github/stars/open-metadata/OpenMetadata?style=social&color=white)](https://github.com/open-metadata/OpenMetadata/stargazers) | **Unified open-source metadata platform with column-level lineage and data contracts.** Apache-2.0. Centralized metadata store with **data discovery, lineage, and governance workflows**. Supports **sensitive data classification** and **data contracts** (machine-readable schema and quality guarantees). **Trade-offs**: younger project than Atlas or DataHub; connector ecosystem still maturing . **Best for teams wanting a single open-source platform** covering catalog, lineage, and quality. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[OpenDLP](https://github.com/ezra100/OpenDLP)** | [![Stars](https://img.shields.io/github/stars/ezra100/OpenDLP?style=social&color=white)](https://github.com/ezra100/OpenDLP/stargazers) | **Open-source data loss prevention scanner** for identifying sensitive data (credit cards, SSNs, PII) across file shares and databases. **Discovery layer only**—complements governance platforms by finding where sensitive data actually lives . **Best for preliminary sensitive data discovery** before cataloging. |

**Frameworks for building custom systems**: Choose **Apache Atlas** for Hadoop-centric metadata with proven compliance capabilities , **DataHub** for a modern, actively-developed catalog with real-time lineage , or **OpenMetadata** for a unified platform with data contracts and classification —all without per-asset or per-governed-asset fees that compound as your data estate grows.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Data governance platforms handle sensitive metadata, classification labels, and access policies; enforce role-based access, audit logging, and compliance with applicable data protection regulations. **Misclassification can expose sensitive data to unauthorized users or AI systems.**
- **Pricing models vary dramatically and hidden costs compound.** **Collibra and Alation are quote-only enterprise platforms** with implementations that require significant organizational commitment—Collibra explicitly notes it is "not the cheapest or fastest-to-implement solution" . **Microsoft Purview's pay-as-you-go model** charges only for governed assets (~$0.0165/asset/day), and **Data Map scanning is free if you avoid Unified Catalog features** . **BigID requires a $525,000 Foundation package** before any additional applications can be purchased . **Securiti publishes transparent self-serve pricing** (Pro $299/month) making it the most accessible commercial entry point . **Open-source catalogs have different trade-offs**: Apache Atlas is proven but Hadoop-focused and dated ; DataHub is modern and actively developed but requires significant infrastructure (Kafka, Elasticsearch, Neo4j) ; OpenMetadata is unified but younger . **Validate connector coverage, operational capacity, and whether you need a Hadoop-era backbone (Atlas) or a modern catalog (DataHub)** before committing.

---

**Made for data governance teams, CDOs, and organizations building trusted data foundations.**  
Let's make enterprise data governance more open, discoverable, and trustworthy.
