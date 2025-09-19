# Get Lookups

## Headers
- **Authorization**: Bearer <token>

## Query Parameters
- None

## Response Codes
- **200**: Success

## Response Body
```json
{
  "countries": ["string"],
  "regions": ["string"]
}
```

## Sample Request
```bash
curl -X GET \
  https://api.example.com/lookups \
  -H "Authorization: Bearer <token>"
```

## Sample Response
```json
{
  "countries": ["USA", "Canada"],
  "regions": ["North America", "Europe"]
}
```