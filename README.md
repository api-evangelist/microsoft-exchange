# Microsoft Exchange (microsoft-exchange)

A comprehensive API collection for Microsoft Exchange Server and Exchange Online, providing programmatic access to email, calendars, contacts, and other mailbox resources through Microsoft Graph, EWS, PowerShell, Autodiscover, and the Exchange Online Admin API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Calendar
- Collaboration
- Contacts
- Email
- Enterprise

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Microsoft Graph Mail API

Access Exchange Online mailboxes through the Microsoft Graph API, providing modern REST endpoints for reading, sending, and managing email messages, drafts, attachments, and mail folders.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview](https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Email
- Mail
- Messaging
- Microsoft Graph
- REST

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview)
- [OpenAPI](openapi/microsoft-exchange-graph-mail-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-exchange-graph-mail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-mail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Getting Started](https://developer.microsoft.com/en-us/graph/quick-start)
- [S D Ks](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)

### Microsoft Graph Calendar API

Manage calendar events, meetings, and scheduling for Exchange Online users. Provides endpoints for creating, updating, and deleting events, managing attendees, and handling recurring meetings.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/calendar](https://learn.microsoft.com/en-us/graph/api/resources/calendar)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Calendar
- Events
- Meetings
- Microsoft Graph
- Scheduling

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/calendar)
- [OpenAPI](openapi/microsoft-exchange-graph-calendar-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-exchange-graph-calendar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-calendar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Getting Started](https://developer.microsoft.com/en-us/graph/quick-start)
- [S D Ks](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)

### Microsoft Graph Contacts API

Manage Outlook personal contacts and contact folders for Exchange Online users. Supports creating, reading, updating, and deleting contacts, organizing them into folders, and assigning categories.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/outlook-contacts-concept-overview](https://learn.microsoft.com/en-us/graph/outlook-contacts-concept-overview)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Address Book
- Contacts
- Microsoft Graph
- Outlook
- People

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/outlook-contacts-concept-overview)
- [Reference](https://learn.microsoft.com/en-us/graph/api/resources/contact?view=graph-rest-1.0)
- [OpenAPI](openapi/microsoft-exchange-graph-contacts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-exchange-graph-contacts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-contacts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [S D Ks](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)

### Microsoft Graph People API

Retrieve people most relevant to a user based on communication and collaboration patterns, business relationships, and contacts. Useful for people-picking scenarios and social intelligence features.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/people-insights-overview](https://learn.microsoft.com/en-us/graph/people-insights-overview)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Collaboration
- Contacts
- Microsoft Graph
- People
- Social Intelligence

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/people-insights-overview)
- [Reference](https://learn.microsoft.com/en-us/graph/api/user-list-people?view=graph-rest-1.0)
- [OpenAPI](openapi/microsoft-exchange-graph-people-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-exchange-graph-people.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-people.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [S D Ks](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)

### Exchange Web Services (EWS)

Legacy SOAP-based API for Exchange Server providing comprehensive access to mailbox data and operations. Planned for deprecation in Exchange Online in October 2026, with Microsoft Graph recommended for new development.

- **Human URL:** [https://learn.microsoft.com/en-us/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange](https://learn.microsoft.com/en-us/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange)
- **Base URL:** `https://outlook.office365.com/EWS/Exchange.asmx`

#### Tags

- Exchange Server
- Legacy
- Mailbox
- SOAP
- Web Services

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/exchange/client-developer/web-service-reference/web-services-reference-for-exchange)
- [W S D L](https://outlook.office365.com/EWS/Exchange.asmx?wsdl)
- [SDK](https://github.com/officedev/ews-managed-api)
- [Reference](https://learn.microsoft.com/en-us/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange)
- [Getting Started](https://learn.microsoft.com/en-us/exchange/client-developer/exchange-server-development)
- [Postman Collection](collections/microsoft-exchange-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-calendar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-calendar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-contacts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-contacts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-import-export.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-import-export.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-mail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-mail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-people.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-people.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Exchange Online PowerShell API

PowerShell module for managing Exchange Online through REST-based cmdlets. Provides the complete Exchange management surface for administrative tasks including mailbox management, mail flow rules, and organization configuration.

- **Human URL:** [https://learn.microsoft.com/en-us/powershell/exchange/exchange-online-powershell](https://learn.microsoft.com/en-us/powershell/exchange/exchange-online-powershell)
- **Base URL:** `https://outlook.office365.com/powershell-liveid/`

#### Tags

- Administration
- Automation
- Exchange Online
- Management
- PowerShell

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/powershell/exchange/exchange-online-powershell-v2)
- [Installation  Guide](https://learn.microsoft.com/en-us/powershell/exchange/exchange-online-powershell-v2#install-and-maintain-the-exchange-online-powershell-module)
- [Authentication](https://learn.microsoft.com/en-us/powershell/exchange/connect-to-exchange-online-powershell)
- [Reference](https://learn.microsoft.com/en-us/powershell/exchange/exchange-online-powershell)
- [Postman Collection](collections/microsoft-exchange-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-calendar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-calendar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-contacts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-contacts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-import-export.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-import-export.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-mail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-mail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-people.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-people.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Exchange Autodiscover API

Service that enables client applications to automatically configure themselves for Exchange connectivity using minimal user input. Supports SOAP and POX protocols for discovering EWS endpoint URLs and other Exchange service settings.

- **Human URL:** [https://learn.microsoft.com/en-us/exchange/client-developer/exchange-web-services/autodiscover-for-exchange](https://learn.microsoft.com/en-us/exchange/client-developer/exchange-web-services/autodiscover-for-exchange)
- **Base URL:** `https://outlook.office365.com/autodiscover/autodiscover.svc`

#### Tags

- Autodiscover
- Configuration
- Exchange Server
- Service Discovery
- SOAP

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/exchange/client-developer/exchange-web-services/autodiscover-for-exchange)
- [Reference](https://learn.microsoft.com/en-us/exchange/client-developer/web-service-reference/soap-autodiscover-web-service-reference-for-exchange)
- [SDK](https://github.com/officedev/ews-managed-api)
- [Postman Collection](collections/microsoft-exchange-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-calendar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-calendar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-contacts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-contacts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-import-export.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-import-export.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-mail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-mail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-exchange-graph-people.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-people.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Exchange Online Admin API

REST-based administrative API that provides cmdlet-style endpoints for Exchange Online management tasks previously available through EWS. Supports organization configuration, mailbox folder permissions, distribution group membership, and delegation management.

- **Human URL:** [https://learn.microsoft.com/en-us/exchange/reference/admin-api-overview](https://learn.microsoft.com/en-us/exchange/reference/admin-api-overview)
- **Base URL:** `https://outlook.office365.com/adminapi/v2.0`

#### Tags

- Administration
- Exchange Online
- Management
- Permissions
- REST

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/exchange/reference/admin-api-overview)
- [OpenAPI](openapi/microsoft-exchange-admin-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-exchange-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://learn.microsoft.com/en-us/exchange/reference/admin-api-get-started)
- [Authentication](https://learn.microsoft.com/en-us/exchange/reference/admin-api-authentication)

### Microsoft Graph Mailbox Import Export API

APIs for discovering, importing, and exporting content from Exchange Online mailboxes in full fidelity. Enables mailbox migration scenarios and content copying as a replacement for EWS-based approaches.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/mailbox-import-export-concept-overview](https://learn.microsoft.com/en-us/graph/mailbox-import-export-concept-overview)
- **Base URL:** `https://graph.microsoft.com/beta`

#### Tags

- Export
- Import
- Mailbox
- Microsoft Graph
- Migration

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/mailbox-import-export-concept-overview)
- [OpenAPI](openapi/microsoft-exchange-graph-import-export-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-exchange-graph-import-export.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-exchange-graph-import-export.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://learn.microsoft.com/en-us/graph/api/resources/mailbox-import-export-api-overview?view=graph-rest-beta)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [S D Ks](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://developer.microsoft.com/en-us/graph)
- [Documentation](https://learn.microsoft.com/en-us/exchange/client-developer/exchange-server-development)
- [Getting Started](https://developer.microsoft.com/en-us/graph/quick-start)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Blog](https://devblogs.microsoft.com/microsoft365dev/tag/exchange/)
- [Status Page](https://status.office365.com/)
- [Support](https://support.microsoft.com/en-us/office)
- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub Organization](https://github.com/OfficeDev)
- [Community](https://techcommunity.microsoft.com/category/exchange)
- [Website](https://www.microsoft.com/en-us/microsoft-365/exchange/email)
- [Login](https://admin.exchange.microsoft.com)
- [Sign Up](https://signup.azure.com/)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)
- [S D Ks](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Pricing](https://www.microsoft.com/en-us/microsoft-365/exchange/compare-microsoft-exchange-online-plans)
- [Graph  Explorer](https://developer.microsoft.com/en-us/graph/graph-explorer)
- [J S O N- L D  Context](json-ld/microsoft-exchange-context.jsonld)
- [J S O N  Schema](json-schema/microsoft-exchange-message-schema.json)
- [J S O N  Schema](json-schema/microsoft-exchange-event-schema.json)
- [J S O N  Schema](json-schema/microsoft-exchange-contact-schema.json)
- [J S O N  Schema](json-schema/microsoft-exchange-calendar-schema.json)
- [J S O N  Schema](json-schema/microsoft-exchange-mail-folder-schema.json)
- [J S O N  Schema](json-schema/microsoft-exchange-person-schema.json)
- [Integrations](https://www.microsoft.com/en-us/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
