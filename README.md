# Google Sheets (google-sheets)
API for reading, writing, and formatting data in Google Sheets.

**URL:** [Visit APIs.json URL](https://developers.google.com/sheets/api)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Google Workspace, Productivity, Spreadsheets

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Google Sheets API v4
The Google Sheets API lets you read, write, and format Google Sheets data.

**Human URL:** [https://developers.google.com/sheets/api](https://developers.google.com/sheets/api)

#### Tags:

 - Collaboration, Data, Google, Productivity, Spreadsheets

#### Properties

- [Documentation](https://developers.google.com/sheets/api/reference/rest)
- [OpenAPI](openapi/google-sheets-openapi.yml)
- [Authentication](https://developers.google.com/sheets/api/guides/authorizing)
- [Quickstart](https://developers.google.com/sheets/api/quickstart/python)
- [GettingStarted](https://developers.google.com/workspace/sheets/api/guides/concepts)
- [APIReference](https://developers.google.com/workspace/sheets/api/reference/rest)
- [SDK](https://developers.google.com/workspace/sheets/api/guides/libraries)
- [ChangeLog](https://developers.google.com/workspace/sheets/release-notes)
- [CodeExamples](https://developers.google.com/workspace/sheets/api/samples)
- [RateLimits](https://developers.google.com/workspace/sheets/api/limits)
- [Errors](https://developers.google.com/workspace/sheets/api/troubleshoot-api-errors)
- [JSONSchema](json-schema/google-sheets-spreadsheet-schema.json)
- [JSONLD](json-ld/google-sheets-context.jsonld)

### Google Apps Script Spreadsheet Service
The built-in Google Apps Script Spreadsheet Service allows creation, access, and modification of Google Sheets files directly from Apps Script with performance bundling and numerous classes for formatting, data sources, structure, and content.

**Human URL:** [https://developers.google.com/apps-script/reference/spreadsheet](https://developers.google.com/apps-script/reference/spreadsheet)

#### Tags:

 - Apps Script, Automation, Google, Scripting, Spreadsheets

#### Properties

- [Documentation](https://developers.google.com/apps-script/reference/spreadsheet)
- [GettingStarted](https://developers.google.com/apps-script)
- [APIReference](https://developers.google.com/apps-script/reference)
- [ReleaseNotes](https://developers.google.com/apps-script/release-notes)

## Common Properties

- [Portal](https://developers.google.com/workspace/sheets/api)
- [Documentation](https://developers.google.com/workspace/sheets/api/reference/rest)
- [Blog](https://workspace.google.com/blog/developers-practitioners)
- [GitHubOrganization](https://github.com/googleapis)
- [Support](https://developers.google.com/sheets/api/support)
- [StatusPage](https://www.google.com/appsstatus/dashboard/)
- [TermsOfService](https://developers.google.com/terms)
- [PrivacyPolicy](https://policies.google.com/privacy)
- [SignUp](https://console.cloud.google.com/)
- [Login](https://console.cloud.google.com/)
- [StackOverflow](https://stackoverflow.com/questions/tagged/google-sheets-api)
- [YouTube](https://developers.google.com/workspace/sheets/api/videos)
- [GettingStarted](https://developers.google.com/workspace/sheets/api/guides/concepts)
- [Authentication](https://developers.google.com/sheets/api/guides/authorizing)
- [SDK](https://developers.google.com/workspace/sheets/api/guides/libraries)
- [ReleaseNotes](https://developers.google.com/workspace/sheets/release-notes)
- [Pricing](https://developers.google.com/workspace/sheets/api/limits)
- [RateLimits](https://developers.google.com/workspace/sheets/api/limits)

## Features

| Name | Description |
|------|-------------|
| Spreadsheet Management | Create, read, update, and delete spreadsheets programmatically with full control over properties and metadata. |
| Cell Value Operations | Read and write individual cell values, ranges, and batch operations across multiple ranges. |
| Formatting | Apply rich formatting to cells including fonts, colors, borders, alignment, and number formats. |
| Sheet Management | Add, remove, copy, and configure individual sheets within a spreadsheet. |
| Developer Metadata | Attach custom metadata to spreadsheets, sheets, rows, and columns for application-specific data. |
| Data Validation | Set validation rules on cells to enforce data quality and consistency. |
| Conditional Formatting | Apply conditional formatting rules based on cell values and formulas. |
| Charts and Graphs | Create and manage embedded charts within spreadsheets. |
| Named Ranges | Define and manage named ranges for easier formula references. |
| Batch Operations | Execute multiple read and write operations in a single API call for efficiency. |

## Use Cases

| Name | Description |
|------|-------------|
| Data Collection and Reporting | Collect data from various sources and generate automated reports in Google Sheets. |
| Database Backend | Use Google Sheets as a lightweight database for web applications and prototypes. |
| Workflow Automation | Automate data entry, processing, and distribution workflows using the API. |
| Data Integration | Synchronize data between Google Sheets and other business applications. |
| Dashboard Creation | Build interactive dashboards and visualizations from spreadsheet data. |

## Integrations

| Name | Description |
|------|-------------|
| Google Workspace | Deep integration with Google Docs, Slides, Forms, and other Workspace applications. |
| Google Apps Script | Extend Sheets functionality with custom functions, menus, and automation scripts. |
| Google Cloud Platform | Connect to BigQuery, Cloud Functions, and other GCP services for advanced data processing. |
| Zapier | Connect Google Sheets to thousands of apps through Zapier automation workflows. |
| Slack | Send notifications and updates to Slack channels based on spreadsheet changes. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Google Sheets API](openapi/google-sheets-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Google Sheets API](capabilities/shared/google-sheets.yaml) — 13 operations for spreadsheet data management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Spreadsheet Data Management](capabilities/spreadsheet-data-management.yaml) | Google Sheets | 13 | Data Analyst / Developer |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
