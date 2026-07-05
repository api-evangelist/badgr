# Badgr (badgr)

Badgr is an open digital badging and micro-credentialing platform built on the Open Badges standard. Originally created by Concentric Sky, Badgr is now operated by Instructure as Canvas Credentials (and folded into Parchment Digital Badges). It lets organizations issue verifiable, portable achievement badges and lets learners collect them in a shareable Backpack. The platform is backed by the open-source `badgr-server` (github.com/concentricsky/badgr-server, GNU AGPL-3.0), which implements Open Badges 2.0/2.1 (Badge Connect). The documented REST API (base `https://api.badgr.io/v2`, with regional deployments in the EU, Canada, and Australia) uses OAuth2 bearer tokens and exposes Issuers, BadgeClasses, Assertions (awarded badges), the learner Backpack, Collections, and Users.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/badgr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/badgr/refs/heads/main/apis.yml)

## Tags

- Digital Badges
- Open Badges
- Micro-Credentials
- Credentialing
- Verifiable Credentials
- Education
- Open Source

## Timestamps

- **Created:** 2026-07-05
- **Modified:** 2026-07-05

## APIs

### Badgr Issuers API

Create, list, get, update, and delete Issuers - the organizations or programs that award badges. Includes nested access to an issuer's BadgeClasses and Assertions, plus an issuers/changed feed for syncing.

- **Human URL:** [https://api.badgr.io/docs/v2/](https://api.badgr.io/docs/v2/)
- **Base URL:** `https://api.badgr.io/v2`

#### Tags

- Issuers
- Organizations
- Open Badges

#### Properties

- [API Reference](https://api.badgr.io/docs/v2/)
- [Documentation](https://community.canvaslms.com/t5/Canvas-Badges/Canvas-Badges-App-Developers-API-Guide-Quickstart/ta-p/528729)
- [OpenAPI](openapi/badgr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/badgr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/badgr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Badgr BadgeClasses API

Define and manage BadgeClasses - the reusable badge templates (name, description, image, criteria, alignments, and tags) that get awarded as Assertions. Supports single and batch issuing plus a badgeclasses/changed feed.

- **Human URL:** [https://api.badgr.io/docs/v2/](https://api.badgr.io/docs/v2/)
- **Base URL:** `https://api.badgr.io/v2`

#### Tags

- BadgeClasses
- Badge Definitions
- Open Badges

#### Properties

- [API Reference](https://api.badgr.io/docs/v2/)
- [Documentation](https://community.canvaslms.com/t5/Canvas-Badges/Canvas-Badges-App-Developers-API-Guide-Quickstart/ta-p/528729)
- [OpenAPI](openapi/badgr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/badgr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/badgr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Badgr Assertions (Awarded Badges) API

Issue, retrieve, update, and revoke Assertions - individual awards of a BadgeClass to a named recipient. Assertions are the verifiable Open Badges objects; supports single and batch issue, batch revoke, and an assertions/changed feed.

- **Human URL:** [https://api.badgr.io/docs/v2/](https://api.badgr.io/docs/v2/)
- **Base URL:** `https://api.badgr.io/v2`

#### Tags

- Assertions
- Awarded Badges
- Issuing
- Verification

#### Properties

- [API Reference](https://api.badgr.io/docs/v2/)
- [Documentation](https://concentricsky.github.io/badge-connect-guide/)
- [OpenAPI](openapi/badgr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/badgr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/badgr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Badgr Backpack API

The learner-side Backpack for badges an earner has received or imported from any Open Badges issuer. List and manage held Assertions, import external badges, retrieve baked badge images, and create public share links.

- **Human URL:** [https://api.badgr.io/docs/v2/](https://api.badgr.io/docs/v2/)
- **Base URL:** `https://api.badgr.io/v2`

#### Tags

- Backpack
- Earners
- Portable Credentials

#### Properties

- [API Reference](https://api.badgr.io/docs/v2/)
- [Documentation](https://concentricsky.github.io/badge-connect-guide/)
- [OpenAPI](openapi/badgr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/badgr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/badgr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Badgr Collections API

Group Backpack Assertions into named Collections that learners can curate and publish. Create, list, get, update, and delete collections, and generate a public share URL for a collection.

- **Human URL:** [https://api.badgr.io/docs/v2/](https://api.badgr.io/docs/v2/)
- **Base URL:** `https://api.badgr.io/v2`

#### Tags

- Collections
- Backpack
- Sharing

#### Properties

- [API Reference](https://api.badgr.io/docs/v2/)
- [Documentation](https://concentricsky.github.io/badge-connect-guide/)
- [OpenAPI](openapi/badgr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/badgr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/badgr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Badgr Users API

Read and update the authenticated user's profile via `/users/self`, manage account emails and the latest terms version. Governs the identity behind both issuing and earning.

- **Human URL:** [https://api.badgr.io/docs/v2/](https://api.badgr.io/docs/v2/)
- **Base URL:** `https://api.badgr.io/v2`

#### Tags

- Users
- Profiles
- Accounts

#### Properties

- [API Reference](https://api.badgr.io/docs/v2/)
- [Documentation](https://community.canvaslms.com/t5/Canvas-Badges/Canvas-Badges-App-Developers-API-Guide-Quickstart/ta-p/528729)
- [OpenAPI](openapi/badgr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/badgr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/badgr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Badgr Authentication API

OAuth2 authentication surface. Exchange credentials for a bearer token at `/o/token` (scopes rw:profile rw:issuer rw:backpack), run the authorization-code flow at `/o/authorize` and `/o/code`, and list or revoke issued access tokens at `/v2/auth/tokens`.

- **Human URL:** [https://api.badgr.io/docs/v2/](https://api.badgr.io/docs/v2/)
- **Base URL:** `https://api.badgr.io`

#### Tags

- Authentication
- OAuth2
- Access Tokens

#### Properties

- [API Reference](https://api.badgr.io/docs/v2/)
- [Documentation](https://community.canvaslms.com/t5/Canvas-Badges/Canvas-Badges-App-Developers-API-Guide-Quickstart/ta-p/528729)
- [OpenAPI](openapi/badgr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/badgr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/badgr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/concentricsky)
- [LinkedIn](https://www.linkedin.com/company/instructure)
- [Website](https://badgr.com)
- [Documentation](https://api.badgr.io/docs/v2/)
- [Plans](plans/badgr-plans-pricing.yml)
- [Rate Limits](rate-limits/badgr-rate-limits.yml)
- [Fin Ops](finops/badgr-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
