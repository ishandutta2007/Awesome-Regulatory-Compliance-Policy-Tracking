# Awesome-Regulatory-Compliance-Policy-Tracking

# Awesome Regulatory Compliance & Policy Tracking

> A curated list of top Regulatory Compliance and Policy Tracking platforms — both SaaS/Hosted commercial GRC solutions and open-source alternatives for tracking regulations, managing policies, and evidencing compliance.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [ServiceNow GRC](#servicenow-grc)
  - [OneTrust](#onetrust)
  - [AuditBoard](#auditboard)
  - [LogicGate](#logicgate)
  - [MetricStream](#metricstream)
  - [Archer](#archer)
  - [Diligent HighBond](#diligent-highbond)
  - [Resolver](#resolver)
- [Open-Source Software](#-open-source-software)
  - [Probo](#probo)
  - [CISO Assistant](#ciso-assistant)
  - [Eramba](#eramba)
  - [SimpleRisk](#simplerisk)
  - [Comp AI](#comp-ai)
  - [OpenGRC](#opengrc)
  - [OSPAC](#ospac)
  - [federal-register-mcp](#federal-register-mcp)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Regulatory Compliance and Policy Tracking platforms. These are not open-source but are included as reference points for feature comparison.

### ServiceNow GRC
**Type:** Enterprise GRC within ServiceNow platform  
ServiceNow GRC integrates risk management, policy management, compliance tracking, and audit management directly into the ServiceNow platform. It is the natural choice for organizations already using ServiceNow for ITSM or ITAM, as GRC workflows operate on the same data model without external integration overhead. Pricing is quote-based and typically targets large enterprises.

### OneTrust
**Type:** Privacy and compliance management platform  
OneTrust is the dominant commercial privacy management platform, covering consent management, data mapping, privacy impact assessments, vendor risk, and policy management. It is frequently referenced as the commercial standard for privacy-focused compliance, with broad certification and regulatory framework support.

### AuditBoard
**Type:** Connected risk and compliance platform  
AuditBoard provides audit management, risk management, compliance management, and ESG reporting in a connected platform. It is positioned for internal audit and compliance teams wanting a modern alternative to legacy GRC suites, with strong visualization and workflow capabilities.

### LogicGate
**Type:** Risk and compliance process automation  
LogicGate provides a flexible platform for building risk and compliance processes, with a visual workflow builder and a library of pre-built applications for policy management, regulatory tracking, and control testing. Suited for organizations wanting customizable GRC workflows without heavy coding.

### MetricStream
**Type:** Enterprise GRC and quality management  
MetricStream provides enterprise GRC covering risk, compliance, audit, policy, and quality management. It is a long-standing commercial option for large organizations needing comprehensive governance across multiple domains.

### Archer
**Type:** Enterprise GRC (RSA)  
Archer (RSA) is a mature enterprise GRC platform covering risk management, compliance, policy management, and audit. It is often deployed in large, regulated organizations with complex governance requirements.

### Diligent HighBond
**Type:** GRC and audit analytics  
Diligent HighBond (formerly Galvanize) combines GRC with audit analytics, allowing organizations to track compliance, manage policies, and analyze data for anomalies. Suited for internal audit and compliance teams wanting data-driven governance.

### Resolver
**Type:** Risk and compliance management  
Resolver provides risk management, compliance tracking, and incident management with a focus on actionable intelligence. Positioned for organizations wanting a unified view of risk and compliance posture.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Regulatory Compliance and Policy Tracking tools. The open-source ecosystem spans **full GRC platforms with policy management**, **compliance automation platforms**, **risk registers**, and **specialized policy engines**.

### Probo
**Stack:** Go / PostgreSQL / GraphQL / Docker | **License:** ISC  
Probo is a comprehensive open-source GRC platform covering the full lifecycle: risk identification, control tracking, vendor risk, data privacy, access reviews, audit programs, and document approval workflows [citation:4]. For policy tracking specifically, it provides **versioned documents with approval quorums, electronic signatures, and PDF export**, alongside a **public compliance portal** with NDA management and certification publishing [citation:4]. Every entity is accessible via web console, `prb` CLI (44+ command groups), **270+ MCP tools** for AI agents, and GraphQL API, with policy-based RBAC and immutable audit logs [citation:4].  
**Best for:** Organizations wanting a self-hosted GRC platform with strong document/policy approval workflows and AI agent accessibility via MCP, under a permissive ISC license.

### CISO Assistant
**Stack:** Python / Django / Docker | **License:** Open Source  
CISO Assistant is a one-stop GRC platform covering risk management, AppSec, compliance and audit, TPRM, BIA, privacy, and reporting [citation:3]. It supports **150+ global frameworks** including ISO 27001, NIST CSF, SOC 2, CIS, PCI DSS, NIS2, DORA, GDPR, HIPAA, and CMMC, with **automatic control mapping** [citation:3]. It is actively developed (last updated August 2026) and recommended as a strong base platform for organizations building GRC capabilities due to its microservices architecture and API-first design [citation:6].  
**Best for:** Organizations wanting broad framework coverage with automatic control mapping and a modern, extensible architecture.

### Eramba
**Stack:** PHP / MySQL | **License:** Open Source (Community)  
Eramba is a well-established open-source GRC tool with comprehensive features for compliance, risk, and evidence management [citation:6]. It is best suited for organizations tackling multiple frameworks simultaneously, with 10 releases in the past year and 3,689+ downloads [citation:6]. It provides policy management, control tracking, and audit workflows.  
**Best for:** Organizations managing multiple compliance frameworks needing a proven, feature-rich GRC platform.

### SimpleRisk
**Stack:** PHP / MySQL | **License:** Open Source (Community)  
SimpleRisk is designed to get organizations "from zero to GRC in minutes" with quick deployment and an intuitive interface [citation:14]. It covers governance (policy management, regulatory framework integration with **250+ frameworks mapped to 1,250+ controls**), risk management, compliance (control testing, audit management, evidence collection), and incident management [citation:14]. It is trusted by hundreds of companies, particularly in healthcare, government, and technology [citation:14].  
**Best for:** Organizations wanting rapid GRC deployment with pre-mapped regulatory frameworks and an accessible interface.

### Comp AI
**Stack:** TypeScript / Node.js / Postgres | **License:** AGPLv3 (Community Edition)  
Comp AI is an open-source compliance platform targeting SOC 2, ISO 27001, HIPAA, and GDPR, positioned as a direct alternative to Vanta and Drata [citation:9]. Its **AI Policy Editor** allows users to draft and update security policies through natural language, with a diff viewer showing changes before acceptance [citation:9]. **Automated Evidence** lets users create recurring evidence collection automations via plain-language prompts. A **Device Agent** checks endpoints for disk encryption, antivirus, password policy, and screen lock compliance [citation:9]. The Community Edition is AGPLv3 and self-hostable, with a separate managed Cloud offering [citation:13].  
**Best for:** Startups and SMBs wanting automated compliance with AI-assisted policy editing and evidence collection, accepting the AGPLv3 license.

### OpenGRC
**Stack:** Web application | **License:** MIT  
OpenGRC is a cyber GRC web application intended for small businesses and teams, explicitly "not intended to replace large-scale GRC Platforms, but it just might for your use case" [citation:6]. Features include a simple interface designed for minimal training, quick imports of common security frameworks, ability to connect Standards/Controls/Implementations, internal and external audit capabilities, report generation for auditors, and intuitive dashboards [citation:6].  
**Best for:** Small businesses and teams wanting a lightweight, MIT-licensed GRC tool with framework imports and audit reporting, without enterprise complexity.

### OSPAC
**Stack:** Python / YAML policies | **License:** Open Source (PyPI)  
OSPAC (Open Source Policy as Code) is a **policy engine for automated OSS license compliance**, with all compliance logic, rules, and decisions defined in versionable YAML/JSON policy files rather than hardcoded [citation:1]. It provides SPDX license integration (700+ licenses), a compatibility engine, **obligation tracking with automated checklist generation**, and both CLI and Python API [citation:1]. Policies are stored in Git, reviewable via PR, testable, and auditable with clear decision lineage [citation:1].  
**Best for:** Engineering and legal teams needing automated open-source license compliance with policy-as-code, version-controlled rules, and auditable decisions.

### federal-register-mcp
**Stack:** Python / MCP Server | **License:** Open Source (PyPI)  
federal-register-mcp is a free, open-source **MCP server for the Federal Register API**, providing access to proposed rules, final rules, notices, executive orders, comment periods, and **regulatory tracking since 1994** [citation:7]. No API key is required, and it has been tested through nine audit rounds with 295 regression tests [citation:7]. It enables AI agents (Claude, ChatGPT) to query and track regulatory changes directly.  
**Best for:** Compliance and legal teams wanting AI-assisted tracking of US federal regulations, particularly for monitoring proposed and final rules affecting their industry.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Policy Management | Regulatory Frameworks | Self-Hosted | Best For |
|----------|---------|-------|-------------------|----------------------|-------------|----------|
| **ServiceNow GRC** | Proprietary | Cloud | ✅ | ✅ | ❌ | ServiceNow enterprises |
| **OneTrust** | Proprietary | Cloud | ✅ | ✅ Privacy-focused | ❌ | Privacy compliance |
| **Probo** | ISC | Go/Postgres | ✅ Versioned + approvals | ✅ Custom import | ✅ | GRC + policy + MCP |
| **CISO Assistant** | Open Source | Python/Django | ✅ | ✅ 150+ frameworks | ✅ | Broad framework coverage |
| **Eramba** | Open Source | PHP/MySQL | ✅ | ✅ Multiple | ✅ | Multi-framework GRC |
| **SimpleRisk** | Open Source | PHP/MySQL | ✅ | ✅ 250+ mapped | ✅ | Rapid GRC deployment |
| **Comp AI** | AGPLv3 | TypeScript/Postgres | ✅ AI editor | ✅ SOC 2/ISO/HIPAA/GDPR | ✅ | AI-assisted compliance |
| **OpenGRC** | MIT | Web app | (Light) | ✅ Framework imports | ✅ | Lightweight SMB GRC |
| **OSPAC** | Open Source | Python/YAML | ✅ Policy-as-code | OSS licenses | ✅ | License compliance |
| **federal-register-mcp** | Open Source | Python/MCP | ❌ | US Federal Register | ✅ | AI regulatory tracking |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Regulatory Compliance or Policy Tracking tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem **splits** between **full GRC platforms with policy management** (Probo, CISO Assistant, Eramba, SimpleRisk), **AI-assisted compliance automation** (Comp AI), **lightweight SMB tools** (OpenGRC), and **specialized tracking tools** (OSPAC for license compliance, federal-register-mcp for US regulatory tracking). **Probo** offers the most comprehensive open-source GRC coverage with versioned policy approvals and 270+ MCP tools for AI agent access [citation:4]. **CISO Assistant** provides the broadest framework support (150+) with automatic control mapping [citation:3]. **Comp AI** is the strongest open-source Vanta/Drata alternative with AI-assisted policy editing [citation:9].

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
