# Awesome-Enterprise-Data-Governance-Information-Management

## Top Enterprise Data Governance & Information Management Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Data Catalogs, Policy Enforcement & Self-Hosted Metadata Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Data Governance & Information Management**. These tools help organizations discover, catalog, classify, and govern data assets—ensuring the right people access the right data while maintaining compliance and enabling AI initiatives with trusted data.

**Examples** include Collibra, Alation, Microsoft Purview, Informatica, Ataccama, Privacera (Trust3 AI), Securiti, BigID, Apache Atlas, and DataHub (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted metadata management, open-source data catalogs, and community-driven governance—ideal for organizations seeking data sovereignty and avoiding per-asset or per-user enterprise licensing. The open-source landscape is anchored by **Apache Atlas** (the Hadoop-era standard for metadata and lineage) and **DataHub** (LinkedIn's modern, real-time metadata platform), with **OpenMetadata** providing a unified alternative .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global enterprise data governance and information management market is estimated at **$4.6B – $5.2B in 2025/2026** and is expanding at a ~16–22% CAGR driven by enterprise AI adoption, regulatory mandates (e.g., GDPR, DORA, CCPA), and cloud migrations. Market concentration is **moderately concentrated to medium fragmented**: it features a dual structure where massive hyperscalers (Microsoft) and established legacy leaders (Informatica) anchor cross-enterprise standards, while specialized pure-play platforms (Collibra, Alation, Securiti) capture dedicated governance, catalog, and AI safety workloads without any single player establishing winner-take-all dominance.

## SaaS/Hosted Platforms

| Product | Valuation / Revenue | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---|---|---|---|---|
| **[Microsoft Purview](https://www.microsoft.com/en-us/security/business/microsoft-purview)** | ~$3.89 Trillion (Market Cap) | Integrated data governance with **Data Map** (scanning, classification, lineage) and **Unified Catalog** (governance domains, data products, CDEs). **Pricing model**: pay-as-you-go based on governed assets (~$0.0165/asset/day); Data Map and scanning are free if Unified Catalog governance features are not used. | Pay-as-you-go starting at ~$0.0165/governed asset/day (~$0.50/asset/month); Data Map scanning included free | **Free tier**: Up to 1,000 annotated assets lifetime (90-day inactivity purge); **Free trial**: 90-day trial with 25 Microsoft Purview Suite licenses for E3 customers |
| **[Informatica Cloud Data Governance](https://www.informatica.com/)** | ~$7.64 Billion (Market Cap) | Enterprise data governance and catalog within the IDMC platform. Consumption-based IPU (Informatica Processing Unit) model across cataloging, metadata scanning, and policy enforcement. | Starting floor at ~$131,760/year (12-month contract for 120 IPUs/month on AWS Marketplace, ~$91.50/IPU/month) | **No direct free tier** for CDGC module; **Free trial**: 30-day trial offered on companion IDMC modules (Cloud Data Integration & Data Quality) |
| **[Collibra](https://www.collibra.com/)** | ~$5.25 Billion (Valuation) | **The enterprise standard for governed data foundations.** Centralizes policies, automates workflows, and creates a single source of truth for business terminology. Features AI-driven stewardship, embedded Slack/Teams collaboration, and a Data Helpdesk for issue tracking. Positioned for data-intensive organizations needing long-term scalable governance. | Starting floor at ~$170,000/year (12-month base enterprise subscription on AWS Marketplace) | **No free tier**; **Free trial**: 20-day trial for Collibra Data Quality & Observability module only, guided interactive tours available on site |
| **[Securiti](https://securiti.ai/)** | ~$1.725 Billion (Valuation / Acquisition) | Unified Data Command Center for data security, privacy, governance, and AI safety. Features contextual AI firewalling, DSPM, and automated compliance. Acquired by Veeam Software in 2025. | Pro plan starting at $299/month ($3,050/year billed annually); Business plan starting at $599/month ($6,110/year billed annually) | **Free tier**: Permanent free plan for AI Security / AI Firewall with 1,000 requests/month; **Free trial**: 7-day Pro trial for SecuritiGPT (50 chats/day, 4 tool uses/day) |
| **[Alation](https://www.alation.com/)** | ~$1.70 Billion (Valuation) | **Pioneer of the data catalog market with an Agentic Platform for AI.** Agents automate documentation, resolve incomplete metadata, and apply governance policies. AI Agent SDK with Anthropic MCP support lets organizations build custom agents on top of Alation's metadata graph. 40% of the Fortune 100 are customers. | Starting floor at ~$60,000/year (12-month base package on AWS Marketplace; full enterprise deployments typically scale $100,000+/year) | **No free tier**; **Free trial**: Custom sales-scoped evaluation / Proof of Concept (PoC) pilot under formal trial agreements; interactive tours available online |
| **[BigID](https://bigid.com/)** | ~$1.00 Billion (Valuation) | Data intelligence platform for discovery, classification, and privacy compliance across 100+ sources. Advanced discovery layer mapping structured, unstructured, and streaming data for privacy frameworks and DSPM. | C4 Discovery Foundation Package starts at $525,000 (3-year contract for up to 100 data sources); optional Purview connector at $35,000/year | **No free tier**; **Free trial**: Free Data Risk Assessment (specialist-led scan of targeted AWS/M365 environment) or customized enterprise PoC pilot |
| **[Ataccama ONE](https://www.ataccama.com/)** | ~$550 Million (Valuation) | Unified platform for the data trust lifecycle spanning cataloging, data quality, and MDM. Unlimited read-only consumer seats across all license levels; cost is calculated across authoring named users, managed data objects, and active DQ rules. | Starting floor ranges between ~$118,000 – $133,000/year for entry enterprise deployments (placeholder $1.00 unit on AWS Marketplace requires custom contract) | **No free tier**; **Free trial**: Guided Proof of Concept / sandbox evaluation via sales, plus free access to Ataccama Academy sandbox training labs |
| **[Privacera (Trust3 AI)](https://privacera.com/)** | ~$250M – $500M (Valuation) | **Agentic platform for data and AI governance.** Positions itself as the "Trust layer" bridging traditional data governance and AI policy enforcement. Trust agents govern data and AI with enterprise-grade security and unified Apache Ranger-compatible policies. | PrivaceraCloud Starter Pack starts at ~$100,000/year (12-month contract on AWS Marketplace) | **No free tier**; **Free trial**: 30-day free trial available for PrivaceraCloud on AWS Marketplace (software license included; user covers AWS infrastructure) |

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
