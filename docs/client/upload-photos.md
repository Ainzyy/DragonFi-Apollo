# Upload Client Photos

## Headers
- **Authorization**: Bearer <token>
- **Content-Type**: multipart/form-data

## Query Parameters
- **client_id**: The ID of the client.

## Response Codes
- **200**: Success
- **400**: Bad Request

## Response Body
```json
{
  "client_id": "string",
  "status": "photos_uploaded"
}
```

## Sample Request
```bash
curl -X POST \
  https://api.example.com/client/upload?client_id=12345 \
  -H "Authorization: Bearer <token>" \
  -F "photo=@photo.jpg"
```

## Sample Response
```json
{
  "client_id": "12345",
  "status": "photos_uploaded"
}
```