# Endpoint: <METHOD> <PATH>

- Stability: `experimental | beta | stable`
- Since: `vX.Y.Z`
- Scope: `public | partner | internal`

## Description
Concise purpose and behavior.

## Authentication
- Scheme and required scopes/permissions

## Request
- Path params
- Query params
- Headers
- Body schema

## Response
- Status codes and bodies

## Errors
- Error codes and meanings

## Examples
```bash
curl -sS -H 'Authorization: Bearer <TOKEN>' \
  -X <METHOD> 'https://api.example.com<PATH>' \
  -d '{"example": true}'
```