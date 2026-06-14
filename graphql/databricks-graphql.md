# Databricks GraphQL Schema

## Overview

Databricks does not currently offer a native GraphQL API. Its public surface area is entirely REST-based, documented at [https://docs.databricks.com/api/workspace/introduction](https://docs.databricks.com/api/workspace/introduction). The schema below is a **conceptual GraphQL representation** of the Databricks platform derived from its REST API, Unity Catalog data model, MLflow, Delta Live Tables, and related surface areas. It is intended to illustrate how Databricks resources could be expressed as a strongly-typed GraphQL schema for tooling, federation, or gateway integration purposes.

## Source

- REST API Reference: https://docs.databricks.com/api/workspace/introduction
- GitHub Organization: https://github.com/databricks
- Unity Catalog: https://docs.databricks.com/api/workspace/catalogs
- MLflow: https://docs.databricks.com/aws/en/reference/mlflow-api

## Schema Coverage

The schema covers the following resource domains:

| Domain | Types |
|---|---|
| Compute / Clusters | Cluster, ClusterPolicy, ClusterSpec, ClusterEvent, NodeType, SparkVersion, RuntimeEngine, AutoScale, AwsAttributes, AzureAttributes, GcpAttributes, InstancePool, Library, InitScript |
| Jobs / Workflows | Job, JobCluster, JobSettings, Task, TaskDependency, Run, RunState, TaskRun, Schedule, GitSource, EmailNotifications, WebhookNotifications |
| Workspace | Workspace, WorkspaceObject, Notebook, Directory, File, Repo, GlobalInitScript |
| Identity / Security | User, Group, ServicePrincipal, Token, SecretScope, Secret, Permission, ACLItem, IPAccessList, EncryptionConfig |
| Unity Catalog | Catalog, Schema, Table, Column, Partition, View, Volume, Function, Grant, MetastoreDetail, StorageCredential, ExternalLocation, Connection, WorkspaceBinding, TableConstraint |
| SQL | SQLWarehouse, Query, Dashboard, Widget, Alert, Statement, StatementResult |
| ML / MLflow | MLflowExperiment, MLflowRun, MLflowMetric, MLflowParam, MLflowArtifact, RegisteredModel, ModelVersion, ModelAlias |
| Serving | ServingEndpoint, ServedModel, ServingConfig, TrafficConfig |
| Pipelines (DLT) | Pipeline, PipelineSpec, DLTSettings, PipelineCluster, PipelineEvent |
| Delta Sharing | Share, ShareObject, Recipient, Provider |
| Vector Search | VectorSearchEndpoint, VectorSearchIndex |
| Apps / Dashboards | App, LakeviewDashboard, NotificationDestination, OnlineTable, QualityMonitor |

Total types: **71**

## Usage Notes

Because Databricks is REST-only, this schema would require a GraphQL gateway or resolver layer (e.g., Apollo Federation, Hasura Remote Schema, or a custom GraphQL server) that proxies calls to the underlying REST endpoints. Field names follow camelCase GraphQL conventions mapped from the snake_case REST responses.
