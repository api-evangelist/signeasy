# Signeasy (signeasy)

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
