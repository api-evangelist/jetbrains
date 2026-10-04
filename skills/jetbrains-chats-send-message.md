---
name: jetbrains-chats-send-message
description: Send a message to a chat channel after retrieving the list of available channels.
api: openapi/jetbrains-chats-api-openapi.yml
operations:
- listChannels
- sendMessage
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/jetbrains-chats-api-openapi.yml ; every operationId checked against the contract
---

# jetbrains-chats-send-message

Send a message to a chat channel after retrieving the list of available channels.

## Steps

1. 1. `listChannels` – no required query parameters or request body fields.
2. 2. `sendMessage` – requires the request body fields `channelId` and `content` (as shown in the contract) and the `Authorization` header.

## Rules

- Authentication: provide either a `Basic` auth header or a `Bearer` token as defined by the `basicAuth` and `bearerAuth` schemes.
- Idempotency: not applicable for these operations.
