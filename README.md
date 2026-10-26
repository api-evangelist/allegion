# Allegion (allegion)

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
