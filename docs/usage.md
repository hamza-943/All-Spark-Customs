# Usage Guide

Use these patterns to write examples for your public APIs and components.

## Programmatic API (library)

```ts
// TypeScript example
import { createClient } from 'all-spark-customs';

const client = createClient({ baseUrl: 'https://api.example.com' });
const result = await client.widgets.list({ limit: 10 });
console.log(result.items);
```

```python
# Python example
from all_spark_customs import Client

client = Client(base_url='https://api.example.com')
items = client.widgets.list(limit=10)
print(items)
```

## HTTP API

```bash
curl -sS -H 'Authorization: Bearer <TOKEN>' \
     'https://api.example.com/v1/widgets?limit=10'
```

## CLI

```bash
all-spark widgets list --limit 10 --output json
```

Replace these with real examples once the implementation exists.