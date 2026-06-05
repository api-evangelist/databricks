# Databricks (databricks)

Collection of Databricks REST APIs for managing workspaces, clusters, jobs, and data operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/databricks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/databricks/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- Analytics
- Apache Spark
- Big Data
- Clean Rooms
- Cloud Computing
- Data
- Data Analytics
- Data Engineering
- Data Governance
- Delta Lake
- Delta Sharing
- ETL
- Identity Management
- Lakehouse
- Machine Learning
- MLflow
- Model Serving
- Security
- SQL
- Unity Catalog
- Vector Search
- Visualize

## Timestamps

- **Created:** 2025-01-14
- **Modified:** 2026-05-19

## APIs

### Databricks

Databricks is a cloud-based data platform that simplifies and accelerates the process of preparing and analyzing large volumes of data. The platform integrates with popular data sources and tools, allowing data engineers and data scientists to collaborate and work more efficiently. Databricks offers powerful features such as data visualization, machine learning, and real-time analytics, helping organizations make data-driven decisions and improve their business outcomes.

- **Human URL:** [ https://www.databricks.com]( https://www.databricks.com)

#### Tags

- Analytics
- Data
- Visualize

#### Properties

- [Documentation]( https://www.databricks.com)
- [API Reference](https://docs.databricks.com/api/workspace/introduction)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Clusters API

The Databricks Clusters API allows you to create, start, edit, list, terminate, and delete clusters. Clusters are managed cloud resources that enable you to run data engineering and data science workloads on Apache Spark in the cloud. The API provides programmatic control over cluster lifecycle management, configuration, and monitoring.

- **Human URL:** [https://docs.databricks.com/api/workspace/clusters](https://docs.databricks.com/api/workspace/clusters)

#### Tags

- Clusters
- Compute
- Infrastructure

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/clusters)
- [OpenAPI](openapi/databricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/databricks-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-create-cluster-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-edit-cluster-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-cluster-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-spark-node-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-auto-scale-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-aws-attributes-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-azure-attributes-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-gcp-attributes-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-init-script-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-cluster-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-error-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/databricks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Databricks Jobs API

The Databricks Jobs API allows you to create, edit, delete, and trigger jobs. Jobs are the primary mechanism for running automated workloads on Databricks, including notebooks, JARs, Python scripts, and Spark submit applications. The API supports complex multi-task workflows with dependencies, scheduling, and monitoring capabilities.

- **Human URL:** [https://docs.databricks.com/api/workspace/jobs](https://docs.databricks.com/api/workspace/jobs)

#### Tags

- Jobs
- Orchestration
- Scheduling
- Workflows

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/jobs)
- [OpenAPI](openapi/databricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/databricks-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-create-job-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-task-settings-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-job-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-job-email-notifications-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-webhook-notifications-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-cron-schedule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-git-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-library-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-access-control-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-job-settings-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-run-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-run-task-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/databricks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Databricks DBFS API

The Databricks File System (DBFS) API is a distributed file system mounted into a Databricks workspace and available on Databricks clusters. The API enables you to interact with object storage using directory and file semantics, allowing you to put, get, list, and delete files and directories programmatically.

- **Human URL:** [https://docs.databricks.com/api/workspace/dbfs](https://docs.databricks.com/api/workspace/dbfs)

#### Tags

- Data
- Files
- Storage

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/dbfs)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Workspace API

The Databricks Workspace API allows you to list, import, export, and delete notebooks, folders, and libraries in a Databricks workspace. It provides programmatic access to manage workspace objects, enabling automation of notebook deployment and workspace organization.

- **Human URL:** [https://docs.databricks.com/api/workspace/workspace](https://docs.databricks.com/api/workspace/workspace)

#### Tags

- Folders
- Notebooks
- Workspace

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/workspace)
- [OpenAPI](openapi/databricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/databricks-workspace-object-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/databricks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Databricks SQL Warehouses API

The Databricks SQL Warehouses API allows you to create, edit, list, start, stop, and delete SQL warehouses. SQL warehouses are compute resources that enable you to run SQL commands on data objects within Databricks SQL, providing serverless or classic compute options for analytical workloads.

- **Human URL:** [https://docs.databricks.com/api/workspace/warehouses](https://docs.databricks.com/api/workspace/warehouses)

#### Tags

- Analytics
- SQL
- Warehouses

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/warehouses)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Pipelines API

The Databricks Pipelines API allows you to create, edit, delete, start, and stop Delta Live Tables pipelines. Delta Live Tables is a declarative framework for building reliable, maintainable, and testable data processing pipelines. The API provides full lifecycle management of ETL pipelines.

- **Human URL:** [https://docs.databricks.com/api/workspace/pipelines](https://docs.databricks.com/api/workspace/pipelines)

#### Tags

- Delta Live Tables
- ETL
- Pipelines

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/pipelines)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Serving Endpoints API

The Databricks Serving Endpoints API allows you to create, update, query, and delete model serving endpoints. Mosaic AI Model Serving provides a unified interface to deploy, govern, and query AI models, including custom models, generative AI models, and large language models, with high availability and low latency.

- **Human URL:** [https://docs.databricks.com/api/workspace/servingendpoints](https://docs.databricks.com/api/workspace/servingendpoints)

#### Tags

- AI
- Machine Learning
- Model Serving

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/servingendpoints)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Secrets API

The Databricks Secrets API allows you to manage secrets, secret scopes, and secret ACLs. Secrets provide a secure way to store and reference credentials and other sensitive information in notebooks and jobs without exposing them in plaintext.

- **Human URL:** [https://docs.databricks.com/api/workspace/secrets](https://docs.databricks.com/api/workspace/secrets)

#### Tags

- Credentials
- Secrets
- Security

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/secrets)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Instance Pools API

The Databricks Instance Pools API allows you to create, edit, delete, and list instance pools. Instance pools reduce cluster start and auto-scaling times by maintaining a set of idle, ready-to-use cloud instances, improving performance and reducing costs for frequently used cluster configurations.

- **Human URL:** [https://docs.databricks.com/api/workspace/instancepools](https://docs.databricks.com/api/workspace/instancepools)

#### Tags

- Clusters
- Compute
- Infrastructure

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/instancepools)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Token Management API

The Databricks Token Management API enables workspace administrators to manage personal access tokens for users and service principals. It allows creating, listing, and revoking tokens, providing centralized control over API authentication credentials.

- **Human URL:** [https://docs.databricks.com/api/workspace/tokenmanagement](https://docs.databricks.com/api/workspace/tokenmanagement)

#### Tags

- Authentication
- Security
- Tokens

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/tokenmanagement)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Catalogs API

The Databricks Catalogs API is part of Unity Catalog and allows you to create, update, list, and delete catalogs. Catalogs are the top-level container for data objects in Unity Catalog, providing a three-level namespace (catalog.schema.table) for organizing and governing data assets across workspaces.

- **Human URL:** [https://docs.databricks.com/api/workspace/catalogs](https://docs.databricks.com/api/workspace/catalogs)

#### Tags

- Data Governance
- Metadata
- Unity Catalog

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/catalogs)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Vector Search Indexes API

The Databricks Vector Search Indexes API allows you to create, manage, query, and delete vector search indexes. Vector Search enables you to store vector representations of your data and perform similarity searches, powering retrieval-augmented generation (RAG) applications and other AI use cases.

- **Human URL:** [https://docs.databricks.com/api/workspace/vectorsearchindexes](https://docs.databricks.com/api/workspace/vectorsearchindexes)

#### Tags

- AI
- Embeddings
- Vector Search

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/vectorsearchindexes)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Model Versions API

The Databricks Model Versions API allows you to manage model versions within the Unity Catalog model registry. It provides programmatic access to create, update, list, and delete model versions, enabling automated ML lifecycle management and model governance.

- **Human URL:** [https://docs.databricks.com/api/workspace/modelversions](https://docs.databricks.com/api/workspace/modelversions)

#### Tags

- Machine Learning
- MLflow
- Model Registry

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/modelversions)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Permissions API

The Databricks Permissions API allows you to manage permissions on workspace objects such as clusters, jobs, notebooks, and SQL warehouses. It provides programmatic access to get, set, and update access control lists for various Databricks resources, enabling fine-grained authorization management.

- **Human URL:** [https://docs.databricks.com/api/workspace/permissions](https://docs.databricks.com/api/workspace/permissions)

#### Tags

- Access Control
- Authorization
- Security

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/permissions)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Repos API

The Databricks Repos API allows you to manage Git repositories within a Databricks workspace. It provides programmatic access to create, update, delete, and list repos, as well as perform Git operations like pulling latest changes, enabling version-controlled notebook and code development.

- **Human URL:** [https://docs.databricks.com/api/workspace/repos](https://docs.databricks.com/api/workspace/repos)

#### Tags

- Git
- Repositories
- Version Control

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/repos)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Git Credentials API

The Databricks Git Credentials API allows you to manage Git credentials for authenticating with Git providers. It provides programmatic access to create, update, delete, and list stored Git credentials, enabling seamless integration with GitHub, GitLab, Bitbucket, and other Git hosting services.

- **Human URL:** [https://docs.databricks.com/api/workspace/gitcredentials](https://docs.databricks.com/api/workspace/gitcredentials)

#### Tags

- Authentication
- Credentials
- Git

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/gitcredentials)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Cluster Policies API

The Databricks Cluster Policies API allows administrators to create, edit, delete, and list cluster policies. Cluster policies limit the ability to configure clusters based on a set of rules, enabling administrators to enforce cost controls and governance over compute resources.

- **Human URL:** [https://docs.databricks.com/api/workspace/clusterpolicies](https://docs.databricks.com/api/workspace/clusterpolicies)

#### Tags

- Clusters
- Governance
- Policies

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/clusterpolicies)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Libraries API

The Databricks Libraries API allows you to install, uninstall, and list libraries on clusters. It provides programmatic management of Python, Java, Scala, and R library dependencies for cluster workloads, enabling automated environment configuration.

- **Human URL:** [https://docs.databricks.com/api/workspace/libraries](https://docs.databricks.com/api/workspace/libraries)

#### Tags

- Clusters
- Dependencies
- Libraries

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/libraries)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Global Init Scripts API

The Databricks Global Init Scripts API enables workspace administrators to manage global initialization scripts that run on every cluster in the workspace. It provides programmatic access to create, update, delete, list, and reorder init scripts for consistent cluster configuration.

- **Human URL:** [https://docs.databricks.com/api/workspace/globalinitscripts](https://docs.databricks.com/api/workspace/globalinitscripts)

#### Tags

- Administration
- Compute
- Configuration

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/globalinitscripts)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Command Execution API

The Databricks Command Execution API allows you to execute Python, Scala, SQL, or R commands on running Databricks clusters. It provides programmatic access to create execution contexts, run commands, check status, and retrieve results, enabling remote interactive cluster usage.

- **Human URL:** [https://docs.databricks.com/api/workspace/commandexecution](https://docs.databricks.com/api/workspace/commandexecution)

#### Tags

- Commands
- Compute
- Execution

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/commandexecution)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Statement Execution API

The Databricks Statement Execution API allows you to execute SQL statements on Databricks SQL warehouses and retrieve results. It provides a synchronous and asynchronous interface for running SQL queries, checking execution status, fetching result data, and canceling statements.

- **Human URL:** [https://docs.databricks.com/api/workspace/statementexecution](https://docs.databricks.com/api/workspace/statementexecution)

#### Tags

- Queries
- SQL
- Warehouses

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/statementexecution)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Queries API

The Databricks Queries API allows you to create, update, delete, list, and run saved SQL queries in Databricks SQL. It provides programmatic management of SQL query objects, enabling automation of analytical workflows and query lifecycle management.

- **Human URL:** [https://docs.databricks.com/api/workspace/queries](https://docs.databricks.com/api/workspace/queries)

#### Tags

- Analytics
- Queries
- SQL

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/queries)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Alerts API

The Databricks Alerts API allows you to create, update, delete, and list alerts in Databricks SQL. Alerts automate query execution, evaluate custom conditions, and deliver notifications when those conditions are met, enabling proactive monitoring of business data.

- **Human URL:** [https://docs.databricks.com/api/workspace/alerts](https://docs.databricks.com/api/workspace/alerts)

#### Tags

- Alerts
- Monitoring
- SQL

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/alerts)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Schemas API

The Databricks Schemas API is part of Unity Catalog and allows you to create, update, list, and delete schemas. Schemas, also known as databases, reside within catalogs and contain tables, views, volumes, functions, and models, providing the second level of the three-level namespace for data organization.

- **Human URL:** [https://docs.databricks.com/api/workspace/schemas](https://docs.databricks.com/api/workspace/schemas)

#### Tags

- Data Governance
- Schemas
- Unity Catalog

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/schemas)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Tables API

The Databricks Tables API is part of Unity Catalog and allows you to create, update, list, and delete tables. Tables reside within schemas and represent structured data assets, supporting managed and external table types with full governance and access control through Unity Catalog.

- **Human URL:** [https://docs.databricks.com/api/workspace/tables](https://docs.databricks.com/api/workspace/tables)

#### Tags

- Data Governance
- Tables
- Unity Catalog

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/tables)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Volumes API

The Databricks Volumes API is part of Unity Catalog and allows you to create, update, list, and delete volumes. Volumes provide a governed location for storing and accessing non-tabular data files such as images, documents, and other unstructured data within the Unity Catalog namespace.

- **Human URL:** [https://docs.databricks.com/api/workspace/volumes](https://docs.databricks.com/api/workspace/volumes)

#### Tags

- Storage
- Unity Catalog
- Volumes

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/volumes)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Functions API

The Databricks Functions API is part of Unity Catalog and allows you to create, list, and delete user-defined functions. Functions reside within schemas and can be used in SQL queries and notebooks, with full governance and access control managed through Unity Catalog.

- **Human URL:** [https://docs.databricks.com/api/workspace/functions](https://docs.databricks.com/api/workspace/functions)

#### Tags

- Functions
- SQL
- Unity Catalog

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/functions)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Grants API

The Databricks Grants API is part of Unity Catalog and allows you to get, update, and manage permissions on Unity Catalog securable objects. It provides programmatic control over access to catalogs, schemas, tables, volumes, and other data assets, enabling fine-grained data governance.

- **Human URL:** [https://docs.databricks.com/api/workspace/grants](https://docs.databricks.com/api/workspace/grants)

#### Tags

- Access Control
- Security
- Unity Catalog

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/grants)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks External Locations API

The Databricks External Locations API is part of Unity Catalog and allows you to create, update, list, and delete external locations. External locations combine a cloud storage path with a storage credential, enabling governed access to data stored in external cloud storage systems.

- **Human URL:** [https://docs.databricks.com/api/workspace/externallocations](https://docs.databricks.com/api/workspace/externallocations)

#### Tags

- Cloud Storage
- Storage
- Unity Catalog

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/externallocations)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Storage Credentials API

The Databricks Storage Credentials API is part of Unity Catalog and allows you to create, update, list, and delete storage credentials. Storage credentials contain long-term cloud credentials that provide access to cloud storage, and are referenced when creating external locations for governing data access.

- **Human URL:** [https://docs.databricks.com/api/workspace/storagecredentials](https://docs.databricks.com/api/workspace/storagecredentials)

#### Tags

- Cloud Storage
- Security
- Unity Catalog

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/storagecredentials)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Metastores API

The Databricks Metastores API is part of Unity Catalog and allows you to create, update, list, and delete metastores. A metastore is the top-level container of objects in Unity Catalog, providing centralized metadata management, access control, and data governance across workspaces.

- **Human URL:** [https://docs.databricks.com/api/workspace/metastores](https://docs.databricks.com/api/workspace/metastores)

#### Tags

- Data Governance
- Metadata
- Unity Catalog

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/metastores)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Connections API

The Databricks Connections API is part of Unity Catalog and allows you to create, update, list, and delete connections to external data sources. Connections enable federated queries across external databases and data systems, extending Unity Catalog governance to data outside the lakehouse.

- **Human URL:** [https://docs.databricks.com/api/workspace/connections](https://docs.databricks.com/api/workspace/connections)

#### Tags

- Connections
- External Data
- Unity Catalog

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/connections)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Registered Models API

The Databricks Registered Models API allows you to create, update, list, and delete registered models in the Unity Catalog model registry. It provides centralized model lifecycle management with versioning, aliasing, and governance capabilities for machine learning models.

- **Human URL:** [https://docs.databricks.com/api/workspace/registeredmodels](https://docs.databricks.com/api/workspace/registeredmodels)

#### Tags

- Machine Learning
- MLflow
- Model Registry

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/registeredmodels)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Experiments API

The Databricks Experiments API allows you to create, update, list, and manage MLflow experiments. Experiments are the primary unit of organization in MLflow, grouping runs that track parameters, metrics, and artifacts for machine learning model development and comparison.

- **Human URL:** [https://docs.databricks.com/api/workspace/experiments](https://docs.databricks.com/api/workspace/experiments)

#### Tags

- Experiments
- Machine Learning
- MLflow

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/experiments)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Online Tables API

The Databricks Online Tables API allows you to create, get, and delete online tables. Online tables are materialized copies of Delta tables optimized for low-latency lookups, enabling real-time feature serving and online inference workloads for machine learning applications.

- **Human URL:** [https://docs.databricks.com/api/workspace/onlinetables](https://docs.databricks.com/api/workspace/onlinetables)

#### Tags

- Feature Serving
- Real-Time
- Tables

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/onlinetables)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Quality Monitors API

The Databricks Quality Monitors API allows you to create, update, get, and delete data quality monitors for tables. Quality monitors enable automated data profiling and anomaly detection, providing continuous monitoring of data quality metrics and statistical properties.

- **Human URL:** [https://docs.databricks.com/api/workspace/qualitymonitors](https://docs.databricks.com/api/workspace/qualitymonitors)

#### Tags

- Data Quality
- Monitoring
- Observability

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/qualitymonitors)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Vector Search Endpoints API

The Databricks Vector Search Endpoints API allows you to create, list, get, and delete vector search endpoints. Vector search endpoints are compute resources that host vector search indexes, enabling similarity search queries for retrieval-augmented generation and other AI applications.

- **Human URL:** [https://docs.databricks.com/api/workspace/vectorsearchendpoints](https://docs.databricks.com/api/workspace/vectorsearchendpoints)

#### Tags

- AI
- Compute
- Vector Search

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/vectorsearchendpoints)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Shares API

The Databricks Shares API is part of Delta Sharing and allows you to create, update, list, and delete shares. A share is a read-only logical collection of tables and table partitions that a data provider wants to share with one or more recipients for secure cross-organization data sharing.

- **Human URL:** [https://docs.databricks.com/api/workspace/shares](https://docs.databricks.com/api/workspace/shares)

#### Tags

- Collaboration
- Data Sharing
- Delta Sharing

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/shares)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Recipients API

The Databricks Recipients API is part of Delta Sharing and allows you to create, update, list, and delete recipients. A recipient is an entity that receives shared data from a provider, and can be either a Databricks workspace or an open-protocol recipient using bearer tokens.

- **Human URL:** [https://docs.databricks.com/api/workspace/recipients](https://docs.databricks.com/api/workspace/recipients)

#### Tags

- Access Control
- Data Sharing
- Delta Sharing

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/recipients)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Providers API

The Databricks Providers API is part of Delta Sharing and allows you to create, update, list, and delete data providers. Providers represent organizations that share data through Delta Sharing, enabling secure and governed cross-organization data exchange.

- **Human URL:** [https://docs.databricks.com/api/workspace/providers](https://docs.databricks.com/api/workspace/providers)

#### Tags

- Data Sharing
- Delta Sharing
- Marketplace

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/providers)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Clean Rooms API

The Databricks Clean Rooms API allows you to create, update, list, and delete clean rooms. Clean rooms use Delta Sharing and serverless compute to provide a secure and privacy-protecting environment where multiple parties can collaborate on sensitive enterprise data without exposing raw data.

- **Human URL:** [https://docs.databricks.com/api/workspace/cleanrooms](https://docs.databricks.com/api/workspace/cleanrooms)

#### Tags

- Clean Rooms
- Collaboration
- Privacy

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/cleanrooms)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Notification Destinations API

The Databricks Notification Destinations API allows you to create, update, list, and delete notification destinations for a workspace. Notification destinations define where alerts and notifications are sent, supporting integrations with email, Slack, PagerDuty, webhooks, and other channels.

- **Human URL:** [https://docs.databricks.com/api/workspace/notificationdestinations](https://docs.databricks.com/api/workspace/notificationdestinations)

#### Tags

- Alerts
- Integration
- Notifications

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/notificationdestinations)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Apps API

The Databricks Apps API allows you to create, deploy, manage, and delete Databricks Apps. Apps run directly on a Databricks workspace, integrating with workspace data and services to build custom data applications, dashboards, and tools with built-in authentication and authorization.

- **Human URL:** [https://docs.databricks.com/api/workspace/apps](https://docs.databricks.com/api/workspace/apps)

#### Tags

- Applications
- Deployment
- Development

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/apps)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Lakeview API

The Databricks Lakeview API allows you to create, update, get, list, and delete AI/BI dashboards. Lakeview dashboards provide a modern visualization experience built on top of Databricks SQL, enabling interactive data exploration and business intelligence reporting.

- **Human URL:** [https://docs.databricks.com/api/workspace/lakeview](https://docs.databricks.com/api/workspace/lakeview)

#### Tags

- Analytics
- Dashboards
- Visualization

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/lakeview)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Files API

The Databricks Files API provides a standard HTTP interface for reading, writing, listing, and deleting files and directories in Unity Catalog volumes and other workspace storage locations. It supports direct file access by URI, enabling seamless file management for data and ML workloads.

- **Human URL:** [https://docs.databricks.com/api/workspace/files](https://docs.databricks.com/api/workspace/files)

#### Tags

- Files
- Storage
- Unity Catalog

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/files)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Tokens API

The Databricks Tokens API allows you to create, list, and revoke personal access tokens. Personal access tokens are used to authenticate with the Databricks REST API and integrations, providing an alternative to OAuth for programmatic access.

- **Human URL:** [https://docs.databricks.com/api/workspace/tokens](https://docs.databricks.com/api/workspace/tokens)

#### Tags

- Authentication
- Security
- Tokens

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/tokens)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks IP Access Lists API

The Databricks IP Access Lists API allows administrators to configure IP allow lists and block lists for a workspace. It provides programmatic management of network security rules to restrict access to the workspace based on IP addresses or CIDR ranges.

- **Human URL:** [https://docs.databricks.com/api/workspace/ipaccesslists](https://docs.databricks.com/api/workspace/ipaccesslists)

#### Tags

- Access Control
- Networking
- Security

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/ipaccesslists)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Current User API

The Databricks Current User API allows you to retrieve information about the currently authenticated user or service principal. It returns identity details including username, display name, and group memberships for the caller making the API request.

- **Human URL:** [https://docs.databricks.com/api/workspace/currentuser](https://docs.databricks.com/api/workspace/currentuser)

#### Tags

- Authentication
- Identity
- Users

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/currentuser)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Groups API

The Databricks Groups API allows you to create, update, list, and delete groups in a workspace. Groups simplify identity management by enabling administrators to assign access permissions to collections of users and service principals rather than managing them individually.

- **Human URL:** [https://docs.databricks.com/api/workspace/groups](https://docs.databricks.com/api/workspace/groups)

#### Tags

- Access Control
- Groups
- Identity

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/groups)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Service Principals API

The Databricks Service Principals API allows you to create, update, list, and delete service principals in a workspace. Service principals are identities for automated tools, jobs, scripts, apps, and CI/CD platforms, enabling secure non-interactive authentication with Databricks resources.

- **Human URL:** [https://docs.databricks.com/api/workspace/serviceprincipals](https://docs.databricks.com/api/workspace/serviceprincipals)

#### Tags

- Automation
- Identity
- Service Principals

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/serviceprincipals)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Users API

The Databricks Users API allows you to create, update, list, and delete users in a workspace. It provides programmatic management of user identities and their workspace access, supporting SCIM protocol for identity provider integration and automated user provisioning.

- **Human URL:** [https://docs.databricks.com/api/workspace/users](https://docs.databricks.com/api/workspace/users)

#### Tags

- Administration
- Identity
- Users

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/users)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Dashboards API

The Databricks Dashboards API allows you to create, update, list, and delete legacy SQL dashboards. Dashboards provide visual representations of query results, enabling business intelligence reporting and data visualization directly within Databricks SQL.

- **Human URL:** [https://docs.databricks.com/api/workspace/dashboards](https://docs.databricks.com/api/workspace/dashboards)

#### Tags

- Dashboards
- SQL
- Visualization

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/dashboards)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Model Registry API

The Databricks Model Registry API provides the workspace model registry for managing the full lifecycle of ML models. It enables creating registered models, managing model versions, transitioning stages, and setting permissions for collaborative model governance and deployment.

- **Human URL:** [https://docs.databricks.com/api/workspace/modelregistry](https://docs.databricks.com/api/workspace/modelregistry)

#### Tags

- Machine Learning
- MLflow
- Model Registry

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/modelregistry)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Workspace Bindings API

The Databricks Workspace Bindings API allows you to manage the binding of Unity Catalog securables to specific workspaces. It enables configuring whether catalogs and other objects are available across all workspaces or isolated to specific ones, supporting multi-workspace governance.

- **Human URL:** [https://docs.databricks.com/api/workspace/workspacebindings](https://docs.databricks.com/api/workspace/workspacebindings)

#### Tags

- Governance
- Unity Catalog
- Workspace

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/workspacebindings)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks System Schemas API

The Databricks System Schemas API allows you to enable, disable, and list system schemas within a metastore. System schemas contain system tables that provide operational data about your Databricks account, including audit logs, billing usage, lineage, and access history.

- **Human URL:** [https://docs.databricks.com/api/workspace/systemschemas](https://docs.databricks.com/api/workspace/systemschemas)

#### Tags

- Monitoring
- System Tables
- Unity Catalog

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/systemschemas)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Databricks Table Constraints API

The Databricks Table Constraints API allows you to create and delete primary key and foreign key constraints on Unity Catalog tables. Table constraints define relationships between tables, supporting data integrity and enabling query optimization across the lakehouse.

- **Human URL:** [https://docs.databricks.com/api/workspace/tableconstraints](https://docs.databricks.com/api/workspace/tableconstraints)

#### Tags

- Data Quality
- Tables
- Unity Catalog

#### Properties

- [Documentation](https://docs.databricks.com/api/workspace/tableconstraints)
- [Postman Collection](collections/databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Authentication](https://docs.databricks.com/dev-tools/auth.html)
- [Getting Started](https://docs.databricks.com/getting-started/index.html)
- [S D Ks](https://docs.databricks.com/dev-tools/sdks.html)
- [Status Page](https://status.databricks.com/)
- [Support](https://help.databricks.com/)
- [API Reference](https://docs.databricks.com/api/workspace/introduction)
- [Documentation](https://docs.databricks.com/aws/en/reference/api)
- [Pricing](https://www.databricks.com/product/pricing)
- [Sign Up](https://www.databricks.com/try-databricks)
- [Privacy Policy](https://www.databricks.com/legal/privacynotice)
- [Terms of Service](https://www.databricks.com/legal/terms-of-use)
- [Security](https://www.databricks.com/trust)
- [Rate Limits](https://docs.databricks.com/aws/en/resources/limits)
- [Changelog](https://docs.databricks.com/aws/en/release-notes/)
- [Blog](https://www.databricks.com/blog)
- [Support](https://community.databricks.com/)
- [GitHub Organization](https://github.com/databricks)
- [SDK](https://github.com/databricks/databricks-sdk-py)
- [SDK](https://github.com/databricks/databricks-sdk-go)
- [C L I](https://github.com/databricks/cli)
- [Documentation](https://docs.databricks.com/aws/en/dev-tools/cli)
- [X (Twitter)](https://twitter.com/databricks)
- [LinkedIn](https://www.linkedin.com/company/databricks)
- [Login](https://login.databricks.com/)
- [Contact](https://www.databricks.com/company/contact)
- [Training](https://www.databricks.com/learn/training/home)
- [Academy](https://customer-academy.databricks.com/learn)
- [SDK](https://github.com/databricks/databricks-sdk-java)
- [SDK](https://github.com/databricks/databricks-sql-python)
- [SDK](https://github.com/databricks/terraform-provider-databricks)
- [API Reference](https://docs.databricks.com/aws/en/reference/mlflow-api)
- [Security](https://www.databricks.com/trust/security-features)
- [Authentication](https://docs.databricks.com/aws/en/dev-tools/auth)
- [API Reference](https://api-docs.databricks.com/)
- [OpenAPI](openapi/databricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/databricks-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/databricks-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/databricks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/databricks-spectral-rules.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://docs.databricks.com/aws/en/integrations)
- [Agent Skill](https://github.com/databricks/databricks-agent-skills)
- [L L Ms Txt](https://docs.databricks.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**Email:** support@databricks.com
**URL:** https://www.databricks.com/
