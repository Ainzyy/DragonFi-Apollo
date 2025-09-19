# Update Client Information

## Headers
- **Authorization**: Bearer <token>

## Query Parameters
- **client_id**: The ID of the client to update.

## Response Codes
- **200**: Success
- **404**: Client Not Found

## Response Body
```json
{
  "client_id": "string",
  "status": "updated"
}
```

## Sample Request
```bash
curl -X PUT \
  https://api.example.com/client/update?client_id=12345 \
  -H "Authorization: Bearer <token>" \
  -d '{"name": "Jane Doe"}'
```

## Sample Response
```json
{
  "client_id": "12345",
  "status": "updated"
}
```