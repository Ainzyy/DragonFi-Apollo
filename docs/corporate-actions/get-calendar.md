# Get Corporate Actions Calendar

## Headers
- **Authorization**: Bearer <token>

## Query Parameters
- **date**: The date for which to retrieve the calendar (optional).

## Response Codes
- **200**: Success

## Response Body
```json
[
  {
    "action_id": "string",
    "date": "string",
    "description": "string"
  }
]
```

## Sample Request
```bash
curl -X GET \
  https://api.example.com/corporate-actions/calendar?date=2025-09-17 \
  -H "Authorization: Bearer <token>"
```

## Sample Response
```json
[
  {
    "action_id": "12345",
    "date": "2025-09-17",
    "description": "Dividend Payment"
  }
]
```