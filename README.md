# Google Identity Platform (google-identity-platform)
Google Identity Platform provides authentication and identity management APIs on Google Cloud that enable developers to add sign-in, user management, and multi-tenancy capabilities to applications. It supports email/password, phone, and federated identity providers (Google, Facebook, Apple, SAML, OIDC) through the Identity Toolkit REST API, with additional APIs for tenant management and OAuth provider configuration.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/google-identity-platform/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Authentication, Identity, OAuth, OpenID Connect, SAML, Multi-Tenancy, Google Cloud

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-03-13

## APIs

### Identity Toolkit API
The Identity Toolkit API (v3) provides REST endpoints for managing user authentication in Google Identity Platform. It supports creating and signing in users with email/password, phone, and federated identity providers. The API handles token verification, password resets, email verification, account linking, and multi-factor authentication enrollment and sign-in.

**Human URL:** [https://cloud.google.com/identity-platform/docs/reference/rest](https://cloud.google.com/identity-platform/docs/reference/rest)


#### Tags:

 - Authentication, Users, Sign-In, Identity

#### Properties

- [Documentation](https://cloud.google.com/identity-platform/docs/reference/rest)
- [OpenAPI](openapi/identity-toolkit-openapi.yml)
- [JSONSchema](json-schema/google-identity-platform-user-schema.json)

### Identity Platform Tenant Management API
The Tenant Management API enables developers to create and manage tenants for multi-tenant Identity Platform configurations. Each tenant can have its own set of identity providers, authentication settings, and user pools, allowing SaaS applications to isolate authentication for different customers or organizational units.

**Human URL:** [https://cloud.google.com/identity-platform/docs/multi-tenancy](https://cloud.google.com/identity-platform/docs/multi-tenancy)


#### Tags:

 - Multi-Tenancy, Tenant Management, SaaS

#### Properties

- [Documentation](https://cloud.google.com/identity-platform/docs/multi-tenancy)

### Identity Platform OAuth Configuration API
The OAuth Configuration API allows developers to programmatically manage OAuth identity provider configurations for Identity Platform projects. It supports configuring Google, Facebook, Apple, Microsoft, Twitter, GitHub, and other OIDC and SAML providers for federated authentication.

**Human URL:** [https://cloud.google.com/identity-platform/docs/federated-login](https://cloud.google.com/identity-platform/docs/federated-login)


#### Tags:

 - OAuth, Federation, Identity Providers

#### Properties

- [Documentation](https://cloud.google.com/identity-platform/docs/reference/rest/v2/projects.defaultSupportedIdpConfigs)

## Common Properties

- [GettingStarted](https://cloud.google.com/identity-platform/docs/quickstarts)
- [Pricing](https://cloud.google.com/identity-platform/pricing)
- [Authentication](https://cloud.google.com/identity-platform/docs/concepts)
- [Console](https://console.cloud.google.com/customer-identity)
- [SDKs](https://cloud.google.com/identity-platform/docs/reference/libraries)
- [Support](https://cloud.google.com/identity-platform/docs/support)
- [Status](https://status.cloud.google.com)
- [JSON-LD](json-ld/google-identity-platform-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
