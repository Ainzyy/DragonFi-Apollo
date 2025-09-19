# Get Regions

## Headers
- **Authorization**: Bearer <token>

## Query Parameters
- None

## Response Codes
- **200**: Success

## Response Body
```json
[
  "string"
]
```

## Sample Request
```bash
curl -X GET \
  https://api.example.com/lookups/regions \
  -H "Authorization: Bearer <token>"
```

## Sample Response
```json
[
  "North America",
  "Europe"
]
```