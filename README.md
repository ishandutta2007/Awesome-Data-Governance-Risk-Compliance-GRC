# Awesome-Data-Governance-Risk-Compliance-GRC

# Top Data Governance, Risk & Compliance (GRC) Ecosystem

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

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Druva GRC](https://www.druva.com/)** | Governance, risk, and compliance capabilities within Druva's cloud data protection platform. Focused on data resilience, compliance management, and risk control for backup and information governance—not a full enterprise GRC suite . | Paid version starts at **$8.00/month** (Software Advice listing)  | **Free trial** available; no free version  |
| **[ServiceNow GRC (IRM)](https://www.servicenow.com/)** | Enterprise Integrated Risk Management (formerly GRC) sold as tiered bundles: **IRM Standard ($125/operator/month), Professional ($250), Enterprise ($375)**. Covers audit, risk, policy, and compliance applications. **IRM Lite operators (~$75/month)** can respond to attestations and questionnaires at lower cost. Published third-party estimates of $150–$300/user/month are consistent with G-Cloud list prices . | Standard: **$125/operator/month**; Professional: $250; Enterprise: $375  | No free tier; demo via sales |
| **[MetricStream](https://www.metricstream.com/)** | Enterprise GRC suite for large regulated organizations. SelectHub lists starting price at **$75,000/year** (quote-based), with free trial available on request. Industry analysis shows small-enterprise deployments at $75K–$150K, scaling to **$750K–$1M** for large enterprises. Admin seats $200–$2,500/user/app . | **$75,000/year** (SelectHub); small-enterprise $75K–$150K  | **Free trial** (request via SelectHub)  |
| **[AuditBoard](https://www.auditboard.com/)** | Category leader for internal audit, SOX compliance, and controls management. Vendr benchmark shows typical annual contract around **$45,947**. Implementation services add **10–25%** to first-year cost; renewal escalations typically **3–7%/year**. Buyers who evaluate alternatives secure **15–30% lower pricing** than initial quotes . | ~**$45,947/year** (Vendr median)  | No free tier; demo via sales |
| **[LogicGate](https://www.logicgate.com/)** | Mid-market GRC with no-code workflow builder. Median observed deployment ~**$52,600**; 4 apps + 5 power users ~$88,600 (from prior research). Positioned as configurable risk workflows without enterprise price tags. | Median ~**$52,600**  | No free tier; demo via sales |
| **[Riskonnect](https://www.riskonnect.com/)** | Enterprise risk management platform with modular pricing. **ERM: $900–$1,600/user/year** (250-user band); **TPRM: $1,800–$2,400/user** plus data feed fees; **Internal Audit: $1,500–$2,100/user**. Sales teams open with 10–15% off list and escalate to 38–42% for multi-year commitments . | ERM: **$900–$1,600/user/year**  | No free tier; demo via sales |
| **[RSA Archer](https://www.archerirm.com/)** | Fixture in banking, insurance, and heavily regulated sectors requiring deep, auditable integrated-risk management. CDW-G lists a **1-month subscription license at $671.31** (single license, indicative of per-user monthly cost). Seven solution areas including audit, IT risk, third-party governance, and regulatory compliance . | ~**$671.31/month** per license (CDW-G)  | No free tier; demo via sales |
| **[Diligent HighBond](https://www.diligent.com/)** | GRC platform with Enterprise Risk Management, Audit Management, and Vendor Risk modules. Capterra comparison lists starting price at **$5,000/year** (Diligent One Platform). Monitors KPIs, KRIs, and KCIs with threshold alerts. | **$5,000/year** (Capterra listing)  | No free tier; demo via sales |
| **[OneTrust GRC](https://www.oneTrust.com/)** | Privacy and third-party risk-centered GRC platform. **No public pricing**—all custom-quoted. Vendr data (278 transactions): **median annual spend ~$10,514**. Single-domain CMP from **$827/month**; full Privacy Essentials Suite **$3,680/month**. Enterprise GRC quoted separately . | Median **~$10,514/year** (Vendr); CMP from $827/month  | No free tier; demo via sales |
| **[LogicManager](https://www.logicmanager.com/)** | ERM software with **Job-to-be-Done pricing**: unlimited users (internal and external), fixed all-inclusive price covering licensing, advisory service, and onboarding. **90-day satisfaction guarantee**. Guided onboarding with dedicated specialist and ongoing advisory analyst . | Quote-only (fixed all-inclusive pricing)  | **90-day unconditional money-back guarantee**  |

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
