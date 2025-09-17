# API Endpoint Documentation

## Objectives
- Create a comprehensive API documentation using [Docsify](https://docsify.js.org/#/).
- Simplify API integration for third-party partners.
- Provide interactive and customizable documentation.

## Setup
1. Install [Docsify CLI](https://docsify.js.org/#/quickstart):
   ```bash
   npm install -g docsify-cli
   ```
2. Initialize the Docsify project:
   ```bash
   docsify init ./docs
   ```
3. Serve the documentation locally:
   ```bash
   docsify serve ./docs
   ```
4. Host the documentation via GitHub Pages.

## Plugins
Integrate the following Docsify plugins to enhance functionality:
- [Full text search](https://docsify.js.org/#/plugins?id=full-text-search): Enables search across all files.
- [External Script](https://docsify.js.org/#/plugins?id=external-script): Allows separation of scripts.
- [Zoom image](https://docsify.js.org/#/plugins?id=zoom-image): Makes images zoomable.
- [Copy to Clipboard](https://docsify.js.org/#/plugins?id=copy-to-clipboard): Simplifies copying code blocks.
- [Tabs](https://docsify.js.org/#/plugins?id=tabs): Useful for displaying options.

## Additional Features
- **Theme Selection**: Dark Mode (default) and Light Mode.
- **Custom Color Palette**: Align with branding.
- **Interactive Cover Page**: Customizable and engaging.

## Contents
> **Note**: Content structure can be updated as needed.

1. **Version History/Change Logs**
2. **Overview**
3. **Authenticate Section**
   - Institution Login
   - Refresh Token
4. **Client Section**
   - Create Client
   - Update Client Information
   - Upload Client Photos
     - JSON
     - Form
   - Verify Client
   - Get Client Status
   - Get Client Information
   - Get Client List
5. **Corporate Actions Section**
   - Get Corporate Actions Calendar
6. **Lookups Section**
   - Get Lookups
   - Get Countries
   - Get Regions
   - Get Provinces
   - Get Cities
   - Get Towns
   - Get Sectors and Industries
   - Get Sector by ID
   - Get Industry by ID
7. **Market Data Section**
   - Get Instruments
   - Get All Instruments
   - Get Popular Stocks
   - Get Snapshots
   - Get Market Status
   - Get Market Schedule
   - Get Lines
   - Get Bars
   - Get News
   - Get Tick Sizes
   - Get Prices
   - Get Market Movers
   - Get Securities Dividend History
   - Get Disclosures
8. **Money Section**
   - Get Banks List
   - Deposit
   - Withdraw
   - Get Transfers
   - Get Transfer Detail
   - Get Partner Detail
   - Settlement
9. **Order Data Section**
   - Get Order History
   - Create Order
   - Replace Order
   - Cancel Order
   - Calculate Investment Fees
10. **Reports Section**
    - Get Trading Summary
11. **Transactions Section**
    - Get Transaction History

## Plan
1. Create an initial outline.
2. Update with detailed documentation for each API.

## Swagger Integration
If available, provide the Swagger JSON file for the API. This can be used to auto-generate parts of the documentation or for reference.
