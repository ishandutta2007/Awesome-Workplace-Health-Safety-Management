# Awesome-Workplace-Health-Safety-Management

# Top Workplace Health & Safety Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on EHS Compliance, Incident Reporting & Self-Hosted Safety Platforms*  
**Last updated: October 2026**

This repository tracks notable **commercial workplace health and safety platforms** and **open-source projects** that manage incidents, track corrective actions, ensure regulatory compliance, and promote safer work environments across industries.

**Examples** include Salesforce Safety Cloud, Cority, Intelex, Benchmark ESG, VelocityEHS, EcoOnline, SafetyCulture, Alcumus, Origami Risk, and Quentic (the category leaders).

**Open-source emphasis**: Workplace health and safety management is a growing open-source domain. **SafeSphere** leads as a comprehensive OSHE platform with AI-powered safety assistance and statutory repositories. **GuardianSDS** brings AI-native Safety Data Sheet management with OSHA compliance. **Vision Desk AI** delivers multimodal PPE detection with YOLOv8 and multi-agent incident investigation. **JSAPY** provides a Python toolkit for accident analysis, vibration, and noise exposure assessment. **Riskor API** offers a Spring Boot backend for OHS incident management with JWT authentication. **SIA** from BCAA provides a standardized Excel-based SMS interface for aviation training organizations. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Safety Cloud](https://www.salesforce.com/products/safety-cloud/)**  
  **Salesforce's workplace safety platform** — employee wellness, emergency response, and safety compliance integrated with Salesforce.

- **[Cority](https://www.cority.com/)**  
  **Enterprise EHS and quality management** — incident management, compliance, and risk assessment.

- **[Intelex](https://www.intelex.com/)**  
  **EHS management software** — incident tracking, audits, and compliance management.

- **[Benchmark ESG](https://www.benchmarkdigitalesg.com/)**  
  **ESG and EHS platform** — compliance, safety, and sustainability management.

- **[VelocityEHS](https://www.velocityehs.com/)**  
  **EHS and ESG software** — safety, industrial hygiene, and environmental management.

- **[EcoOnline](https://www.ecoonline.com/)**  
  **EHS and chemical safety platform** — risk management and compliance.

- **[SafetyCulture](https://safetyculture.com/)**  
  **Workplace safety platform** — inspections, checklists, and incident reporting (iAuditor).

- **[Alcumus](https://www.alcumus.com/)**  
  **Risk management and compliance** — health and safety, supply chain, and contractor management.

- **[Origami Risk](https://www.origamirisk.com/)**  
  **Risk management platform** — safety, claims, and compliance management.

- **[Quentic](https://www.quentic.com/)**  
  **EHS and ESG software** — safety, environment, and sustainability management.

## Open-Source GitHub Projects

### Comprehensive EHS & Safety Platforms

- **[SafeSphere](https://github.com/)**  
  **Comprehensive open-source OSHE (Occupational Safety, Health, Environment) platform**, open-source. **SafeWork AI** — interactive agentic AI assistant answering complex OSH questions based on national statutory guidelines. **National Statutory Repository** — complete database of Indian OSH legislation including OSHWC Code 2020 and Rules. **OSH Calculators** — professional screening tools for Noise Exposure (TWA/Dose), Heat Stress (WBGT), Chemical Exposure (TLV), Ventilation, and Illumination. **Virtual SafeSphere Lab** — interactive virtual laboratory simulations for safety drills, hazard identification, and emergency response training. **First Aid Guidelines** — comprehensive emergency protocols for industrial hazards.

- **[Open Source EHS Web Console](https://github.com/topics/safety-management)**  
  **Open-source EHS web console: incidents, CAPA, metrics, documents, training, and audits**, TypeScript . **Role-aware with PostgreSQL-backed self-hostable architecture**. **Self-hosted EHS console: incidents, CAPA, audits, and TRIR-style metrics** with optional AI suggesting wording only — humans close records .

### Safety Data Sheet Management

- **[GuardianSDS](https://github.com/TAStagg/GuardianSDS)**  
  **AI-native Safety Data Sheet (SDS) management and compliance platform**, MIT licensed . **AI-Neural Extraction** — automatically converts manufacturer PDFs into structured JSON data using Vision-Language Models. **Emergency Mode** — one-tap/Voice-activated access to Section 4 (First Aid) and Section 8 (PPE) without a login. **The Sentinel** — automated agents that monitor manufacturer databases for revisions to ensure 2025 OSHA compliance. **Secondary Labeling** — instant GHS-compliant label generation for secondary containers. **Offline-First** — critical safety data is cached locally on iPad/Mobile devices for network outages. **Built for hospitals, clinics, and industrial facilities** to break the cost barrier of proprietary SDS management .

- **[ChemIP](https://pubs.acs.org/)**  
  **Open-source web platform for unified chemical safety data retrieval across Korean and international regulatory sources**, open-source . **Deterministic alias-based cross-lingual name/CAS resolver** — bidirectional Korean–English–CAS query resolution without machine translation. **Adapter-based multi-source orchestration** covering Korean government portals (KOSHA, KISCHEM, NCIS, KIPRIS) and international sources. **Self-hostable deployment** preserving confidentiality of chemical inquiry patterns. **Hazard classifications follow GHS rev. 10** .

### Incident Management & Response

- **[Riskor API](https://github.com/DiazzzDev/Riskor-API)**  
  **Backend service powering the Riskor Occupational Health and Safety platform**, educational/portfolio purpose . **Workplace incident management** — reporting, updating, and managing incidents with historical records for investigations. **Investigation support** — documenting investigation results, contributing factors, corrective actions, and preventive measures. **JWT authentication with Argon2id password hashing** implemented from scratch. **PPE inventory management**, file storage via Cloudinary, email notifications, and report generation with JasperReports. **Spring Boot 3, Java 17, Oracle Cloud Database** .

- **[FlowIntel](https://github.com/flowintel/flowintel)**  
  **Open-source incident & forensic case management platform**, co-funded by CIRCL and the European Union . **Day-to-day CSIRT/SOC work without spreadsheets or expensive closed platforms**. **Tracks cases, tasks, subtasks and their status**. **Organises notes, evidence, timelines and reports**. **Deep integration with MISP** — import MISP events as cases, attach MISP-Object, export cases to MISP. **REST API and connectors for automation** .

### Vision-Based Safety Monitoring

- **[Vision Desk AI](https://github.com/VedikaPunjabi/vision-desk-ai)**  
  **Enterprise multimodal workplace safety platform**, MIT licensed . **Real-time PPE & Hazard Vision Detection** — YOLOv8 detects workers, hardhats, high-visibility vests, gloves, boots, and unsafe equipment. **Multimodal Document RAG** — ChromaDB + Gemini for safety SOP and compliance PDF indexing. **Autonomous Multi-Agent Root Cause Investigation** — LangGraph workflow (Query Analysis → Document Retrieval → Visual Analysis → Evidence Validation → Reasoning → Report Generation) with human sign-off. **Executive Safety Dashboard** — live workplace compliance percentage, department safety scoreboard, and 1-click CSV report exports .

- **[VisionAI Toolkit](https://github.com/visionify/visionai)**  
  **Workplace health and safety solution with 60+ scenarios**, open-source . **PPE detection** (helmets, vests, safety boots, eye protection, face-masks). **Hazard monitoring** — smoke, fire, gas leaks, toxic gases, wet/slippery surfaces. **Confined spaces monitoring** — personnel entry/exit and duration tracking. **Crowd control** — occupancy metrics and social distancing compliance .

### Occupational Hygiene & Risk Assessment

- **[JSAPY (Job Safety Analysis in Python)](https://ruc.udc.es/)**  
  **Open-source Python package for occupational risk prevention technicians**, open-source . **Three areas**: analysis of work-related accidents, analysis of exposure to vibrations (hand-arm and whole-body), and analysis of noise exposure. **Fully documented, tested with Pytest, and published on GitHub**. **Adapts to both users with programming experience and those seeking quick tools** . **Designed for automation** — from measurement to report generation .

- **[NanoRisk-Web](https://www.sciencedirect.com/)**  
  **Open-source decision-support platform for nanomaterial risk assessment**, open-source . **Bayesian Network hazard-prediction model** with 20 nodes and 35 arcs predicting biological-effect endpoints. **Seven-parameter workplace scenario score** (process stage, handling frequency, ventilation effectiveness, dustiness, mass handled, temperature, humidity). **Control-measure recommendation** with risk group and final risk score. **Complete result exportable as CSV report** . **Eliminates proprietary software dependencies** through independent exact inference engine .

- **[Organilab](https://github.com/Solvosoft/organilab)**  
  **Open-source virtual tool for inventory management of chemical substances**, designed for ISO-17025 and GHS compliance . **Chemical substance inventory management** for laboratories and facilities.

- **[Seirich](https://www.travail-et-securite.fr/)**  
  **French open-access chemical risk assessment software**, adopted by nearly 40,000 companies in a decade . **Three levels of use** — beginner, intermediate, and expert. **Chemical inventory, risk evaluation, and prevention action planning**. **Evolved to address polyexposure and nanomaterials** .

### Aviation Safety Management

- **[SIA (SMS Interface for ATO)](https://mobilit.belgium.be/)**  
  **Open-source Microsoft Excel tool for Safety Management Systems in EASA Approved Training Organizations**, commissioned by BCAA . **Covers full SMS scope** — annual risk assessment (hazard register), risk assessment matrix, occurrence follow-up, and safety meetings. **Standardized across Belgian/European ATOs** for comparison and national statistics . **Free of charge to the aviation community** .

- **[OpenDroneSMS](https://github.com/gearboxxsv/OPENDroneSMS)**  
  **Anonymous Safety Reporting System (ASRS) for Unmanned Aircraft Safety Team (UAST)**, open-source . **Bridges the gap for NASA and all communities** — each flight operation will have issues, the public will have reports, and we all want to protect proprietary information and privacy. **Foundation to develop your own SMS program** — share data, contribute code, integrate anonymous and secure code .

### Additional Strong Open-Source Options

- **Gestion Seguridad Industrial** — FastAPI-based industrial safety and occupational health management system with JWT authentication, role-based access control, and Docker deployment .
- **rEHS** — R package for EHS management tools, Apache licensed .
- **EHS Web Console** — Self-hosted EHS console with incidents, CAPA, audits, and TRIR-style metrics .
- **Flutter OH&S Platform** — Flutter-based occupational health and safety operations platform for inspections, incidents, and field workflows .
- **Yoshi Checks App** — Japanese workplace safety app for digitizing Yoshi checks and SOP workflows .
- **Risk Evaluation Web App** — Next.js application for systematic risk evaluations and root cause analysis with multi-step forms .

**Frameworks for building custom workplace health and safety solutions**: Combine **SafeSphere** for comprehensive OSHE management with AI assistance and statutory repositories. Use **GuardianSDS** for AI-native SDS management with OSHA compliance. Deploy **Vision Desk AI** for multimodal PPE detection and multi-agent incident investigation. Integrate **JSAPY** for occupational hygiene calculations (noise, vibration, accidents). Use **Riskor API** for incident management with JWT authentication. Choose **FlowIntel** for case management with MISP integration. Note that true enterprise workplace health and safety platforms with managed infrastructure, global compliance coverage, and vendor-supported SLAs (Salesforce Safety Cloud, Cority, Intelex) remain primarily commercial territory; open-source stacks provide strong incident management, SDS management, and risk assessment foundations that require integration for complete workplace health and safety management.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Workplace health and safety platforms handle sensitive incident data and may involve regulatory compliance obligations. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.
- **Regulatory compliance varies by jurisdiction** — workplace safety requirements (OSHA in the US, OSHWC Code 2020 in India, EASA regulations in aviation) differ significantly. Verify compliance before deployment.
- **Open-source safety platforms vary significantly in maturity** — SafeSphere and GuardianSDS are production-oriented ; some projects are educational or proof-of-concept. Evaluate before relying on them for regulatory-critical workflows.
- The open-source ecosystem provides strong incident management, SDS management, and risk assessment foundations, but **managed infrastructure, global compliance coverage, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for safety professionals, EHS managers, and organizations seeking workplace health and safety sovereignty.**  
Let's make workplace health and safety management more open, transparent, and proactive.
