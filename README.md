# Allegion

Allegion plc is a global security products company with $3.8B in 2024 revenue, 13,000+ employees, and 30+ brands across 120 countries (Schlage, Von Duprin, LCN, CISA, Steelcraft, Interflex, SimonsVoss, Yonomi). The Allegion Developer Portal exposes two documented integration surfaces — the Schlage Home API V2 (residential WiFi smart locks) and the ENGAGE Cloud Credentialing API (commercial BLE mobile credentials) — plus iOS and Android Device Communication and BLE Mobile Access SDKs gated behind an Allegion Security Token Agreement.

**Type:** Company
**Modified:** 2026-05-23

## Tags

Access Control, Schlage, Von Duprin, ENGAGE, Smart Lock, Smart Home, Mobile Credentials, Bluetooth, BLE, IoT, Security, Webhooks, OAuth

## Developer Portal

- [Allegion Developer Portal](https://developer.allegion.com)
- [Documentation](https://developer.allegion.com/en/documentation.html)
- [Release Notes](https://developer.allegion.com/en/release-notes.html)
- [Developer Support (Zendesk)](https://developersupport.allegion.com/hc/en-us)
- [Azure API Management Portal](https://developerapi.allegion.com)

## APIs

### Schlage Home API

REST + webhook API for the Schlage Home residential smart-lock platform (Schlage Encode, Encode Plus, Encode Lever). Designed for business and commercial integrations — partner apps and smart-home automation platforms — that scale across residential deployments. Uses OAuth 2.0 Authorization Code flow against `account.schlage.com` and an asynchronous 202 ACCEPTED command pattern.

**Human URL:** [https://developer.allegion.com/en/products/schlage-home/schlage-home-api.html](https://developer.allegion.com/en/products/schlage-home/schlage-home-api.html)
**Base URL:** `https://api.allegion.com/schlage-home`

#### Properties
- [Documentation](https://developer.allegion.com/en/products/schlage-home/schlage-home-api.html)
- [Getting Started](https://developer.allegion.com/en/products/schlage-home/getting-started.html)
- [Best Practices](https://developer.allegion.com/en/products/schlage-home/best-practices.html)
- [Access Codes Quickstart](https://developer.allegion.com/en/products/schlage-home/getting_started_res_access_codes.html)
- [Blog](https://developer.allegion.com/en/products/schlage-home/schlage-home-api-blog.html)
- [OpenAPI](openapi/schlage-home-openapi.yml)
- [Capability — Devices](capabilities/schlage-home-devices.yaml)
- [Capability — Access Codes](capabilities/schlage-home-access-codes.yaml)
- [Capability — Webhooks](capabilities/schlage-home-webhooks.yaml)
- [Spectral Rules](rules/schlage-home-rules.yml)
- [JSON Schema — Device](json-schema/schlage-home-device-schema.json)
- [JSON Schema — Access Code](json-schema/schlage-home-access-code-schema.json)
- [JSON Schema — Webhook Subscription](json-schema/schlage-home-webhook-subscription-schema.json)
- [JSON Structure — Device](json-structure/schlage-home-device-structure.json)
- [Example — List Devices](examples/schlage-home-list-devices-example.json)
- [Example — Create Access Code](examples/schlage-home-create-access-code-example.json)
- [Example — Webhook Subscription](examples/schlage-home-webhook-subscription-example.json)

### ENGAGE Cloud Credentialing API

REST API on the Allegion Device Management and Mobile Access Cloud (Engage Cloud) for managing BLE Mobile Credentials. Brokers interactions between an Access Control System (ACS), the Allegion Mobile SDKs (iOS / Android), and Gen 2 ENGAGE Schlage hardware (Control B, NDEB, LEBMS/LEBMD locks; MTKB readers) plus Von Duprin RU/RM exit devices. Authenticated with an `alle-subscription-key` header plus Basic Auth derived from ENGAGE credentials; integrators must execute the Allegion Security Token Agreement before access is granted.

**Human URL:** [https://developer.allegion.com/en/products/schlage-mobile-credentials/credentialing-api.html](https://developer.allegion.com/en/products/schlage-mobile-credentials/credentialing-api.html)
**Base URL:** `https://api.allegion.com/engage`

#### Properties
- [Documentation](https://developer.allegion.com/en/products/schlage-mobile-credentials/credentialing-api.html)
- [Getting Started](https://developer.allegion.com/en/products/schlage-mobile-credentials/getting-started.html)
- [How to Integrate Schlage BLE with an ACS](https://developer.allegion.com/en/products/schlage-mobile-credentials/how-to-integrate-schlage-ble-mobile-credentials-with-an-access-control-system.html)
- [Mobile SDK Overview](https://developer.allegion.com/en/products/schlage-mobile-credentials/mobile-sdk.html)
- [OpenAPI](openapi/engage-credentialing-openapi.yml)
- [Capability — Credentials](capabilities/engage-credentials.yaml)
- [Spectral Rules](rules/engage-credentialing-rules.yml)
- [JSON Schema — Credential](json-schema/engage-credential-schema.json)
- [JSON Structure — Credential](json-structure/engage-credential-structure.json)
- [Example — Upload Credential](examples/engage-upload-credential-example.json)
- [Example — List Credentials](examples/engage-list-credentials-example.json)

## Cross-API Artifacts

- [JSON-LD Context](json-ld/allegion-context.jsonld)
- [Vocabulary](vocabulary/allegion-vocabulary.yml)
- [Plans & Pricing](plans/allegion-plans-pricing.yml)
- [Rate Limits](rate-limits/allegion-rate-limits.yml)
- [FinOps](finops/allegion-finops.yml)

## Supported Hardware

| Family | Models | Surface |
| --- | --- | --- |
| Schlage Encode (residential WiFi) | BE489WB (Encode), BE499WB (Encode Plus), FE789WB (Encode Lever) | Schlage Home API |
| Schlage Gen 2 ENGAGE (commercial BLE) | Control BE467B / FE410B, NDEB, LEBMS / LEBMD, MTKB readers, XE360, CTE+MTB | ENGAGE Credentialing API |
| Von Duprin (commercial) | RU, RM exit devices | ENGAGE Credentialing API |

ENGAGE for access control supports up to 100 locks per site (500 for Schlage Control) and 5,000 users per site.

## SDKs

- **Allegion BLE Mobile Access SDK** — iOS + Android, hosted in private Allegion GitHub repositories; access requires the Allegion Security Token Agreement.
- **Allegion Device Communication SDK** — iOS + Android, also private; used for ENGAGE device commissioning and door-file distribution.
- Public utility forks live at [github.com/Allegion-Public](https://github.com/Allegion-Public) (AFNetworking, RestKit, CocoaHTTPServer, CocoaLumberjack, Auth0.iOS, LGBluetooth, usb-serial-for-android, etc.) — primarily older Objective-C / Java helper libraries rather than first-party SDKs.

## Brand & Corporate Surfaces

- [Allegion plc (corporate)](https://www.allegion.com) — $3.8B 2024 revenue, 13,000+ employees, 30+ brands across 120 countries.
- [Schlage residential](https://www.schlage.com) — Encode Plus from $329, Encode from $299, Encode Lever from $309, Arrive from $199; "trusted in over 40 million homes".
- [Schlage commercial](https://commercial.schlage.com) — ENGAGE for Access Control product line.
- [Yonomi](https://www.yonomi.com) — smart-home cloud / SDK brand (Allegion-acquired) used for partner integrations such as Schlage Encode.
- [Investors](https://investor.allegion.com), [LinkedIn](https://www.linkedin.com/company/allegion).

## Notable Recent Changes (Schlage Home API)

| Date | Change |
| --- | --- |
| 2026-04-14 | DST offset added to `startDateTime` / `endDateTime` in Access Code webhooks |
| 2025-08-11 | Standardized timestamps in Access Code webhooks |
| 2025-07-30 | Limited trial of Access Code Synchronization |
| 2025-05-28 | New webhook for Invalid Access Codes |
| 2025-03-25 | New Accessor Types added |
| 2025-03-06 | WiFi signal strength surfaced in GET Device endpoint |
| 2024-11-25 | Error messages added to GET Command responses |

Source: [Allegion Developer Portal Release Notes](https://developer.allegion.com/en/release-notes.html).
