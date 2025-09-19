# Get Client Information

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
  "name": "string",
  "email": "string"
}
```

## Sample Request
```bash
curl -X GET \
  https://api.example.com/client/info?client_id=12345 \
  -H "Authorization: Bearer <token>"
```

## Sample Response
```json
{
  "client_id": "12345",
  "name": "John Doe",
  "email": "john.doe@example.com"
}
```