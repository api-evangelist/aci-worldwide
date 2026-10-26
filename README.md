# ACI Worldwide (aci-worldwide)

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

ACI Worldwide (NASDAQ: ACIW) is a US-headquartered payment-software company that builds real-time payment, card, merchant/eCommerce, and bill-payment technology for banks, processors, merchants, and billers worldwide. Its enterprise portfolio — BASE24 card/ATM switching, the ACI Enterprise Payments Platform for real-time and ISO 20022 account-to-account rails, and ACI Speedpay bill payment — ships largely as licensed on-premise or hosted software. ACI's API-native surface is the ACI Open Payment Platform (the PAY.ON global payment gateway), a unified RESTful API for accepting and managing card and alternative payments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/aci-worldwide/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/aci-worldwide/refs/heads/main/apis.yml)

## Tags

- Payments
- United States
- Payment Gateway
- Payment Processing
- Acquiring
- Card Payments
- eCommerce
- Fraud
- Tokenization
- 3D Secure
- Bill Payment
- Real-Time Payments
- ISO 20022

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

All ACI public payment APIs run on the Open Payment Platform (PAY.ON) gateway — production host `https://eu-prod.oppwa.com`, test host `https://eu-test.oppwa.com` — authenticated with an `Authorization: Bearer <access-token>` header plus a channel `entityId`. No downloadable OpenAPI/Swagger is published; the reference is human-readable at [docs.aciworldwide.com](https://docs.aciworldwide.com/).

### ACI Open Payment Platform — Server-to-Server API

Core RESTful payments: preauthorization, debit, capture, refund, and reversal across cards and alternative payment methods.

- **Human URL:** [https://docs.aciworldwide.com/server-to-server](https://docs.aciworldwide.com/server-to-server)
- **Base URL:** `https://eu-prod.oppwa.com`

### ACI COPYandPAY

Secure, PCI-friendly embedded payments widget that tokenizes and submits card/APM data directly to the gateway.

- **Human URL:** [https://docs.aciworldwide.com/copyandpay](https://docs.aciworldwide.com/copyandpay)
- **Base URL:** `https://eu-prod.oppwa.com`

### ACI BackOffice API

Post-authorization transaction management — captures, refunds, and reversals.

- **Human URL:** [https://docs.aciworldwide.com/backoffice](https://docs.aciworldwide.com/backoffice)
- **Base URL:** `https://eu-prod.oppwa.com`

### ACI Pay By Link API

Create secure, customizable hosted payment link pages without a full checkout integration.

- **Human URL:** [https://docs.aciworldwide.com/paybylink](https://docs.aciworldwide.com/paybylink)
- **Base URL:** `https://eu-prod.oppwa.com`

### ACI Mobile SDK

Accept payments inside native mobile apps with device-side tokenization and 3-D Secure.

- **Human URL:** [https://docs.aciworldwide.com/mobile-sdk](https://docs.aciworldwide.com/mobile-sdk)
- **Base URL:** `https://eu-prod.oppwa.com`

## Common Properties

- [Website](https://www.aciworldwide.com/)
- [Developer Portal](https://docs.aciworldwide.com/)
- [API Reference](https://docs.aciworldwide.com/reference/parameters)
- [Getting Started](https://docs.aciworldwide.com/integration-guide)
- [Webhooks](https://docs.aciworldwide.com/webhooks)
- [Change Log / Release Notes](https://docs.aciworldwide.com/reference/release-notes)
- [Support](https://docs.aciworldwide.com/support)
- [GitHub Organization](https://github.com/aciworldwide)
- [Blog](https://www.aciworldwide.com/blog)
- [Terms of Use](https://www.aciworldwide.com/terms-of-use)
- [Privacy Policy](https://www.aciworldwide.com/privacy-policy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
