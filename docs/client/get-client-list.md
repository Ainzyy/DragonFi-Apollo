# Get Client List

## Headers
- **Authorization**: Bearer <token>

## Query Parameters
- None

## Response Codes
- **200**: Success

## Response Body
```json
[
  {
    "client_id": "string",
    "name": "string",
    "email": "string"
  }
]
```

## Sample Request
```bash
curl -X GET \
  https://api.example.com/client/list \
  -H "Authorization: Bearer <token>"
```

## Sample Response
```json
[
  {
    "client_id": "12345",
    "name": "John Doe",
    "email": "john.doe@example.com"
  },
  {
    "client_id": "67890",
    "name": "Jane Smith",
    "email": "jane.smith@example.com"
  }
]
```