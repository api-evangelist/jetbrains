---
name: jetbrains-build-queue-trigger-and-list
description: Trigger a new build and then retrieve the current build queue.
api: openapi/jetbrains-build-queue-api-openapi.yml
operations:
- triggerBuild
- listBuildQueue
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/jetbrains-build-queue-api-openapi.yml ; every operationId checked against the contract
---

# jetbrains-build-queue-trigger-and-list

Trigger a new build and then retrieve the current build queue.

## Steps

1. 1. Call `triggerBuild` with the required request body fields (as defined in the API contract).
2. 2. Call `listBuildQueue` to fetch the updated queue, using any query parameters shown in the contract.

## Rules

- Authentication: include either a Basic Auth header or a Bearer token as defined by the `basicAuth` or `bearerAuth` schemes.
- No rate‑limit information is provided; the API does not specify a limit or exhaustion response.
