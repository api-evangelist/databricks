# Databricks (databricks)
Collection of Databricks REST APIs for managing workspaces, clusters, jobs, and data operations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/databricks/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI, Analytics, Apache Spark, Big Data, Clean Rooms, Cloud Computing, Data, Data Analytics, Data Engineering, Data Governance, Delta Lake, Delta Sharing, ETL, Identity Management, Lakehouse, Machine Learning, MLflow, Model Serving, Security, SQL, Unity Catalog, Vector Search, Visualize

## Timestamps

- **Created:** 2025-01-14
- **Modified:** 2026-04-18

## APIs

### Databricks Clusters API
The Databricks Clusters API allows you to create, start, edit, list, terminate, and delete clusters. Clusters are managed cloud resources that enable you to run data engineering and data science workloads on Apache Spark in the cloud. The API provides programmatic control over cluster lifecycle management, configuration, and monitoring.

**Human URL:** [https://docs.databricks.com/api/workspace/clusters](https://docs.databricks.com/api/workspace/clusters)

#### Tags:

 - Clusters, Compute, Infrastructure

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/clusters)
- [OpenAPI](openapi/databricks-openapi.yml)
- [JSONSchema](json-schema/databricks-cluster-schema.json)
- [JSONLD](json-ld/databricks-context.jsonld)

### Databricks Jobs API
The Databricks Jobs API allows you to create, edit, delete, and trigger jobs. Jobs are the primary mechanism for running automated workloads on Databricks, including notebooks, JARs, Python scripts, and Spark submit applications. The API supports complex multi-task workflows with dependencies, scheduling, and monitoring capabilities.

**Human URL:** [https://docs.databricks.com/api/workspace/jobs](https://docs.databricks.com/api/workspace/jobs)

#### Tags:

 - Jobs, Orchestration, Scheduling, Workflows

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/jobs)
- [OpenAPI](openapi/databricks-openapi.yml)
- [JSONSchema](json-schema/databricks-job-schema.json)
- [JSONLD](json-ld/databricks-context.jsonld)

### Databricks Workspace API
The Databricks Workspace API allows you to list, import, export, and delete notebooks, folders, and libraries in a Databricks workspace. It provides programmatic access to manage workspace objects, enabling automation of notebook deployment and workspace organization.

**Human URL:** [https://docs.databricks.com/api/workspace/workspace](https://docs.databricks.com/api/workspace/workspace)

#### Tags:

 - Folders, Notebooks, Workspace

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/workspace)
- [OpenAPI](openapi/databricks-openapi.yml)
- [JSONLD](json-ld/databricks-context.jsonld)

## Common Properties

- [Authentication](https://docs.databricks.com/dev-tools/auth.html)
- [GettingStarted](https://docs.databricks.com/getting-started/index.html)
- [SDK](https://docs.databricks.com/dev-tools/sdks.html)
- [StatusPage](https://status.databricks.com/)
- [Support](https://help.databricks.com/)
- [APIReference](https://docs.databricks.com/api/workspace/introduction)
- [Documentation](https://docs.databricks.com/aws/en/reference/api)
- [Pricing](https://www.databricks.com/product/pricing)
- [SignUp](https://www.databricks.com/try-databricks)
- [PrivacyPolicy](https://www.databricks.com/legal/privacynotice)
- [TermsOfService](https://www.databricks.com/legal/terms-of-use)
- [Security](https://www.databricks.com/trust)
- [RateLimits](https://docs.databricks.com/aws/en/resources/limits)
- [ChangeLog](https://docs.databricks.com/aws/en/release-notes/)
- [Blog](https://www.databricks.com/blog)
- [GitHubOrganization](https://github.com/databricks)
- [CLI](https://github.com/databricks/cli)
- [Training](https://www.databricks.com/learn/training/home)
- [Academy](https://customer-academy.databricks.com/learn)
- [X](https://twitter.com/databricks)
- [LinkedIn](https://www.linkedin.com/company/databricks)
- [Contact](https://www.databricks.com/company/contact)

## Features

| Name | Description |
|------|-------------|
| Unified Data Lakehouse | Combine data warehousing and data lake capabilities in a single, open platform built on Delta Lake. |
| Serverless Compute | Auto-scaling serverless SQL warehouses and compute that eliminate infrastructure management. |
| Unity Catalog | Unified governance for data and AI assets with fine-grained access control and lineage tracking. |
| Delta Live Tables | Declarative ETL framework for building reliable, maintainable data processing pipelines. |
| Mosaic AI | Integrated AI platform for building, deploying, and monitoring machine learning and generative AI models. |
| Vector Search | Built-in vector similarity search for RAG applications and AI-powered retrieval. |
| Delta Sharing | Open protocol for secure cross-organization data sharing without data copying. |

## Use Cases

| Name | Description |
|------|-------------|
| Data Engineering | Build and orchestrate ETL pipelines with Delta Live Tables and multi-task workflows. |
| Data Warehousing | Run analytical SQL queries on lakehouse data with serverless SQL warehouses. |
| Machine Learning | Train, track, and deploy ML models with MLflow experiment tracking and model registry. |
| Real-Time Analytics | Process streaming data with structured streaming and serve results through online tables. |
| Data Governance | Govern data assets across the organization with Unity Catalog metadata management. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Spark | Native integration with Apache Spark for distributed data processing at scale. |
| Delta Lake | Built on Delta Lake open format for ACID transactions and time travel on data lakes. |
| MLflow | Open-source platform for managing the complete machine learning lifecycle. |
| Terraform | Infrastructure-as-code provider for automating Databricks workspace provisioning. |
| dbt | Integration with dbt for SQL-based data transformation workflows. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Databricks REST API](openapi/databricks-openapi.yml)

### JSON-LD

- [Databricks Context](json-ld/databricks-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Databricks REST API](capabilities/shared/databricks-api.yaml) -- 26 operations for clusters, jobs, and workspace management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Data Engineering](capabilities/data-engineering.yaml) | Databricks REST | 18 | Data Engineer |

## Rules

- [Databricks Spectral Rules](rules/databricks-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
