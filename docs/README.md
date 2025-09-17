# DragonFi Apollo API Documentation

## Overview
Welcome to the DragonFi Apollo API documentation. This guide provides detailed information about the available endpoints, their usage, and examples to help you integrate with our platform efficiently.

## Version History
- **v1.0.0**: Initial release with core functionalities.

## Authentication
### Institution Login
- **Endpoint**: `/auth/login`
- **Method**: POST
- **Description**: Authenticate an institution and retrieve an access token.

### Refresh Token
- **Endpoint**: `/auth/refresh`
- **Method**: POST
- **Description**: Refresh the access token using a valid refresh token.

## Client Management
### Create Client
- **Endpoint**: `/client/create`
- **Method**: POST
- **Description**: Create a new client in the system.

### Update Client Information
- **Endpoint**: `/client/update`
- **Method**: PUT
- **Description**: Update existing client details.

### Upload Client Photos
- **Endpoint**: `/client/upload`
- **Method**: POST
- **Description**: Upload client photos in JSON or form format.

### Verify Client
- **Endpoint**: `/client/verify`
- **Method**: POST
- **Description**: Verify client identity.

### Get Client Status
- **Endpoint**: `/client/status`
- **Method**: GET
- **Description**: Retrieve the status of a client.

### Get Client Information
- **Endpoint**: `/client/info`
- **Method**: GET
- **Description**: Fetch detailed information about a client.

### Get Client List
- **Endpoint**: `/client/list`
- **Method**: GET
- **Description**: Retrieve a list of all clients.

## Corporate Actions
### Get Corporate Actions Calendar
- **Endpoint**: `/corporate-actions/calendar`
- **Method**: GET
- **Description**: Fetch the corporate actions calendar.

## Lookups
### Get Lookups
- **Endpoint**: `/lookups`
- **Method**: GET
- **Description**: Retrieve lookup data.

### Get Countries
- **Endpoint**: `/lookups/countries`
- **Method**: GET
- **Description**: Fetch a list of countries.

### Get Regions
- **Endpoint**: `/lookups/regions`
- **Method**: GET
- **Description**: Retrieve regions data.

## Notes
- For detailed examples and request/response formats, refer to the Swagger JSON file provided.
