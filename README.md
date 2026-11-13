# Awesome-Data-Governance-Risk-Compliance-GRC

## Top Data Governance, Risk & Compliance (GRC) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Enterprise Risk Management, Regulatory Compliance & Audit Automation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Governance, Risk & Compliance (GRC)**. These tools help organizations centralize risk registers, map controls to regulatory frameworks, automate evidence collection, and maintain audit-ready documentation across SOC 2, ISO 27001, GDPR, HIPAA, and industry-specific mandates.

**Examples** include ServiceNow GRC, MetricStream, AuditBoard, LogicGate, Riskonnect, RSA Archer, Diligent HighBond, OneTrust, LogicManager, and open-source alternatives like CISO Assistant and Eramba (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted GRC, open-source risk management, and community-driven compliance automation—ideal for organizations seeking data sovereignty and predictable costs over six-figure enterprise licensing. The open-source GRC landscape has matured significantly: **CISO Assistant** offers a modern microservices architecture with 30+ ready frameworks , **Eramba** provides comprehensive evidence management with active release cadence , and **ComplianceAsCode** delivers security compliance content for multiple platforms .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Starting Pricing Tier | Free Tier / Trial Limits | Description |
|---|---|---|---|---|
| **[ServiceNow GRC (IRM)](https://www.servicenow.com/)** | **~$159B–$219B market cap** (~$11.0B–$13.3B annual revenue) | **$125.00/operator/month** (Standard IRM bundle; Professional at $250/mo, Enterprise at $375/mo, Lite operators at ~$75/mo) | **Free Personal Developer Instance (PDI)** provided indefinitely via ServiceNow Developer Program (sandbox for development/testing; requires periodic login to prevent hibernation/reclamation) | Enterprise Integrated Risk Management (IRM) covering audit, risk, policy, and compliance applications across large enterprise environments. |
| **[Diligent HighBond](https://www.diligent.com/)** | **~$4B–$7B valuation** (Insight Partners / Clearlake / Blackstone; ~$200M+ ARR) | **$5,000.00/year** (Diligent One base platform listing on Capterra) | **14-day free trial** for specific AI/GovernAI modules; **30-day free trial** for ACL Analytics; core platform requires guided sales PoC | GRC platform with Enterprise Risk Management, Audit Management, and Vendor Risk modules tracking KPIs, KRIs, and KCIs. |
| **[OneTrust GRC](https://www.onetrust.com/)** | **$4.5B valuation** (~$500M+ ARR) | **$827.00/month** (entry single-domain CMP/Governance module; enterprise annual contracts typically start at $10,000/year) | **14-day free trial** (scoped PoC with limited admin seats, restricted test inventory/records, and DAUV traffic limits) | Privacy, third-party risk, and trust intelligence GRC platform featuring automated compliance assessments and data mapping. |
| **[AuditBoard](https://www.auditboard.com/)** | **$3.0B valuation** (acquired by Hg in 2024; ~$200M+ ARR) | **$20,000.00/year** (starting baseline tier; median contract spend ~$45,947/year on Vendr) | **Sales-guided Proof of Concept (PoC) only**; no self-service free trial or permanent free tier | Category leader for internal audit, SOX compliance, and controls management with automated workflows and audit trails. |
| **[Druva GRC](https://www.druva.com/)** | **$2.0B valuation** (~$200M+ ARR) | **$8.00/month** (entry listing on Software Advice/Capterra; data protection tiers scale by protected workloads/capacity) | **30-day free trial** (up to 60 days upon tenant evaluation extension; full feature access without upfront credit card) | Governance, risk, and compliance capabilities within Druva's cloud data protection platform focused on data resilience and information governance. |
| **[RSA Archer (Archer IRM)](https://www.archerirm.com/)** | **~$1.38B valuation** (Cinven acquisition; ~$220M annual revenue) | **$671.31/month** (single monthly subscription license via CDW-G list) | **15-day free trial** for select Archer Exchange utility add-ons; core platform requires vendor-led guided demo/PoC | Fixture in banking, insurance, and highly regulated sectors requiring deep, auditable integrated risk management across 7 solution areas. |
| **[Riskonnect](https://www.riskonnect.com/)** | **~$1.0B+ enterprise valuation** (TA Associates / Thoma Bravo; ~$150M–$250M+ ARR) | **$900.00/user/year** (entry ERM 250-user band tier; $75.00/user/month equivalent) | **Sales-guided Proof of Concept (PoC) only**; no self-service free trial or permanent free tier | Enterprise risk management and integrated risk platform (IRM) spanning ERM, claims management, and third-party risk. |
| **[MetricStream](https://www.metricstream.com/)** | **~$480M valuation** (Clearlake Capital / Blue Torch Capital; ~$100M+ ARR) | **$75,000.00/year** (entry small-enterprise deployment floor per SelectHub benchmarks; ~$6,250.00/month equivalent) | **Custom sales-led sandbox evaluation only**; no self-service free trial or permanent free tier | Enterprise GRC suite for large regulated organizations covering enterprise risk, CyberGRC, and regulatory compliance. |
| **[LogicGate](https://www.logicgate.com/)** | **~$160M+ valuation** (backed by PSG; ~$49M–$59M ARR) | **$13,000.00/year** (entry application tier; median spend ~$52,600/year on Vendr; ~$1,083.33/month equivalent) | **Sales-guided Proof of Concept (PoC) only**; no self-service free trial or permanent free tier | Mid-market GRC built on the Risk Cloud no-code workflow builder for custom risk assessments and compliance processes. |
| **[LogicManager](https://www.logicmanager.com/)** | **~$10M–$20M valuation** (bootstrapped/profitable; ~$6.3M–$7.7M annual revenue) | **$10,000.00/year** (entry package tier; value-based Jobs-to-be-Done pricing including unlimited users) | **90-day unconditional satisfaction guarantee** with guided trial onboarding; no permanent free tier | ERM and GRC software offering fixed all-inclusive Jobs-to-be-Done pricing with unlimited user seats and dedicated analyst support. |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[CISO Assistant](https://github.com/intuitem/ciso-assistant-community)** | [![Stars](https://img.shields.io/github/stars/intuitem/ciso-assistant-community?style=social&color=white)](https://github.com/intuitem/ciso-assistant-community/stargazers) | **The most recommended open-source GRC base platform.** Community Edition self-hosted via Docker. **30+ ready frameworks** including ISO 27001, NIST CSF, SOC 2, and custom controls. Controls are reusable objects connecting risks to frameworks. Role-based access, assessment history, reporting views. **Microservices-based architecture** (backend, frontend, dispatcher) ideal for AI integration. API, n8n, MCP, and Kafka integration options . |
| **[Eramba](https://github.com/eramba/eramba)** | [![Stars](https://img.shields.io/github/stars/eramba/eramba?style=social&color=white)](https://github.com/eramba/eramba/stargazers) | **Comprehensive open-source GRC with evidence management.** 3,689+ downloads last year, **10 releases in the past year**—active development cadence. Best for organizations tackling multiple frameworks simultaneously. Includes risk management, compliance, policy management, and audit capabilities . |
| **[ComplianceAsCode](https://github.com/ComplianceAsCode/content)** | [![Stars](https://img.shields.io/github/stars/ComplianceAsCode/content?style=social&color=white)](https://github.com/ComplianceAsCode/content/stargazers) | **Security compliance content for multiple platforms** (2.4k stars, 734 forks). Very active (last update Feb 2024). Provides automated compliance checks and remediation content for various operating systems and platforms. Excellent for training AI models on structured compliance data . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[SimpleRisk](https://github.com/simplerisk/simplerisk)** | [![Stars](https://img.shields.io/github/stars/simplerisk/simplerisk?style=social&color=white)](https://github.com/simplerisk/simplerisk/stargazers) | Quick deployment, intuitive interface. **Trusted by hundreds of companies**. Regular updates. Best for healthcare, government, and technology sectors . |
| **[GovReady-Q](https://github.com/GovReady/govready-q)** | [![Stars](https://img.shields.io/github/stars/GovReady/govready-q?style=social&color=white)](https://github.com/GovReady/govready-q/stargazers) | DevSecOps integration with automated assessments. 53+ GitHub forks. Active development. Best for teams needing fast authorization processes . |
| **[auditree](https://github.com/openmainframeproject/auditree-framework)** | [![Stars](https://img.shields.io/github/stars/openmainframeproject/auditree-framework?style=social&color=white)](https://github.com/openmainframeproject/auditree-framework/stargazers) | Compliance automation and evidence collection. 64 stars, 24 forks. Moderate activity. Best for DevSecOps teams wanting to automate compliance . |
| **[OpenGRC](https://github.com/topics/grc)** | — | Simple interface with quick framework imports. Best for small businesses and teams new to GRC. Exact repository URL not confirmed in search results . |
| **[gapps](https://github.com/topics/grc)** | — | Multiple framework support with WYSIWYG editor. Best for organizations needing to track progress against various frameworks. Exact repository URL not confirmed . |

**Frameworks for building custom systems**: Combine **CISO Assistant** for structured framework mapping with modern microservices architecture, **Eramba** for comprehensive evidence management across multiple frameworks, and **ComplianceAsCode** for automated compliance content—all deployable via Docker without six-figure enterprise licensing. For AI-enhanced GRC, CISO Assistant's microservices architecture is the recommended foundation for integrating predictive analytics and NLP-based evidence collection .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- GRC platforms handle audit evidence, risk registers, and regulatory documentation; enforce role-based access, immutable audit logs, and compliance with applicable data protection regulations.
- **Enterprise GRC pricing is genuinely six-figure territory.** MetricStream starts at **$75,000/year** and scales to **$1M** for large enterprises . ServiceNow IRM charges **$125–$375/operator/month** with a critical distinction between full operators and **Lite operators (~$75/month)** for attestation-only users—misclassifying 400 attesters as full operators costs **~$1.2M/year vs. $360K/year** . AuditBoard median is **~$45,947/year** but buyers who evaluate alternatives secure **15–30% lower pricing** . **Open-source GRC is viable but requires engineering effort.** CISO Assistant is the recommended base platform for AI-enhanced GRC development, with modern microservices architecture and 30+ ready frameworks . Eramba offers comprehensive evidence management with active development . Validate control mappings and evidence quality against your auditor's expectations before relying on any tool for certification.

---

**Made for compliance officers, risk managers, internal auditors, and developers building governance infrastructure.**  
Let's make data governance, risk, and compliance more open, automated, and audit-ready.
