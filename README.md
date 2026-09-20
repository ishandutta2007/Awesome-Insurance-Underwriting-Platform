# Awesome-Insurance-Underwriting-Platform

Top Insurance Underwriting Platforms Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Risk Assessment, Policy Rating, Underwriting Automation & Decision Engines
Last updated: September 2026

This repository tracks notable SaaS platforms and open-source projects for Insurance Underwriting. These tools help insurers, MGAs, and brokers automate risk assessment, policy pricing, coverage eligibility, and underwriting decision workflows.

Examples include Cytora, Send Technology, Guidewire Underwriting, Duck Creek Underwriting, INSTANDA, Artificial Labs, Socotra, EIS Underwriting, Sapiens Underwriting, and Majesco Underwriting (the category leaders).

Open-source emphasis: This section is heavily expanded with every major active project for self-hosting, custom rating engines, and transparent underwriting logic — ideal for insurers, insurtech builders, and actuaries who need full control over pricing models and risk rules without proprietary vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

How to Contribute

Disclaimer

SaaS/Hosted Platforms

Cytora
Digital risk processing platform for commercial insurance. Ingests and structures external data to automate underwriting decisions and risk assessment.

Send Technology
Underwriting workbench for commercial and specialty insurance. Streamlines risk submission, triage, and decision-making with configurable workflows.

Guidewire Underwriting
Underwriting management component within Guidewire InsuranceSuite. Handles submission intake, risk assessment, quoting, and policy issuance for P&C insurers.

Duck Creek Underwriting
Underwriting module within Duck Creek's suite for P&C insurers. Provides rating, rules, and workflow automation for personal and commercial lines.

INSTANDA
No-code insurance platform enabling insurers to design, build, and launch products rapidly. Includes underwriting rules, rating, and customer portals.

Artificial Labs
Contract builder and underwriting platform for specialty insurance. Digitizes complex contracts and automates risk placement workflows.

Socotra
Cloud-native, API-first core insurance platform. Provides policy administration, rating, and underwriting capabilities for modern insurers.

EIS Underwriting
Underwriting and policy administration component within EIS's core insurance platform. Supports life, health, and P&C lines with configurable rules.

Sapiens Underwriting
Underwriting solution within Sapiens' insurance suite. Provides risk assessment, rating, and automated decisioning for insurers.

Majesco Underwriting
Underwriting management for P&C and life insurers. Integrates with Majesco's core suite for quote, rate, and issue workflows.

Open-Source GitHub Projects

Rules-Engine (Underwriter)
Production-ready, domain-extensible underwriting rules engine built with Spring Boot and Drools. Features modular rule domains for auto, life, mortgage, and travel insurance, client-specific configuration, Docker deployment, and a REST API for decisioning. Supports adding new domains and rules via Maven modules. Open source. -
1

ratingtables
Table-driven insurance rating engine for R. Executes ordered rating specifications against factor tables, supports coverage-specific plans, entity aggregation, trace output for auditing, and custom rating functions. MIT licensed. Published on CRAN. -
3
-
13
-
18

insurancerating
R package for actuarial risk classification and tariff construction. Provides GAM-based risk factor modeling, evolutionary tree binning for continuous variables, and GLM tariff class construction. Based on peer-reviewed actuarial research. -
8

AI Underwriting System
Full-stack AI underwriting system with 60+ REST API endpoints. Features policy management, workflow engine with 9 node types, manual review queue, JWT/AES-256-GCM security, RBAC, and Redis caching for sub-500ms execution. Node.js/TypeScript backend, React frontend, PostgreSQL. -
6

Insurance Agentic Mesh (Underwriting Server)
Java-based agentic mesh for insurance with a dedicated Underwriting Server. Provides risk assessment, premium rate calculation, coverage eligibility evaluation, and risk report generation. Uses MCP/A2A protocols, Spring Boot 3.2, and JSON-RPC 2.0. -
11

@zanii/insurance
Machine-verifiable underwriting for agent liability. Generates risk profiles from ledger facts (not scores), supports co-signed policy bodies, and deterministic claim assessment against Merkle-proven receipts. TypeScript/Python SDK. -
16

MediPolicy_IQ (Underwriting Components)
Healthcare insurance platform with underwriting-relevant features: dynamic policy rule engine, COB liability splitting, explainable AI fraud detection with risk scoring (0-100), and document OCR for invoice/prescription extraction. FastAPI/Streamlit stack. -
10

openIMIS
Digital Public Good for social health protection and health insurance administration. Supports beneficiary enrollment, contribution management, claims processing, and medical review. Used by 34+ million beneficiaries across 14+ countries. HL7 FHIR interoperable. -
2
-
7
-
12

Additional Strong Open-Source Options

Rating Engines: ratingtables (R, table-driven), Rules-Engine (Java/Drools, multi-domain).

Risk Classification: insurancerating (R, GAM-based tariff construction, evolutionary tree binning). -
8

AI-Powered Underwriting: AI Underwriting System (Node.js, workflow engine, <500ms execution), Insurance Agentic Mesh (Java, MCP/A2A agents). -
6
-
11

Digital Public Goods: openIMIS (health insurance administration, claims processing, beneficiary management). -
2
-
7

Frameworks for building custom systems: Combine Rules-Engine for Drools-based decisioning, ratingtables for table-driven premium calculation, insurancerating for actuarial risk classification, and PostgreSQL for policy data. Add Docker for deployment and REST APIs for integration with core systems.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Insurance underwriting platforms handle sensitive financial and personal data; ensure compliance with relevant insurance regulations and data protection laws.

Self-hosted open-source solutions require proper security hardening, actuarial validation, and regular model audits.

Made for insurance underwriters, actuaries, insurtech builders, and product managers.
Let's make insurance underwriting more open, transparent, and data-driven.
