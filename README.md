# Microsoft Dynamics NAV (navision)

API collection for Microsoft Dynamics NAV (formerly Navision), an enterprise resource planning (ERP) solution for small and medium-sized businesses. Dynamics NAV has evolved into Dynamics 365 Business Central, which provides modern REST, OData, and SOAP web services for business data integration.

**APIs.json:** [https://dynamics.microsoft.com/nav-overview/](https://dynamics.microsoft.com/nav-overview/)

## Tags

- Business Management
- Dynamics NAV
- ERP
- Finance
- Inventory
- Microsoft
- Navision

## Timestamps

- **Created:** 2024-01-20
- **Modified:** 2026-05-19

## APIs

### Dynamics NAV Web Services API

SOAP and OData web services for interacting with Dynamics NAV business data. Supports publishing pages, codeunits, and queries as web services for external system integration.

- **Human URL:** [https://learn.microsoft.com/en-us/dynamics-nav/web-services](https://learn.microsoft.com/en-us/dynamics-nav/web-services)
- **Base URL:** `https://{server}:{port}/{instance}/api/{version}`

#### Tags

- Enterprise Resource Planning
- OData
- SOAP
- Web Services

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics-nav/microsoft-dynamics-nav-web-services-overview)
- [OpenAPI](https://example.com/openapi/nav-webservices.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/dynamics-nav/web-services-authentication)
- [Getting Started](https://learn.microsoft.com/en-us/dynamics-nav/walkthrough--creating-and-interacting-with-a-page-web-service--odata-)
- [Postman Collection](collections/admin-center-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/admin-center-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/automation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/automation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/business-central-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/business-central-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynamics NAV OData API

OData web services for querying and manipulating NAV business entities. Supports both OData v3 and v4 protocols for reading data and writing back to the Dynamics NAV database through exposed pages and queries.

- **Human URL:** [https://learn.microsoft.com/en-us/dynamics-nav/odata-web-services](https://learn.microsoft.com/en-us/dynamics-nav/odata-web-services)
- **Base URL:** `https://{server}:{port}/{instance}/OData/Company('{company}')`

#### Tags

- Business Data
- Data Integration
- OData
- Queries

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics-nav/odata-web-services)
- [OpenAPI](https://example.com/openapi/nav-odata.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://learn.microsoft.com/en-us/dynamics-nav/walkthrough--creating-and-interacting-with-a-page-web-service--odata-)
- [Postman Collection](collections/admin-center-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/admin-center-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/automation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/automation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/business-central-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/business-central-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynamics NAV SOAP Web Services

SOAP-based web services for legacy integrations and business logic operations in Dynamics NAV. Exposes pages and codeunits with built-in CRUD operations and supports extension codeunits for custom operations.

- **Human URL:** [https://learn.microsoft.com/en-us/dynamics-nav/soap-web-services](https://learn.microsoft.com/en-us/dynamics-nav/soap-web-services)
- **Base URL:** `https://{server}:{port}/{instance}/WS/{company}/`

#### Tags

- Business Logic
- Codeunits
- Legacy Integration
- SOAP

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics-nav/soap-web-service-uris)
- [API Reference](https://learn.microsoft.com/en-us/dynamics-nav/walkthrough--creating-and-using-a-codeunit-web-service--soap-)
- [Getting Started](https://learn.microsoft.com/en-us/dynamics-nav/walkthrough--registering-and-using-a-page-web-service--soap-)
- [Postman Collection](collections/admin-center-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/admin-center-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/automation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/automation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/business-central-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/business-central-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Business Central API v2.0

Modern RESTful API for Dynamics 365 Business Central, the cloud evolution of Dynamics NAV. Provides a comprehensive set of endpoints for managing customers, items, accounts, sales orders, and other business entities.

- **Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/)
- **Base URL:** `https://api.businesscentral.dynamics.com/v2.0/{environment}/api/v2.0`

#### Tags

- Business Central
- Business Data
- Cloud ERP
- Connect Apps
- REST API

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/)
- [API Reference](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/endpoints-apis-for-dynamics)
- [Authentication](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/authenticate-web-services-using-oauth)
- [Getting Started](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-develop-connect-apps)
- [Changelog](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/whatsnew/overview)
- [OpenAPI](openapi/business-central-api-v2.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/business-central-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/business-central-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Business Central Administration Center API

REST API for programmatic administration of Business Central environments. Enables querying and managing production and sandbox environments, setting up notifications, and viewing tenant telemetry.

- **Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/administration-center-api](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/administration-center-api)
- **Base URL:** `https://api.businesscentral.dynamics.com/admin/v2.28`

#### Tags

- Administration
- Cloud ERP
- Environment Management
- Tenant Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/administration-center-api)
- [Authentication](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/automation-apis-using-s2s-authentication)
- [Getting Started](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/)
- [OpenAPI](openapi/admin-center-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/admin-center-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/admin-center-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Business Central Automation API

API for automating company setup and tenant management in Business Central. Supports creating companies, installing extensions, assigning permissions, and applying RapidStart packages programmatically.

- **Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/itpro-introduction-to-automation-apis](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/itpro-introduction-to-automation-apis)
- **Base URL:** `https://api.businesscentral.dynamics.com/v2.0/{environment}/api/microsoft/automation/v2.0`

#### Tags

- Automation
- Extension Management
- Tenant Management
- User Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/itpro-introduction-to-automation-apis)
- [Authentication](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/automation-apis-using-s2s-authentication)
- [Getting Started](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-develop-connect-apps)
- [OpenAPI](openapi/automation-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/automation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/automation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Business Central REST API Web Services

RESTful web services layer for Business Central that provides the preferred integration method. Includes built-in APIs, custom API pages and queries, and supports both on-premises and cloud deployments.

- **Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/api-overview](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/api-overview)
- **Base URL:** `https://api.businesscentral.dynamics.com/v2.0/{environment}/api`

#### Tags

- Business Central
- Custom APIs
- Data Integration
- REST API
- Web Services

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/api-overview)
- [API Reference](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/endpoints-apis-for-dynamics)
- [Authentication](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/authenticate-web-services-using-oauth)
- [Getting Started](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-get-started)
- [Postman Collection](collections/admin-center-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/admin-center-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/automation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/automation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/business-central-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/business-central-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/showcase/microsoft-dynamics-navision)
- [Portal](https://dynamics.microsoft.com)
- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/)
- [Getting Started](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-get-started)
- [Authentication](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/users-credential-types)
- [Blog](https://www.microsoft.com/en-us/dynamics-365/blog/product/dynamics-365-business-central/)
- [Changelog](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/whatsnew/overview)
- [Support](https://support.microsoft.com/dynamics)
- [Sign Up](https://learn.microsoft.com/en-us/dynamics365/business-central/trial-signup)
- [Pricing](https://www.microsoft.com/en-us/dynamics-365/products/business-central/pricing)
- [Terms of Service](https://www.microsoft.com/en/dynamics-365/business-applications/legal)
- [Privacy Policy](https://privacy.microsoft.com)
- [Status Page](https://status.cloud.microsoft)
- [GitHub Organization](https://github.com/microsoft/BCApps)
- [GitHub Repository](https://github.com/christianbraeunlich/d365bc-api-postman)
- [Rate Limits](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/dynamics-rate-limits)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [SDK](https://github.com/niclas-timm/laravel-dynamics-365-business-central)
- [SDK](https://github.com/AgoraIO/agora-rest-client-go)
- [C L I](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-command-line-tools)
- [JSON Schema](json-schema/customer.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/vendor.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/item.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sales-order.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/purchase-order.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/business-central-v2-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/business-central-v2-vendor-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/business-central-v2-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/business-central-v2-sales-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/business-central-v2-purchase-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/admin-center-environment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/admin-center-environment-operation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/automation-extension-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/automation-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/automation-automation-company-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/business-central-v2-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/admin-center-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/automation-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/navision-vocabulary.yaml)
- [Rules](rules/navision-spectral-rules.yml)
- [Capabilities](capabilities/business-operations.yaml)
- [Capabilities](capabilities/platform-administration.yaml)
- [Capabilities](capabilities/shared/business-central-v2.yaml)
- [Capabilities](capabilities/shared/admin-center.yaml)
- [Capabilities](capabilities/shared/automation.yaml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
