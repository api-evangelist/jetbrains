---
name: jetbrains-create-issue-with-comment
description: Create a new issue and add a comment to it.
api: openapi/jetbrains-issues-api-openapi.yml
operations:
- createIssue
- addIssueComment
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/jetbrains-issues-api-openapi.yml ; every operationId checked against the contract
---

# jetbrains-create-issue-with-comment

Create a new issue and add a comment to it.

## Steps

1. 1. Use `createIssue` with the request body fields required to define the issue (e.g., title, description, project).
2. 2. Use `addIssueComment` with the path parameter `issueId` returned from the previous step and the request body field `text` for the comment.

## Rules

- Authentication: include either a `Authorization: Basic <credentials>` header (basicAuth) or a `Authorization: Bearer <token>` header (bearerAuth).
- Idempotency: not applicable for these operations.
