# Microsoft Dynamics NAV (navision)

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/navision/refs/heads/main/apis.yml)

API collection for Microsoft Dynamics NAV (formerly Navision), an enterprise resource planning (ERP) solution for small and medium-sized businesses. Dynamics NAV has evolved into Dynamics 365 Business Central, which provides modern REST, OData, and SOAP web services for business data integration.

## Timestamps

- **Created:** 2024-01-20
- **Modified:** 2026-04-18

## APIs

### Dynamics NAV Web Services API
SOAP and OData web services for interacting with Dynamics NAV business data. Supports publishing pages, codeunits, and queries as web services for external system integration.

**Human URL:** [https://learn.microsoft.com/en-us/dynamics-nav/web-services](https://learn.microsoft.com/en-us/dynamics-nav/web-services)

#### Tags:

 - Enterprise Resource Planning, OData, SOAP, Web Services

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics-nav/microsoft-dynamics-nav-web-services-overview)
- [OpenAPI](https://example.com/openapi/nav-webservices.yaml)
- [Authentication](https://learn.microsoft.com/en-us/dynamics-nav/web-services-authentication)
- [GettingStarted](https://learn.microsoft.com/en-us/dynamics-nav/walkthrough--creating-and-interacting-with-a-page-web-service--odata-)

### Dynamics NAV OData API
OData web services for querying and manipulating NAV business entities. Supports both OData v3 and v4 protocols for reading data and writing back to the Dynamics NAV database through exposed pages and queries.

**Human URL:** [https://learn.microsoft.com/en-us/dynamics-nav/odata-web-services](https://learn.microsoft.com/en-us/dynamics-nav/odata-web-services)

#### Tags:

 - Business Data, Data Integration, OData, Queries

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics-nav/odata-web-services)
- [OpenAPI](https://example.com/openapi/nav-odata.yaml)
- [GettingStarted](https://learn.microsoft.com/en-us/dynamics-nav/walkthrough--creating-and-interacting-with-a-page-web-service--odata-)

### Dynamics NAV SOAP Web Services
SOAP-based web services for legacy integrations and business logic operations in Dynamics NAV. Exposes pages and codeunits with built-in CRUD operations and supports extension codeunits for custom operations.

**Human URL:** [https://learn.microsoft.com/en-us/dynamics-nav/soap-web-services](https://learn.microsoft.com/en-us/dynamics-nav/soap-web-services)

#### Tags:

 - Business Logic, Codeunits, Legacy Integration, SOAP

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics-nav/soap-web-service-uris)
- [APIReference](https://learn.microsoft.com/en-us/dynamics-nav/walkthrough--creating-and-using-a-codeunit-web-service--soap-)
- [GettingStarted](https://learn.microsoft.com/en-us/dynamics-nav/walkthrough--registering-and-using-a-page-web-service--soap-)

### Business Central API v2.0
Modern RESTful API for Dynamics 365 Business Central, the cloud evolution of Dynamics NAV. Provides a comprehensive set of endpoints for managing customers, items, accounts, sales orders, and other business entities.

**Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/)

#### Tags:

 - Business Central, Business Data, Cloud ERP, Connect Apps, REST API

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/)
- [APIReference](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/endpoints-apis-for-dynamics)
- [Authentication](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/authenticate-web-services-using-oauth)
- [GettingStarted](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-develop-connect-apps)
- [ChangeLog](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/whatsnew/overview)
- [OpenAPI](openapi/business-central-api-v2.yml)

### Business Central Administration Center API
REST API for programmatic administration of Business Central environments. Enables querying and managing production and sandbox environments, setting up notifications, and viewing tenant telemetry.

**Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/administration-center-api](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/administration-center-api)

#### Tags:

 - Administration, Cloud ERP, Environment Management, Tenant Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/administration-center-api)
- [Authentication](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/automation-apis-using-s2s-authentication)
- [GettingStarted](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/)
- [OpenAPI](openapi/admin-center-api.yml)

### Business Central Automation API
API for automating company setup and tenant management in Business Central. Supports creating companies, installing extensions, assigning permissions, and applying RapidStart packages programmatically.

**Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/itpro-introduction-to-automation-apis](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/itpro-introduction-to-automation-apis)

#### Tags:

 - Automation, Extension Management, Tenant Management, User Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/itpro-introduction-to-automation-apis)
- [Authentication](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/automation-apis-using-s2s-authentication)
- [GettingStarted](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-develop-connect-apps)
- [OpenAPI](openapi/automation-api.yml)

### Business Central REST API Web Services
RESTful web services layer for Business Central that provides the preferred integration method. Includes built-in APIs, custom API pages and queries, and supports both on-premises and cloud deployments.

**Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/api-overview](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/api-overview)

#### Tags:

 - Business Central, Custom APIs, Data Integration, REST API, Web Services

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/api-overview)
- [APIReference](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/endpoints-apis-for-dynamics)
- [Authentication](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/authenticate-web-services-using-oauth)
- [GettingStarted](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-get-started)

## Common Properties

- [Portal](https://dynamics.microsoft.com)
- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/)
- [GettingStarted](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-get-started)
- [Authentication](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/users-credential-types)
- [Blog](https://www.microsoft.com/en-us/dynamics-365/blog/product/dynamics-365-business-central/)
- [ChangeLog](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/whatsnew/overview)
- [Support](https://support.microsoft.com/dynamics)
- [SignUp](https://learn.microsoft.com/en-us/dynamics365/business-central/trial-signup)
- [Pricing](https://www.microsoft.com/en-us/dynamics-365/products/business-central/pricing)
- [TermsOfService](https://www.microsoft.com/en/dynamics-365/business-applications/legal)
- [PrivacyPolicy](https://privacy.microsoft.com)
- [StatusPage](https://status.cloud.microsoft)
- [GitHubOrganization](https://github.com/microsoft/BCApps)
- [RateLimits](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/dynamics-rate-limits)
- [SDK - Laravel](https://github.com/niclas-timm/laravel-dynamics-365-business-central)
- [CLI - AL Language](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-command-line-tools)

## OpenAPI

- [Business Central API v2.0 OpenAPI](openapi/business-central-api-v2.yml)
- [Administration Center API OpenAPI](openapi/admin-center-api.yml)
- [Automation API OpenAPI](openapi/automation-api.yml)

## JSON Schema

| Schema | File |
|---|---|
| Customer Schema | [json-schema/customer.json](json-schema/customer.json) |
| Vendor Schema | [json-schema/vendor.json](json-schema/vendor.json) |
| Item Schema | [json-schema/item.json](json-schema/item.json) |
| Sales Order Schema | [json-schema/sales-order.json](json-schema/sales-order.json) |
| Purchase Order Schema | [json-schema/purchase-order.json](json-schema/purchase-order.json) |
| BC v2 Customer Schema | [json-schema/business-central-v2-customer-schema.json](json-schema/business-central-v2-customer-schema.json) |
| BC v2 Vendor Schema | [json-schema/business-central-v2-vendor-schema.json](json-schema/business-central-v2-vendor-schema.json) |
| Admin Center Environment Schema | [json-schema/admin-center-environment-schema.json](json-schema/admin-center-environment-schema.json) |
| Automation Extension Schema | [json-schema/automation-extension-schema.json](json-schema/automation-extension-schema.json) |
| Automation User Schema | [json-schema/automation-user-schema.json](json-schema/automation-user-schema.json) |

## JSON-LD

- [JSON-LD Context](json-ld/context.jsonld)
- [Business Central v2 Context](json-ld/business-central-v2-context.jsonld)
- [Admin Center Context](json-ld/admin-center-context.jsonld)
- [Automation Context](json-ld/automation-context.jsonld)

## Vocabulary

- [Navision Vocabulary](vocabulary/navision-vocabulary.yaml)

## Rules

- [Spectral Rules](rules/navision-spectral-rules.yml)

## Capabilities

| Capability | Type | File |
|---|---|---|
| Business Operations | Workflow | [capabilities/business-operations.yaml](capabilities/business-operations.yaml) |
| Platform Administration | Workflow | [capabilities/platform-administration.yaml](capabilities/platform-administration.yaml) |
| Business Central v2 | Shared | [capabilities/shared/business-central-v2.yaml](capabilities/shared/business-central-v2.yaml) |
| Admin Center | Shared | [capabilities/shared/admin-center.yaml](capabilities/shared/admin-center.yaml) |
| Automation | Shared | [capabilities/shared/automation.yaml](capabilities/shared/automation.yaml) |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
