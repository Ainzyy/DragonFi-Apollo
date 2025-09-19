# Create Client

## Headers
- **Authorization**: Bearer <token>

## Query Parameters
- None

## Response Codes
- **201**: Created
- **400**: Bad Request

## Response Body
```json
{
  "client_id": "string",
  "status": "created"
}
```

## Sample Request
```bash
curl -X POST \
  https://api.example.com/client/create \
  -H "Authorization: Bearer <token>" \
  -d '{"name": "John Doe"}'
```

## Sample Response
```json
{
  "client_id": "12345",
  "status": "created"
}
```