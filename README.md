# Awesome-Metadata-Configuration-API

# Top Metadata Configuration API Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Schema Management, Infrastructure as Code & Programmatic Resource Configuration*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Metadata Configuration API Tools**. These tools let developers and administrators programmatically define, deploy, and manage configuration metadata — cloud resources, CRM schemas, application settings, and infrastructure — through declarative APIs and infrastructure-as-code workflows.

**Examples** include Salesforce Metadata API, AWS Cloud Control API, Azure Resource Manager API, Google Cloud Resource Manager API, HashiCorp Terraform Registry, ServiceNow Table API, Okta Management API, GitHub Enterprise Admin API, Datadog Synthetics API, and Jira REST API (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom metadata schemas, and transparent configuration management — ideal for platform engineers, DevOps teams, and developers building data-sovereign infrastructure automation.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Metadata API](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/)**  
  Programmatic API for creating, reading, updating, and deleting Salesforce org metadata including custom objects, layouts, Apex classes, and profiles [citation:14].

- **[AWS Cloud Control API](https://aws.amazon.com/cloudcontrolapi/)**  
  Unified API for CRUD-L operations on AWS and third-party resources using standardized JSON schemas and resource type definitions [citation:2].

- **[Azure Resource Manager API](https://azure.microsoft.com/en-us/features/resource-manager/)**  
  Consistent management layer for creating, updating, and deleting Azure resources with declarative ARM templates and Bicep files [citation:3].

- **[Google Cloud Resource Manager API](https://cloud.google.com/resource-manager)**  
  Programmatic API for managing Google Cloud container resources — organizations, folders, and projects — with hierarchical access control [citation:16].

- **[HashiCorp Terraform Registry](https://registry.terraform.io/)**  
  Public registry for discovering and distributing Terraform providers and modules with a documented HTTP API for metadata retrieval [citation:5].

- **[ServiceNow Table API](https://developer.servicenow.com/)**  
  REST API for defining and managing database tables, columns, and schema metadata within ServiceNow scoped applications [citation:6].

- **[Okta Management API](https://developer.okta.com/docs/api/)**  
  Comprehensive REST API for managing users, groups, applications, policies, and identity metadata in Okta organizations [citation:19].

- **[GitHub Enterprise Admin API](https://docs.github.com/en/graphql)**  
  GraphQL API for managing enterprise accounts, organizations, repositories, and audit log metadata [citation:8].

- **[Datadog Synthetics API](https://docs.datadoghq.com/api/latest/synthetics/)**  
  API for creating and managing synthetic tests, monitors, and configuration metadata in Datadog.

- **[Jira REST API](https://developer.atlassian.com/server/jira/platform/jira-rest-apis-7372883/)**  
  REST API for managing Jira issues, projects, workflows, and configuration metadata with JSON request/response format [citation:10].

## Open-Source GitHub Projects

- **[Twenty CRM Metadata API](https://github.com/twentyhq/twenty)**  
  Modern open-source CRM with auto-generated REST and GraphQL APIs for records and schema. Metadata API manages objects, fields, and relations under `/rest/metadata`, so custom data models instantly gain matching Core API endpoints [citation:11]. AGPL-3.0 licensed.

- **[Terraform](https://github.com/hashicorp/terraform)**  
  Industry-standard infrastructure as code tool with provider-based resource metadata management. Supports custom providers and registry protocol for module distribution [citation:17]. BUSL licensed.

- **[OpenTofu](https://github.com/opentofu/opentofu)**  
  Open-source fork of Terraform (MPL re-licensed) for infrastructure as code with full provider ecosystem and module registry compatibility. MPL-2.0 licensed.

- **[Pulumi](https://github.com/pulumi/pulumi)**  
  Open-source infrastructure as code using general-purpose languages with provider-based resource schemas and configuration management. Apache 2.0 licensed.

- **[Crossplane](https://github.com/crossplane/crossplane)**  
  Kubernetes-native control plane for provisioning and managing cloud infrastructure using CRDs and composition metadata. Apache 2.0 licensed.

- **[Talos](https://github.com/celestiaorg/talis)**  
  Multi-cloud infrastructure provisioning API with configuration-driven resource creation. Uses Hypervisor API for cloud instances and Ansible for system configuration [citation:12]. Apache 2.0 licensed.

- **[Planton](https://github.com/plantonhq/planton)**  
  Open-source infrastructure automation platform with Pulumi-based deployment programs for AWS, Azure, GCP, and Cloudflare resources [citation:13]. Apache 2.0 licensed.

- **[Apache CloudStack](https://github.com/apache/cloudstack)**  
  Open-source IaaS platform with API-driven resource metadata management for compute, storage, and network configuration. Apache 2.0 licensed.

- **[OpenStack](https://github.com/openstack)**  
  Open-source cloud infrastructure platform with service APIs for managing compute, storage, and networking resource metadata. Apache 2.0 licensed.

- **[Kubernetes](https://github.com/kubernetes/kubernetes)**  
  Container orchestration platform with Custom Resource Definitions (CRDs) and API aggregation for metadata-driven resource configuration. Apache 2.0 licensed.

- **[Keycloak](https://github.com/keycloak/keycloak)**  
  Open-source identity and access management with Admin REST API for managing realms, clients, users, and role metadata. Apache 2.0 licensed.

- **[EspoCRM](https://github.com/espocrm/espocrm)**  
  Open-source CRM with REST API for managing entities, fields, layouts, and custom metadata programmatically. GPL-3.0 licensed.

- **[SuiteCRM](https://github.com/salesagility/SuiteCRM)**  
  Open-source CRM with REST API v8 and V8 metadata endpoints for managing modules, fields, and relationships. AGPL-3.0 licensed.

- **[Odoo](https://github.com/odoo/odoo)**  
  Open-source ERP with XML-RPC and JSON-RPC APIs for managing models, fields, views, and configuration metadata. LGPL-3.0 licensed.

- **[Directus](https://github.com/directus/directus)**  
  Open-source data platform with REST and GraphQL APIs for managing collections, fields, and schema metadata dynamically. BSL licensed.

- **[Strapi](https://github.com/strapi/strapi)**  
  Open-source headless CMS with REST and GraphQL APIs for content-type metadata management and schema configuration. MIT licensed.

- **[NocoDB](https://github.com/nocodb/nocodb)**  
  Open-source Airtable alternative with REST API for managing tables, columns, and views metadata on SQL databases. AGPL-3.0 licensed.

- **[Baserow](https://github.com/baserow/baserow)**  
  Open-source no-code database with REST API for managing tables, fields, and views metadata programmatically. MIT licensed.

### Additional Strong Open-Source Options

- **[Apache Airflow](https://github.com/apache/airflow)** — Workflow orchestration with DAG metadata APIs for programmatic pipeline configuration.
- **[Temporal](https://github.com/temporalio/temporal)** — Durable execution platform with workflow metadata and namespace configuration APIs.
- **[Kestra](https://github.com/kestra-io/kestra)** — Declarative orchestration with YAML-based flow metadata and API-driven configuration.
- **[ArgoCD](https://github.com/argoproj/argo-cd)** — GitOps continuous delivery with Application and AppProject metadata APIs.
- **[Flux](https://github.com/fluxcd/flux2)** — GitOps toolkit with Kustomization and HelmRelease metadata configuration.
- **[OPA (Open Policy Agent)](https://github.com/open-policy-agent/opa)** — Policy engine with bundle metadata APIs for configuration governance.
- **[Kyverno](https://github.com/kyverno/kyverno)** — Kubernetes policy engine with ClusterPolicy metadata management.
- **[Backstage](https://github.com/backstage/backstage)** — Developer portal with catalog metadata APIs for service and component configuration.
- **Schema Registry Tools** — Confluent Schema Registry, Apicurio, and Karapace for event schema metadata management.
- **API Gateways** — Kong, Tyk, and KrakenD for API configuration and route metadata management.

**Frameworks for building custom systems**: Combine **Terraform/OpenTofu** for infrastructure metadata, **Crossplane** for Kubernetes-native resource configuration, **Twenty CRM** for schema metadata, **Keycloak** for identity metadata, and **OPA** for policy-as-code to build a complete self-hosted metadata configuration platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Metadata configuration APIs must comply with data protection regulations (GDPR, CCPA), industry standards (SOC 2, ISO 27001), and API security best practices.
- Self-hosted open-source solutions require proper security hardening, credential management, and infrastructure governance.

---

**Made for platform engineers, DevOps teams, cloud architects, and developers building metadata-driven configuration platforms.**  
Let's make metadata configuration APIs more open, declarative, and developer-friendly.
