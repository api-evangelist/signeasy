# Signeasy (signeasy)

Signeasy is an eSignature and intelligent contract management platform used by tens of thousands of businesses to sign, send, and manage documents. The Signeasy API (v3) is a RESTful eSignature API that lets developers send documents for signature (envelopes), embed signing and sending flows directly inside their own web and mobile apps via iframes, manage reusable templates with merge fields, upload original documents, and receive real-time signature lifecycle notifications through webhooks. All endpoints are served from `https://api.signeasy.com/v3` and authenticated with OAuth 2.0 Bearer access tokens (sandbox and live).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/signeasy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/signeasy/refs/heads/main/apis.yml)

## Tags

- eSignature
- Electronic Signature
- Documents
- Contract Management
- Embedded Signing
- Templates
- Webhooks

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Signeasy Envelopes API

Create and send envelopes - signature requests composed of one or many original documents and templates, sent to up to 45 signers. Retrieve the envelope (pending file) object and its status, download the signed PDF, and cancel or void a signature request.

- **Human URL:** [https://docs.signeasy.com/reference/create-an-envelope-rs-originals-templates](https://docs.signeasy.com/reference/create-an-envelope-rs-originals-templates)
- **Base URL:** `https://api.signeasy.com/v3`

#### Tags

- Envelopes
- Signature Requests
- eSignature

#### Properties

- [Documentation](https://docs.signeasy.com/docs/envelopes)
- [API Reference](https://docs.signeasy.com/reference/create-an-envelope-rs-originals-templates)
- [OpenAPI](openapi/signeasy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/signeasy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/signeasy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Signeasy Originals API

Upload original (master) documents that can be reused to send out signature requests. Originals are the raw source files that envelopes and templates are built from.

- **Human URL:** [https://docs.signeasy.com/reference/create-an-original-document](https://docs.signeasy.com/reference/create-an-original-document)
- **Base URL:** `https://api.signeasy.com/v3`

#### Tags

- Documents
- Originals
- Upload

#### Properties

- [Documentation](https://docs.signeasy.com/docs/original-documents-imports)
- [API Reference](https://docs.signeasy.com/reference/create-an-original-document)
- [OpenAPI](openapi/signeasy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/signeasy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/signeasy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Signeasy Templates API

Manage reusable templates - documents with predefined roles and merge fields that automate signature requests. Update a template and fetch an embedded template-creation URL so users can build or edit templates inside your own app in an iframe.

- **Human URL:** [https://docs.signeasy.com/reference/fetch-embedded-template-create-url](https://docs.signeasy.com/reference/fetch-embedded-template-create-url)
- **Base URL:** `https://api.signeasy.com/v3`

#### Tags

- Templates
- Merge Fields
- Automation

#### Properties

- [Documentation](https://docs.signeasy.com/docs/templates)
- [API Reference](https://docs.signeasy.com/reference/fetch-embedded-template-create-url)
- [OpenAPI](openapi/signeasy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/signeasy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/signeasy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Signeasy Embedded Signing API

Embed signing and sending directly in your web or mobile app. Create embedded signature requests (no Signeasy emails sent), generate per-recipient signing URLs to load in an iframe or pop-up, fetch an embedded sending URL to prepare and send documents, and cancel embedded signature requests.

- **Human URL:** [https://docs.signeasy.com/docs/embedded-signing](https://docs.signeasy.com/docs/embedded-signing)
- **Base URL:** `https://api.signeasy.com/v3`

#### Tags

- Embedded Signing
- Embedded Sending
- iFrame

#### Properties

- [Documentation](https://docs.signeasy.com/docs/embedded-signing)
- [API Reference](https://docs.signeasy.com/reference/fetch-rs-sending-url)
- [OpenAPI](openapi/signeasy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/signeasy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/signeasy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Signeasy Webhooks API

Subscribe an HTTP endpoint to signature-request lifecycle events - rs.initiated, rs.link_sent, rs.viewed, rs.signed, rs.completed, rs.declined, rs.reminded, rs.expired, rs.voided, and document.signed. Signeasy POSTs an asynchronous payload (with event_user and metadata token) to your URL, retrying failures with exponential backoff over 24 hours. Subscriptions are configured in the developer portal.

- **Human URL:** [https://docs.signeasy.com/docs/webhooks](https://docs.signeasy.com/docs/webhooks)
- **Base URL:** `https://api.signeasy.com/v3`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.signeasy.com/docs/webhooks)
- [API Reference](https://docs.signeasy.com/docs/webhooks)
- [OpenAPI](openapi/signeasy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Signeasy Users API

Fetch the authenticated user's details via GET /me/, including account information and remaining envelope credits used to gauge available signature request volume.

- **Human URL:** [https://docs.signeasy.com/reference/fetch-user-details](https://docs.signeasy.com/reference/fetch-user-details)
- **Base URL:** `https://api.signeasy.com/v3`

#### Tags

- Users
- Account
- Credits

#### Properties

- [API Reference](https://docs.signeasy.com/reference/fetch-user-details)
- [OpenAPI](openapi/signeasy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/signeasy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/signeasy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/signeasy)
- [LinkedIn](https://www.linkedin.com/company/signeasy)
- [Website](https://signeasy.com/)
- [Documentation](https://docs.signeasy.com/)
- [Plans](plans/signeasy-plans-pricing.yml)
- [Rate Limits](rate-limits/signeasy-rate-limits.yml)
- [Fin Ops](finops/signeasy-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
