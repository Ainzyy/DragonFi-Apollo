# Institution Login

## Headers
- **Authorization**: Bearer <token>

## Query Parameters
- None

## Response Codes
- **200**: Success
- **401**: Unauthorized

## Response Body
```json
{
  "token": "string",
  "expires_in": 3600
}
```

## Sample Request
```bash
curl -X POST \
  https://api.example.com/auth/login \
  -H "Authorization: Bearer <token>"
```

## Sample Response
```json
{
  "token": "abc123",
  "expires_in": 3600
}
```