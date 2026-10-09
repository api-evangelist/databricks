---
name: databricks-create-and-run-job
description: Create a new Databricks job, trigger it, and retrieve its run output.
api: openapi/databricks-jobs-api-openapi.yml
operations:
- createJob
- runJobNow
- getJobRun
- getJobRunOutput
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/databricks-jobs-api-openapi.yml ; every operationId checked against the contract
---

# databricks-create-and-run-job

Create a new Databricks job, trigger it, and retrieve its run output.

## Steps

1. 1. Use `createJob` with the request body fields `name`, `new_cluster`, `spark_jar_task`, etc., as defined in the contract.
2. 2. Use `runJobNow` with the header `Authorization: Bearer <token>` and the field `job_id` returned from `createJob`.
3. 3. Use `getJobRun` with the header `Authorization: Bearer <token>` and the field `run_id` returned from `runJobNow` to poll the run status.
4. 4. Use `getJobRunOutput` with the header `Authorization: Bearer <token>` and the field `run_id` to fetch the job's output once the run is completed.

## Rules

- Authentication: Include an `Authorization: Bearer <token>` header for all requests (bearerAuth).
- Idempotency: `createJob` is not idempotent; ensure unique job names or handle duplicates.
- Errors: The API returns standard HTTP error codes; handle 4xx for client errors and 5xx for server errors.
