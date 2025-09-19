# Verify Client

## Headers
- **Authorization**: Bearer <token>

## Query Parameters
- **client_id**: The ID of the client to verify.

## Response Codes
- **200**: Success
- **404**: Client Not Found

## Response Body
```json
{
  "client_id": "string",
  "status": "verified"
}
```

## Sample Request
```bash
curl -X POST \
  https://api.example.com/client/verify?client_id=12345 \
  -H "Authorization: Bearer <token>"
```

## Sample Response
```json
{
  "client_id": "12345",
  "status": "verified"
}
```