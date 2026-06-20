# MailPace (mailpace)

MailPace is a fast, privacy-focused transactional email API for developers. It delivers application email - password resets, receipts, notifications - over a simple HTTPS REST API and SMTP, with DKIM-verified sending domains, Ed25519-signed webhooks, and EU-based hosting.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mailpace/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mailpace/refs/heads/main/apis.yml)

## Tags

- Email
- Transactional Email
- Messaging
- SMTP
- Privacy

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### MailPace Send Email API

Sends a transactional email via POST /send using the MailPace-Server-Token header. Supports HTML and text bodies, cc/bcc, reply-to, attachments, tags, and up to 50 recipients per request.

- **Human URL:** [https://docs.mailpace.com/reference/send/](https://docs.mailpace.com/reference/send/)
- **Base URL:** `https://app.mailpace.com/api/v1`

#### Tags

- Email
- Send
- Transactional Email

#### Properties

- [Documentation](https://docs.mailpace.com/reference/send/)
- [API Reference](https://docs.mailpace.com/reference/overview/)
- [OpenAPI](openapi/mailpace-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mailpace.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mailpace.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MailPace Domains API

Manages sending domains and their API tokens with the MailPace-Organization-Token header - create, list, update, and DKIM/DNS verify domains, and create or revoke per-domain API tokens.

- **Human URL:** [https://docs.mailpace.com/reference/domains/](https://docs.mailpace.com/reference/domains/)
- **Base URL:** `https://app.mailpace.com/api/v1`

#### Tags

- Domains
- DKIM
- Verification

#### Properties

- [Documentation](https://docs.mailpace.com/reference/domains/)
- [API Reference](https://docs.mailpace.com/reference/overview/)
- [OpenAPI](openapi/mailpace-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mailpace.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mailpace.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MailPace Webhooks API

Delivers outbound, Ed25519-signed event callbacks (email.queued, email.delivered, email.deferred, email.bounced, email.spam) to your endpoints. Configured per domain in the MailPace dashboard; the public verification key is exposed on the domain object.

- **Human URL:** [https://docs.mailpace.com/guide/webhooks/](https://docs.mailpace.com/guide/webhooks/)
- **Base URL:** `https://app.mailpace.com/api/v1`

#### Tags

- Webhooks
- Events
- Ed25519

#### Properties

- [Documentation](https://docs.mailpace.com/guide/webhooks/)
- [Review](review.yml)

## Common Properties

- [GitHub Organization](https://github.com/mailpace)
- [LinkedIn](https://www.linkedin.com/company/mailpace)
- [Website](https://mailpace.com)
- [Documentation](https://docs.mailpace.com)
- [Plans](plans/mailpace-plans-pricing.yml)
- [Rate Limits](rate-limits/mailpace-rate-limits.yml)
- [Fin Ops](finops/mailpace-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
