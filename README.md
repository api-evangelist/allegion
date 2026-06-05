# Allegion (allegion)

Allegion plc is a global security products company with $3.8B in 2024 revenue, 13,000+ employees, and 30+ brands across 120 countries (Schlage, Von Duprin, LCN, CISA, Steelcraft, Interflex, SimonsVoss, Yonomi). The Allegion Developer Portal exposes two documented integration surfaces - the Schlage Home API V2 (residential WiFi smart locks) and the ENGAGE Cloud Credentialing API (commercial BLE mobile credentials), plus iOS and Android Device Communication and BLE Mobile Access SDKs gated behind an Allegion Security Token Agreement.

**APIs.json:** [https://github.com/api-evangelist/allegion](https://github.com/api-evangelist/allegion)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Access Control
- Smart Lock
- Smart Home
- Mobile Credentials
- Bluetooth
- BLE
- IoT
- Security
- Webhooks
- OAuth
- Schlage
- Von Duprin
- ENGAGE

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Schlage Home API

REST + webhook API for the Schlage Home residential smart-lock platform. Designed for business and commercial integrations (partner apps, smart-home automation platforms) that scale across residential deployments of WiFi-enabled Schlage Encode, Encode Plus, and Encode Lever devices. Uses OAuth 2.0 Authorization Code flow against account.schlage.com, async 202 ACCEPTED command pattern, and webhook subscriptions for device, command, access code, and account events.

- **Human URL:** [https://developer.allegion.com/en/products/schlage-home/schlage-home-api.html](https://developer.allegion.com/en/products/schlage-home/schlage-home-api.html)
- **Base URL:** `https://api.allegion.com/schlage-home`

#### Tags

- Smart Lock
- Residential
- WiFi
- OAuth
- Webhooks
- Access Codes
- Devices
- Schlage Encode

#### Properties

- [Documentation](https://developer.allegion.com/en/products/schlage-home/schlage-home-api.html)
- [Getting Started](https://developer.allegion.com/en/products/schlage-home/getting-started.html)
- [Best Practices](https://developer.allegion.com/en/products/schlage-home/best-practices.html)
- [Quickstart](https://developer.allegion.com/en/products/schlage-home/getting_started_res_access_codes.html)
- [Blog](https://developer.allegion.com/en/products/schlage-home/schlage-home-api-blog.html)
- [Authentication](https://developer.allegion.com/en/products/schlage-home/getting-started.html)
- [Webhooks](https://developer.allegion.com/en/products/schlage-home/best-practices.html)
- [Release Notes](https://developer.allegion.com/en/release-notes.html)
- [OpenAPI](openapi/schlage-home-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/schlage-home.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/schlage-home.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/schlage-home-rules.yml)
- [JSON Schema](json-schema/schlage-home-device-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/schlage-home-access-code-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/schlage-home-webhook-subscription-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/schlage-home-device-structure.json)
- [Example](examples/schlage-home-list-devices-example.json)
- [Example](examples/schlage-home-create-access-code-example.json)
- [Example](examples/schlage-home-webhook-subscription-example.json)

### ENGAGE Cloud Credentialing API

REST API on the Allegion Device Management and Mobile Access Cloud (Engage Cloud) for managing BLE Mobile Credentials used to unlock ENGAGE Gen 2 hardware (Schlage Control B, NDEB, LEBMS/LEBMD locks; MTKB readers; Von Duprin RU/RM). Brokers interactions between Access Control Systems (ACS), the Allegion Mobile SDKs, and Schlage hardware. Authentication requires an alle-subscription-key header plus a Basic Auth token derived from ENGAGE credentials; integrators must sign the Allegion Security Token Agreement before receiving SDK and API access.

- **Human URL:** [https://developer.allegion.com/en/products/schlage-mobile-credentials/credentialing-api.html](https://developer.allegion.com/en/products/schlage-mobile-credentials/credentialing-api.html)
- **Base URL:** `https://api.allegion.com/engage`

#### Tags

- Mobile Credentials
- BLE
- Bluetooth
- Access Control
- Commercial
- ENGAGE
- Subscription Key

#### Properties

- [Documentation](https://developer.allegion.com/en/products/schlage-mobile-credentials/credentialing-api.html)
- [Getting Started](https://developer.allegion.com/en/products/schlage-mobile-credentials/getting-started.html)
- [Tutorials](https://developer.allegion.com/en/products/schlage-mobile-credentials/how-to-integrate-schlage-ble-mobile-credentials-with-an-access-control-system.html)
- [SDK](https://developer.allegion.com/en/products/schlage-mobile-credentials/mobile-sdk.html)
- [SDK](https://developer.allegion.com/en/products/schlage-mobile-credentials/how-to-integrate-schlage-ble-mobile-credentials-with-an-access-control-system.html)
- [Authentication](https://developer.allegion.com/en/products/schlage-mobile-credentials/credentialing-api.html)
- [Terms of Service](https://developer.allegion.com/en/products/schlage-mobile-credentials/how-to-integrate-schlage-ble-mobile-credentials-with-an-access-control-system.html)
- [OpenAPI](openapi/engage-credentialing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/engage-credentialing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/engage-credentialing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/engage-credentialing-rules.yml)
- [JSON Schema](json-schema/engage-credential-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/engage-credential-structure.json)
- [Example](examples/engage-upload-credential-example.json)
- [Example](examples/engage-list-credentials-example.json)

## Common Properties

- [Developer Portal](https://developer.allegion.com)
- [Portal](https://developerapi.allegion.com)
- [Sign In](https://developerapi.allegion.com/signin/)
- [Documentation](https://developer.allegion.com/en/documentation.html)
- [Overview](https://developer.allegion.com/en/index.html)
- [Release Notes](https://developer.allegion.com/en/release-notes.html)
- [Support](https://developersupport.allegion.com/hc/en-us)
- [Authentication](https://developer.allegion.com/en/products/schlage-home/getting-started.html)
- [GitHub Organization](https://github.com/Allegion)
- [GitHub Organization](https://github.com/Allegion-Public)
- [SDK](https://developer.allegion.com/en/products/schlage-mobile-credentials/mobile-sdk.html)
- [SDK](https://developer.allegion.com/en/products/schlage-mobile-credentials/how-to-integrate-schlage-ble-mobile-credentials-with-an-access-control-system.html)
- [Blog](https://developer.allegion.com/en/products/schlage-home/schlage-home-api-blog.html)
- [Corporate Site](https://www.allegion.com)
- [About](https://www.allegion.com/corp/en/about.html)
- [Consumer Brand](https://www.schlage.com)
- [Consumer Brand](https://commercial.schlage.com)
- [Consumer Brand](https://www.vonduprin.com)
- [Consumer Brand](https://www.lcnclosers.com)
- [Consumer Brand](https://www.yonomi.com)
- [Partners](https://www.allegion.com/corp/en/partners.html)
- [LinkedIn](https://www.linkedin.com/company/allegion)
- [X (Twitter)](https://x.com/AllegionPlc)
- [Investors](https://investor.allegion.com)
- [Terms of Service](https://developer.allegion.com/en/products/schlage-mobile-credentials/how-to-integrate-schlage-ble-mobile-credentials-with-an-access-control-system.html)
- [Privacy Policy](https://www.allegion.com/corp/en/privacy-policy.html)
- [Features](undefined)
- [Scale](undefined)
- [Supported Hardware](undefined)
- [JSON-LD](json-ld/allegion-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/allegion-vocabulary.yml)
- [Plans](plans/allegion-plans-pricing.yml)
- [Rate Limits](rate-limits/allegion-rate-limits.yml)
- [Fin Ops](finops/allegion-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**FN:** Allegion Developer Support
**URL:** https://developersupport.allegion.com/hc/en-us
