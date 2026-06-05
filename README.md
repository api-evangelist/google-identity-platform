# Google Identity Platform (google-identity-platform)

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
