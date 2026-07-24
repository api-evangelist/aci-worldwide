# ACI Worldwide (aci-worldwide)

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
