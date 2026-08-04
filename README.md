# Google Identity Platform (google-identity-platform)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Google Identity Platform provides authentication and identity management APIs that enable developers to add sign-in, user management, and multi-tenancy capabilities to applications using industry-standard protocols including OAuth 2.0, OpenID Connect, and SAML.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/google-identity-platform/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/google-identity-platform/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Authentication
- Google Cloud
- Identity
- Multi-Tenancy
- OAuth
- OpenID Connect
- SAML

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### Identity Toolkit API

The Identity Toolkit API (v3) provides REST endpoints for managing user authentication in Google Identity Platform. It supports creating and signing in users with email/password, phone, and federated identity providers. The API handles token verification, password resets, email verification, account linking, and multi-factor authentication enrollment and sign-in.

- **Human URL:** [https://cloud.google.com/identity-platform/docs/reference/rest](https://cloud.google.com/identity-platform/docs/reference/rest)
- **Base URL:** `https://identitytoolkit.googleapis.com`

#### Tags

- Authentication
- Identity
- Sign-In
- Users

#### Properties

- [Documentation](https://cloud.google.com/identity-platform/docs/reference/rest)
- [OpenAPI](openapi/identity-toolkit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/identity-toolkit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/identity-toolkit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/google-identity-platform-user-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Identity Platform Tenant Management API

The Tenant Management API enables developers to create and manage tenants for multi-tenant Identity Platform configurations. Each tenant can have its own set of identity providers, authentication settings, and user pools, allowing SaaS applications to isolate authentication for different customers or organizational units.

- **Human URL:** [https://cloud.google.com/identity-platform/docs/multi-tenancy](https://cloud.google.com/identity-platform/docs/multi-tenancy)
- **Base URL:** `https://identitytoolkit.googleapis.com`

#### Tags

- Multi-Tenancy
- SaaS
- Tenant Management

#### Properties

- [Documentation](https://cloud.google.com/identity-platform/docs/multi-tenancy)
- [Postman Collection](collections/identity-toolkit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/identity-toolkit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Identity Platform OAuth Configuration API

The OAuth Configuration API allows developers to programmatically manage OAuth identity provider configurations for Identity Platform projects. It supports configuring Google, Facebook, Apple, Microsoft, Twitter, GitHub, and other OIDC and SAML providers for federated authentication.

- **Human URL:** [https://cloud.google.com/identity-platform/docs/federated-login](https://cloud.google.com/identity-platform/docs/federated-login)
- **Base URL:** `https://identitytoolkit.googleapis.com`

#### Tags

- Federation
- Identity Providers
- OAuth

#### Properties

- [Documentation](https://cloud.google.com/identity-platform/docs/reference/rest/v2/projects.defaultSupportedIdpConfigs)
- [Postman Collection](collections/identity-toolkit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/identity-toolkit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Getting Started](https://cloud.google.com/identity-platform/docs/quickstarts)
- [Pricing](https://cloud.google.com/identity-platform/pricing)
- [Authentication](https://cloud.google.com/identity-platform/docs/concepts)
- [Console](https://console.cloud.google.com/customer-identity)
- [S D Ks](https://cloud.google.com/identity-platform/docs/reference/libraries)
- [Support](https://cloud.google.com/identity-platform/docs/support)
- [Status Page](https://status.cloud.google.com)
- [JSON-LD](json-ld/google-identity-platform-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://cloud.google.com/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
