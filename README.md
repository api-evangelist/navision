# Microsoft Dynamics NAV (navision)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
