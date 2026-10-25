# Sławomir Małyszko

## AI Solutions Architect & Engineer

Warsaw, Poland\
LinkedIn: <https://www.linkedin.com/in/SlawomirMalyszko>

------------------------------------------------------------------------

## Professional Profile

**AI Solutions Architect & Engineer** with 25+ years of experience
across software engineering, enterprise integration, cloud, DevOps,
solution architecture, and IT service delivery in international
organizations in the pharmaceutical, FMCG, retail, banking, and
technology sectors.

Combines hands-on engineering with enterprise architecture experience.
Current focus is on building **AI-assisted enterprise solutions** that
connect Large Language Models with governed enterprise data, APIs,
integration platforms, and graph-based knowledge models.

Strong background in **.NET/C#, REST APIs, integration architecture,
AWS, Azure, DevOps, CI/CD, SQL, SAP/Salesforce integration, Informatica
Cloud (IICS), and TIBCO**. Experienced in translating business discovery
and impact-analysis problems into secure, maintainable technical
architectures.

Currently developing **Integration Catalogue**, a portfolio project
demonstrating AI solution architecture and engineering: natural-language
discovery over a canonical enterprise integration graph using **Amazon
Bedrock, Neo4j, Python, controlled NL-to-Cypher generation, GitHub
Actions, and enterprise integration metadata**.

AWS Solutions Architect -- Associate certification earned in 2019.
Fluent English.

------------------------------------------------------------------------

## Core Competencies

### AI Solution Architecture & Engineering

-   Architecture of AI-assisted enterprise applications
-   LLM integration with structured enterprise data and knowledge graphs
-   Natural-language-to-query solution patterns
-   Prompt context design using schemas, examples, and bounded
    enterprise context
-   Controlled AI execution with validation and read-only access
    boundaries
-   Human-in-the-loop design for ambiguous or low-confidence results
-   Agentic development workflows and MCP-based cloud tooling
-   AI solution security, credential isolation, least-privilege access,
    and cost-aware cloud design

### Software Engineering

-   .NET Core / C#
-   ASP.NET Core and REST APIs
-   Entity Framework / LINQ
-   Angular / TypeScript
-   Python
-   Microsoft SQL Server
-   Automated testing and CI/CD
-   Git / GitHub / Azure DevOps

### Architecture & Integration

-   Enterprise and solution architecture
-   Integration architecture and iPaaS
-   Informatica Cloud / IICS
-   TIBCO BusinessWorks / Container Edition
-   REST/API integration
-   SAP and Salesforce integration
-   Event-driven and messaging integration
-   Canonical data and integration modelling
-   Impact analysis and dependency discovery

### Cloud & DevOps

-   Amazon Web Services
-   Microsoft Azure
-   GitHub Actions
-   Azure DevOps
-   GitLab CI/CD
-   Containers / Kubernetes / OpenShift
-   AWS Elastic Beanstalk
-   Cloud security and secrets-management principles
-   OIDC-based CI/CD authentication patterns

### Leadership & Delivery

-   Technical and integration leadership
-   Architecture governance
-   Distributed and offshore team leadership
-   ITIL service management
-   DevOps operating models
-   Stakeholder and vendor management
-   Service transition and continuous improvement

------------------------------------------------------------------------

## Selected AI Engineering Project

### Integration Catalogue --- AI-Assisted Enterprise Integration Discovery

**Solution Architect & Engineer \| Portfolio / Learning Project \|
2026**

Designing and implementing an AI-assisted architecture and discovery
platform for enterprise architects and managers. The solution builds a
canonical graph of integrations across heterogeneous technologies and
enables users to explore architecture and dependency information through
natural-language questions.

**Example business questions**

- Which objects carry Orders?
- Which end-to-end flows interface with SAP?
- Which applications may be affected if an interface changes?
- How do two applications exchange information?

**Architecture**

- **Neo4j AuraDB** as the graph database and query projection.
- **Amazon Bedrock** planned for focused natural-language-to-Cypher generation.
- **Python 3.12** for extraction, normalization, and application logic.
- **Streamlit** planned for the initial user interface.
- Source-specific extraction separated from canonical normalization.
- Canonical graph concepts include `Application`, `Interface`, `Integration`,
  and `InformationObject`.
- Enterprise-scale demonstration model targeting approximately **5,000 synthetic
  integrations**.
- ServiceNow/APM-inspired application master data with Solace and Kong as likely
  live/demo metadata sources.
- Synthetic enterprise metadata intentionally including incomplete, ambiguous,
  and faulty records to exercise realistic reconciliation scenarios.

**AI and governance design**

- Uses a **focused NL-to-Cypher approach rather than an unrestricted autonomous
  agent**.
- LLM context designed around selected graph schema, worked query examples, and
  bounded application/lookup context.
- Generated Cypher intended to be **validated and restricted to read-only
  operations** before execution.
- Ambiguous or low-confidence questions clarified or rejected rather than
  executed unsafely.
- Git as the source of truth for canonical schemas, mappings, examples, and
  reviewed reconciliation decisions.
- Identity resolution designed to evolve from deterministic matching toward
  probabilistic evidence with human review for unresolved mappings.
- Read-only end-user graph access, with graph writes reserved for controlled
  ingestion.

**Engineering and DevOps**

- GitHub Actions CI with Python 3.12, `pytest`, and `ruff`.
- Read-only default repository permissions and planned GitHub OIDC authentication
  to AWS rather than long-lived access keys.
- MCP-based, read-first AWS discovery with scoped mutations and explicit
  cost/cleanup consideration.
- Solace connectivity workflow validating secure MQTT messaging over WebSockets
  using environment-scoped GitHub secrets.
- Architectural decisions and cloud operating procedures maintained as code
  alongside the project.

**Technologies:** Amazon Bedrock, Neo4j AuraDB, Python, Cypher, GitHub
Actions, AWS, MCP, Solace, Kong, Streamlit, pytest, Ruff, Git

> Project status: foundation and architecture phase. The repository
> currently demonstrates solution design, graph modelling decisions,
> secure cloud/agent operating patterns, CI, and integration
> connectivity; the first functional AI-to-graph vertical slice is the
> next implementation stage.

------------------------------------------------------------------------

## Professional Experience

### Sanofi

**Solution Architect -- Integration / Integration Lead** \| 2018 -- now

Worked in enterprise integration architecture and delivery for a global
pharmaceutical organization.

-   Led integration development activities for a global eCommerce
    initiative using **Informatica Cloud / IICS**.
-   Established and promoted common integration frameworks, Git-based
    version management, and deployment practices.
-   Supported delivery through SIT and UAT and production handover
    activities.
-   Acted as an IT / Integration Partner within the global Integration
    Center of Excellence.
-   Assured delivery of TIBCO BusinessWorks integration interfaces for
    customers across EMEA and AMER.
-   Supported integration migration toward AWS and containerized
    environments connecting on-premises data centres and cloud services.
-   Contributed to modernization initiatives including TIBCO platform
    upgrades, MDM upgrades, and adoption of TIBCO BW Container Edition /
    OpenShift.
-   Worked extensively with enterprise integration scenarios involving
    SAP, Salesforce, transactional interfaces, and ETL flows.

**Technologies:** Informatica Cloud / IICS, TIBCO BusinessWorks, TIBCO
BW Container Edition, AWS, OpenShift, GitLab, SAP, Salesforce

### Self-driven Project

**.NET Core Development** \| 2022 -- 2024

Backend-focused .NET Core development with occasional frontend
development in an Azure DevOps environment.

-   Developed backend services and exposed APIs using .NET/C#.
-   Entity Framework used, LINQ, and Microsoft SQL Server.
-   Angular web frontend utilized.
-   Worked within a modern DevOps software-development lifecycle
    including source control, testing, and delivery processes.
-   Used automated frontend testing with Cypress and service/API testing
    with SoapUI.

**Technologies:** .NET Core, C#, Entity Framework, LINQ, Microsoft SQL
Server, Angular, Cypress, SoapUI, Azure DevOps

### Danone

**Application Management Team Leader -- EMEA IT Competency Center** \|
Sep 2016 -- Feb 2018

-   Led an application-management team supporting EMEA services.
-   Managed service delivery, team development, operational priorities,
    and application lifecycle responsibilities.
-   Worked in a large international FMCG technology organization.

### Statoil Fuel & Retail

**Integration Team Leader** \| Mar 2013 -- Aug 2016

-   Led integration services delivered by a local team of eight
    engineers together with an offshore team in India.
-   Assured operation of approximately **200 Oracle SOA and 20 Microsoft
    BizTalk interfaces**.
-   Managed incident, change, service-improvement, and operational
    processes around enterprise integration platforms.
-   Created and executed a roadmap for migration of BizTalk interfaces
    to the Oracle SOA platform.
-   Introduced a DevOps-oriented support structure for transitioning
    applications from development into operations.
-   Supported applications running on AWS using Kubernetes and Elastic
    Beanstalk.

### IBM

**Service Delivery Manager -- Infrastructure** \| Jul 2012 -- Jan 2013

-   Managed delivery of infrastructure services for an international
    banking customer against agreed SLAs.
-   Led service reviews and steering activities and coordinated customer
    requirements and improvement actions.
-   Performed Major Incident Manager and Problem Manager
    responsibilities.
-   Managed service improvement, risk management, root-cause analysis,
    and infrastructure maintenance initiatives.
-   Coordinated data-centre maintenance and power-down projects across
    IBM and customer teams.

### Roche

**Group Service Manager / Service Manager / .NET Developer** \| 2002 --
2011

Progressed from software development into service and people leadership.

-   Managed a distributed organization of approximately **25 service
    managers, line managers, and IT specialists**.
-   Delivered software development, application management, and testing
    services.
-   Expanded distributed operations and introduced second-shift and
    work-from-home models.
-   Participated in an international assignment in San Francisco
    supporting integration of Californian and Polish IT organizations.
-   Harmonized processes and tools and helped transition work to the
    Warsaw delivery organization.
-   Earlier worked hands-on as a **.NET Developer**.

### Earlier Experience

**CALAN & ASSOCIES --- .NET Application Developer** \| 2003 -- 2004\
**Nokia Poland / Finland --- Intranet Application Developer /
Application Specialist** \| 2000 -- 2002\
**Polygon Poland --- IT Specialist** \| 1999 -- 2000

------------------------------------------------------------------------

## Technical Skills

| Area | Technologies / Capabilities |
| --- | --- |
| AI / GenAI | Amazon Bedrock, LLM solution architecture, NL-to-Cypher design, prompt/context design, controlled agentic querying, MCP workflows |
| Graph / Data | Neo4j, Cypher, graph modelling, canonical enterprise models, identity-resolution design |
| Development | .NET Core, C#, ASP.NET Core, Python, Entity Framework, LINQ |
| Frontend | Angular, TypeScript |
| APIs & Integration | REST APIs, Informatica Cloud/IICS, TIBCO BW, TIBCO BW CE, Oracle SOA, BizTalk, Solace, Kong |
| Databases | Microsoft SQL Server, Neo4j AuraDB |
| Cloud | AWS, Microsoft Azure |
| DevOps | GitHub Actions, Azure DevOps, GitLab, Git, CI/CD, OIDC patterns |
| Containers | Kubernetes, OpenShift |
| Testing | pytest, Ruff, Cypress, SoapUI |
| Enterprise Systems | SAP, Salesforce |
| Service Management | ITIL, Incident, Problem, Change, Service Improvement, SLA Management |

------------------------------------------------------------------------

## Education

**Canadian Executive MBA**\
University of Montreal / Warsaw School of Economics \| 2012

**Postgraduate Studies -- Project Management**\
Warsaw School of Economics \| 2006

**Master's Degree in Information Technology -- Software Design**\
Technical University in Bialystok \| 1999

------------------------------------------------------------------------

## Certifications & Selected Training

-   **Microsoft Azure Fundamentals (AZ-900)** --- 2021
-   **AWS Certified Solutions Architect -- Associate** --- 2019
-   **Architecting on AWS** --- instructor-led course, 2019
-   **ITIL Manager's Certificate in IT Service Management** --- 2008
-   **Insight -- Communication and Behavior Models** --- 2006, 2017

------------------------------------------------------------------------

## Languages

**English** --- Full professional / fluent proficiency\
**Polish** --- Native

------------------------------------------------------------------------

## Additional Information

**Career experience since:** 1999\
**Professional interests:** AI-enabled enterprise architecture,
knowledge graphs, enterprise integration, cloud architecture, software
engineering, DevOps\
**Personal interests:** Tennis --- active, competitive /
semi-professional level
