# HTTP Endpoints

Use this file to document REST/HTTP endpoints.

## Conventions
- Base URL
- Authentication scheme
- Error model
- Pagination, filtering, sorting

## Example endpoint

- Method: GET
- Path: `/v1/widgets`
- Query params:
  - `limit` (integer, optional, default 20)
  - `cursor` (string, optional)
- Response: 200 OK

```json
{
  "items": [{ "id": "w_123", "name": "Example" }],
  "nextCursor": null
}
```

### cURL
```bash
curl -sS -H 'Authorization: Bearer <TOKEN>' \
  'https://api.example.com/v1/widgets?limit=20'
```