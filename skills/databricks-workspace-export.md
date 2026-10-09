---
name: databricks-workspace-export
description: Export a workspace object after locating it in the workspace hierarchy.
api: openapi/databricks-workspace-api-openapi.yml
operations:
- listWorkspaceObjects
- getWorkspaceObjectStatus
- exportWorkspaceObject
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/databricks-workspace-api-openapi.yml ; every operationId checked against the contract
---

# databricks-workspace-export

Export a workspace object after locating it in the workspace hierarchy.

## Steps

1. 1. Use `listWorkspaceObjects` with the `path` query parameter to list objects in the target directory.
2. 2. Use `getWorkspaceObjectStatus` with the `path` of the desired object to verify its status.
3. 3. Use `exportWorkspaceObject` with the `path` and `format` fields to retrieve the object's content.

## Rules

- Auth: Include a Bearer token in the `Authorization` header as defined by the `bearerAuth` scheme.
- No rate limit is documented; exhaustion returns no specific HTTP status.
- Pagination is not applicable to these endpoints.
