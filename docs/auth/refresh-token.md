# Refresh Token

## Headers
- **Authorization**: Bearer <refresh_token>

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
  https://api.example.com/auth/refresh \
  -H "Authorization: Bearer <refresh_token>"
```

## Sample Response
```json
{
  "token": "abc123",
  "expires_in": 3600
}
```