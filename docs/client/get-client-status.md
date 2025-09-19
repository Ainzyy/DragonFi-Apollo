# Get Client Status

## Headers
- **Authorization**: Bearer <token>

## Query Parameters
- **client_id**: The ID of the client.

## Response Codes
- **200**: Success
- **404**: Client Not Found

## Response Body
```json
{
  "client_id": "string",
  "status": "active"
}
```

## Sample Request
```bash
curl -X GET \
  https://api.example.com/client/status?client_id=12345 \
  -H "Authorization: Bearer <token>"
```

## Sample Response
```json
{
  "client_id": "12345",
  "status": "active"
}
```