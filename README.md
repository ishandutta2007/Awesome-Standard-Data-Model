# Awesome-Standard-Data-Model

# Top Standard Data Model Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Industry Data Standards, Ontologies & Self-Hosted Semantic Models*
**Last updated: October 2026**

This repository tracks notable **commercial and open standard data models** and **open-source projects** that define shared vocabularies, entity relationships, and data structures for interoperability across industries — from financial messaging and healthcare to retail, telecom, and the web.

**Examples** include SAP One Domain Model, Microsoft Common Data Model, Schema.org, HL7 FHIR, TM Forum Open API, OData, CDISC, ISO 20022, and EDMC FIBO (the category leaders).

**Open-source emphasis**: Standard data models are one of the strongest open-source domains. **Schema.org** provides the vocabulary foundation for the web with 3,840 classes and 49,916 properties . **EDMC FIBO** defines financial industry business ontology with 642 GitHub stars . **HL7 FHIR** delivers the global standard for healthcare data exchange with open-source implementations in Python, Java, Dart, PHP, and more . **TM Forum Open API** provides standardized telecom APIs with a governance process for multi-team collaboration . **OData** is an ISO/IEC approved OASIS standard with rich open-source libraries for .NET, Java, Python, and JavaScript . **OHDSI OMOP Common Data Model** powers observational health research with 881 GitHub stars . **Smart Data Models** program covers energy, water, waste, mobility, and more with 18,000+ standardized terms . This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[SAP One Domain Model](https://www.sap.com/)**  
  **SAP's unified data model for the Intelligent Enterprise** — provides common semantics for business objects across SAP applications . **Enables out-of-the-box integrations between SAP cloud applications with one mapping per application, reducing total cost of ownership** . **Defined in Core Data Services (CDS) format for machine-readable definitions** . **Best for SAP-centric organizations wanting harmonized master data** .

- **[Microsoft Common Data Model](https://learn.microsoft.com/en-us/common-data-model/)**  
  **Microsoft's shared data model for business applications** — defines standard entities and relationships for Dynamics 365, Power Platform, and Azure . **Supports custom entities, relationships, and business rules** . **Best for Microsoft ecosystem integration** .

- **[Schema.org](https://schema.org/)**  
  **The collaborative vocabulary for structured data on the web** — 3,840 classes, 49,916 properties, and 2,593 vocabularies as of 2020 . **Provides a shared vocabulary for search engines, websites, and applications** . **Best for web data interoperability** .

- **[HL7 FHIR](https://www.hl7.org/fhir/)**  
  **Fast Healthcare Interoperability Resources** — the global standard for exchanging healthcare information electronically . **Supports R4, R5, STU3, and DSTU2 with JSON and XML formats** . **Best for healthcare data exchange** .

- **[TM Forum Open API](https://www.tmforum.org/)**  
  **Telecom industry standard APIs** — component suite covering customer, product, service, and resource domains . **API governance process permits multiple collaboration teams to capture API requirements in parallel** . **Best for telecom BSS/OSS interoperability** .

- **[OData](https://www.odata.org/)**  
  **ISO/IEC approved, OASIS standard for building and consuming RESTful APIs** . **Machine-readable metadata enables generic client proxies and tools** . **Domain-agnostic with platform-agnostic support for .NET, Java, PHP, Python, and REST** . **Best for RESTful API standardization** .

- **[CDISC](https://www.cdisc.org/)**  
  **Clinical Data Interchange Standards Consortium** — global standards for clinical research data . **Best for clinical trial data standardization** .

- **[ISO 20022](https://www.iso20022.org/)**  
  **Global standard for financial messaging** — syntax-independent modelling methodology for financial business areas, transactions, and message flows . **Central dictionary of commonly agreed business items with data dictionary and business process catalogue** . **Best for financial messaging interoperability** .

- **[EDMC FIBO](https://spec.edmcouncil.org/fibo/)**  
  **Financial Industry Business Ontology** — defines the sets of things of interest in financial business applications and their relationships . **Gives meaning to any data describing the business of finance** . **MIT licensed with 642 GitHub stars** . **Best for financial data semantics** .

## Open-Source GitHub Projects

### Financial Industry Standards

- **[EDMC FIBO](https://github.com/edmcouncil/fibo)**  
  **The Financial Industry Business Ontology (FIBO)**, MIT licensed with **642 GitHub stars** . **Defines the sets of things that are of interest in financial business applications and the ways those things can relate to one another** . **Gives meaning to any data (spreadsheets, relational databases, XML documents) that describe the business of finance** . **Actively maintained with recent pull requests for ISO MIC codes updates and ACTUS mapping vocabulary corrections** . **Best for financial industry semantic modeling** .

- **[modelith-dbt](https://pypi.org/project/modelith-dbt/)**  
  **Cross-repo model catalog for dbt projects with FIBO integration**, open-source . **Git-native manifest backend with no database or server required** — one human-readable YAML entry per model . **Ships with a small mock FIBO server for offline development** . **Browsable catalog with searchable/filterable model list, ontology-layer chips, and commit-pinned views** . **Supports S3, DataHub, and other backends via adapter interface** . **Best for managing multiple FIBO-aligned data models** .

### Healthcare Standards

- **[OHDSI OMOP Common Data Model](https://github.com/OHDSI/CommonDataModel)**  
  **Observational Medical Outcomes Partnership Common Data Model**, open-source with **881 GitHub stars** . **Standardizes observational health data for research** — enables consistent analysis across disparate databases . **Ecosystem includes ATLAS (analysis tool), Achilles (data characterization), Usagi (mapping), and WebAPI** . **ETL tools for CMS, MIMIC, and Synthea datasets** . **Best for observational health research** .

- **[HL7 FHIR Open Source Implementations](https://confluence.hl7.org/pages/viewpage.action?pageId=307302805)**  
  **Comprehensive collection of open-source FHIR implementations** across languages . **client-py** — flexible Python client supporting SMART on FHIR . **IBM FHIR Server** — Java server and libraries for R4 with JSON/XML and FHIRPath 2.0 . **Android FHIR SDK** — Kotlin library for offline-capable mobile healthcare apps . **Medplum** — FHIR-native EHR for modern app development . **Blaze** — high-performance Clojure FHIR server with CQL evaluation . **Best for healthcare interoperability** .

### Web & Cross-Domain Standards

- **[Schema.org](https://github.com/schemaorg/schemaorg)**  
  **The collaborative vocabulary for structured data on the web**, open-source . **3,840 classes and 49,916 properties** . **Maps to FOAF and other LOV vocabularies** — 135 classes mapped in semantic alignment experiment . **Version 6 published January 2020** . **Best for web data standardization** .

- **[OData Libraries](https://github.com/OData/)**  
  **Open Data Protocol libraries and tools**, open-source . **Restier** — main library for .NET Framework . **Apache Olingo** — Java platform for building OData services . **odata-v2-adapter** — OData V2 adapter for SAP CDS . **odata-sequelize** — transforms OData queries to Sequelize . **odata-v4-typeorm** — OData to TypeORM query compiler . **Best for RESTful API development** .

- **[Smart Data Models](https://github.com/smart-data-models)**  
  **Open-licensed data models for smart cities and IoT**, open-source . **Covers energy, water, waste, mobility, agrifood, tourism, and more** . **18,000+ terms mapped with 100+ collaborators across 800 data models** . **Integrates 18 ontologies/vocabularies including SAREF core, schema.org, and IUDX** . **Configuration file enables precedence-based mapping across ontologies** . **Best for smart city and IoT data standardization** .

### Telecom Standards

- **[TM Forum Open API](https://github.com/tmforum-rand)**  
  **Telecom industry Open API assets**, open-source . **GB1023 Data Governance Guide Book v2.0.0** . **GB1024 Data Governance API Engine — Executive Summary v1.0.0** . **GB1025 Data Governance Maturity Model v1.0.0** . **TR261 Data Governance Functions and Implementation R16.0.1** . **API governance process drives technical inputs (yaml Rules files) for API tooling** . **Best for telecom data governance** .

### Additional Strong Open-Source Options

- **italia/daf-ontologie-vocabolari-controllati** — Italian government ontologies and controlled vocabularies, 82 GitHub stars, Python .
- **Azure Digital Twins Ontology Browser** — Search, browse, and visualize open-source digital twin ontologies on GitHub, TypeScript .
- **MHCLG Digital Planning Data Models** — Standardized data definitions for enterprise data architecture, 17,000+ definitions .
- **OHDSI Broadsea** — Docker container deploying core OHDSI technology stack .
- **FHIR Protocol Buffers** — Protocol buffer definitions for FHIR, 828 GitHub stars .
- **Clinical Quality Language (CQL)** — HL7 specification for expressing clinical knowledge .

**Frameworks for building custom standard data model solutions**: Combine **Schema.org** for web data vocabularies and search engine visibility . Use **EDMC FIBO** for financial industry semantic modeling with ontology-driven data integration . Deploy **HL7 FHIR** for healthcare data exchange with open-source implementations in any language . Integrate **OHDSI OMOP CDM** for observational health research data standardization . Choose **OData** for RESTful API standardization with ISO/IEC approval . Use **Smart Data Models** for smart city and IoT data models with cross-ontology mapping . Integrate **TM Forum Open API** for telecom BSS/OSS interoperability . Note that true enterprise data models with vendor-supported governance, industry-wide adoption, and compliance certifications (SAP One Domain Model, Microsoft CDM) remain primarily commercial territory; open-source standards provide strong vocabularies, ontologies, and data model foundations that require integration for complete enterprise interoperability.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Standard data models define shared semantics for interoperability and may involve regulatory compliance obligations. Self-hosted implementations require proper governance, version management, and alignment with industry standards.
- **Adoption varies significantly** — Schema.org is universal for web data, HL7 FHIR is mandated in many healthcare jurisdictions, while other standards may be emerging or industry-specific. Verify industry adoption before committing .
- **License considerations**: FIBO uses MIT , Schema.org is open-source , OData is OASIS/ISO standard , OHDSI OMOP CDM is open-source , and Smart Data Models is open-licensed . Verify licensing against your use case before committing.
- **Governance is critical** — standard data models require ongoing maintenance and version management. TM Forum's API governance process is a reference for managing multi-team contributions .
- The open-source ecosystem provides strong vocabularies, ontologies, and data model foundations, but **vendor-supported governance, industry-wide adoption, and compliance certifications** remain primarily commercial offerings.

---

**Made for data architects, semantic engineers, and organizations seeking standard data model sovereignty.**
Let's make standard data models more open, transparent, and interoperable.
