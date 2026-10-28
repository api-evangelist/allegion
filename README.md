# Allegion

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

**Areas:** Access Control · Smart Lock · Smart Home · Mobile Credentials · Bluetooth · BLE · IoT · Security · Webhook · Authentication · Schlage · Von Duprin

## Allegion on APIs.io

Everything profiled for Allegion is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/allegion/](https://apis.io/providers/allegion/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Allegion Access Codes API](https://apis.io/apis/allegion/allegion-access-codes-api/) — Create, schedule, update, and delete numeric access codes per device
- [Allegion Commands API](https://apis.io/apis/allegion/allegion-commands-api/) — Track the asynchronous status of lock / unlock and configuration commands
- [Allegion Devices API](https://apis.io/apis/allegion/allegion-devices-api/) — ENGAGE hardware discovery and commissioning (Allegion Device Communication SDK)
- [Allegion Mobile Credentials API](https://apis.io/apis/allegion/allegion-mobile-credentials-api/) — Upload, delete, and list BLE Mobile Credentials for end users
- [Allegion Webhook Subscriptions API](https://apis.io/apis/allegion/allegion-webhook-subscriptions-api/) — Subscribe partner endpoints to device, command, access code, and account events

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Allegion Agentic Access](https://apis.io/agentic-access/allegion/allegion-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [ENGAGE Mobile Credential](https://apis.io/schemas/allegion/engage-credential/)
- [Schlage Home Access Code](https://apis.io/schemas/allegion/schlage-home-access-code/)
- [Schlage Home Device](https://apis.io/schemas/allegion/schlage-home-device/)
- [Schlage Home Webhook Subscription](https://apis.io/schemas/allegion/schlage-home-webhook-subscription/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Engage Credential Structure](https://apis.io/json-structure/allegion/engage-credential-structure/)
- [Schlage Home Device Structure](https://apis.io/json-structure/allegion/schlage-home-device-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Allegion Context](https://apis.io/jsonld/allegion/allegion-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Allegion Vocabulary](https://apis.io/vocabularies/allegion/allegion-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Engage List Credentials Example](https://apis.io/examples/allegion/engage-list-credentials-example/)
- [Engage Upload Credential Example](https://apis.io/examples/allegion/engage-upload-credential-example/)
- [Schlage Home Create Access Code Example](https://apis.io/examples/allegion/schlage-home-create-access-code-example/)
- [Schlage Home List Devices Example](https://apis.io/examples/allegion/schlage-home-list-devices-example/)
- [Schlage Home Webhook Subscription Example](https://apis.io/examples/allegion/schlage-home-webhook-subscription-example/)

#### Collections (12)

Postman and Open Collection request collections.

- [ENGAGE Cloud Credentialing Access Codes API](https://apis.io/collections/allegion/open-allegion-access-codes-api/)
- [ENGAGE Cloud Credentialing Access Codes Commands API](https://apis.io/collections/allegion/open-allegion-commands-api/)
- [ENGAGE Cloud Credentialing Access Codes Devices API](https://apis.io/collections/allegion/open-allegion-devices-api/)
- [ENGAGE Cloud Credentialing Access Codes Mobile Credentials API](https://apis.io/collections/allegion/open-allegion-mobile-credentials-api/)
- [ENGAGE Cloud Credentialing Access Codes Webhook Subscriptions API](https://apis.io/collections/allegion/open-allegion-webhook-subscriptions-api/)
- [ENGAGE Cloud Credentialing API](https://apis.io/collections/allegion/open-engage-credentialing/)
- [Schlage Home API](https://apis.io/collections/allegion/open-schlage-home/)
- [ENGAGE Cloud Credentialing Access Codes API](https://apis.io/collections/allegion/postman-allegion-access-codes-api/)
- [ENGAGE Cloud Credentialing Access Codes Commands API](https://apis.io/collections/allegion/postman-allegion-commands-api/)
- [ENGAGE Cloud Credentialing Access Codes Devices API](https://apis.io/collections/allegion/postman-allegion-devices-api/)
- [ENGAGE Cloud Credentialing Access Codes Mobile Credentials API](https://apis.io/collections/allegion/postman-allegion-mobile-credentials-api/)
- [ENGAGE Cloud Credentialing Access Codes Webhook Subscriptions API](https://apis.io/collections/allegion/postman-allegion-webhook-subscriptions-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Allegion — jsonschema rules](https://apis.io/rules/allegion/allegion-jsonschema-spectral-rules/)
- [Allegion — engage credentialing rules](https://apis.io/rules/allegion/engage-credentialing-rules/)
- [Allegion — schlage home rules](https://apis.io/rules/allegion/schlage-home-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Allegion Authentication](https://apis.io/security/allegion/allegion-authentication/)
- [Allegion Domain Security](https://apis.io/security/allegion/allegion-domain-security/)
- [Allegion Trust Center](https://apis.io/security/allegion/allegion-trust-center/)
- [Allegion Vulnerability Disclosure](https://apis.io/security/allegion/allegion-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Allegion Scopes](https://apis.io/scopes/allegion/allegion-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Allegion Plans Pricing](https://apis.io/plans/allegion/allegion-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Allegion Rate Limits](https://apis.io/rate-limits/allegion/allegion-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Allegion Finops](https://apis.io/finops/allegion/allegion-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.allegion.com/)
- [Documentation](https://developer.allegion.com/en/documentation.html)
- [Support](https://developersupport.allegion.com/hc/en-us)
- [Blog](https://developer.allegion.com/en/products/schlage-home/schlage-home-api-blog.html)
- [Terms of service](https://developer.allegion.com/en/products/schlage-mobile-credentials/how-to-integrate-schlage-ble-mobile-credentials-with-an-access-control-system.html)
- [Privacy policy](https://www.allegion.com/corp/en/privacy-policy.html)
- [GitHub](https://github.com/Allegion)

## API Evangelist rating

**Kin Score 52.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 62.9 |
| Contract governance | 27.3 |
| Operational transparency | 44.7 |
| Developer ergonomics | 58.3 |
| Access clarity | 32.9 |

**Agent readiness 29.6** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 41.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/allegion/](https://apis.io/providers/allegion/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Allegion: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/allegion/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
