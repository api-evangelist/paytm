# Paytm (paytm)

Paytm (One97 Communications) is India's leading digital payments and financial services company. Through Paytm for Business it operates a wide catalogue of payment APIs covering online payment gateway, UPI, payment links, subscriptions, auto-debit, pre-auth, refunds, settlement, payouts, token gateway, bank offers, EMI, disputes, and in-store retail solutions (Dynamic QR, EDC, Point-of-Sale). Backend integrations are exposed via REST APIs at the secure gateway (securegw.paytm.in), with first-party Android, iOS, Flutter, React Native, and Web JS / Custom Checkout / JS Elements SDKs, and server SDKs for S2S checksum-signed flows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/paytm/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/paytm/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** 3rd-Party

## Tags

- Payments
- Payment Gateway
- UPI
- Payouts
- Subscriptions
- Refunds
- Settlement
- QR
- EDC
- Fintech
- India

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Paytm Payments API

Core server-to-server payment initiation and status APIs. Generates transaction tokens, processes payments across UPI, cards, netbanking, and wallet, and exposes transaction-status retrieval. Requests are checksum-signed and routed through the secure gateway.

- **Human URL:** [https://business.paytm.com/docs/api/](https://business.paytm.com/docs/api/)
- **Base URL:** `https://securegw.paytm.in`

#### Tags

- Payments
- Checkout
- Transactions

#### Properties

- [Documentation](https://business.paytm.com/docs/api/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm Refunds API

Initiates full and partial refunds against settled or unsettled Paytm transactions and exposes refund status retrieval. Supports instant refund flows for eligible payment methods.

- **Human URL:** [https://business.paytm.com/docs/api/refunds/](https://business.paytm.com/docs/api/refunds/)
- **Base URL:** `https://securegw.paytm.in`

#### Tags

- Refunds
- Payments

#### Properties

- [Documentation](https://business.paytm.com/docs/api/refunds/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm Settlement API

Returns settlement reports and merchant payout cycles for transactions collected through Paytm, including settlement IDs, UTRs, and per-order breakdowns for reconciliation.

- **Human URL:** [https://business.paytm.com/docs/api/settlement/](https://business.paytm.com/docs/api/settlement/)
- **Base URL:** `https://securegw.paytm.in`

#### Tags

- Settlement
- Reconciliation
- Reporting

#### Properties

- [Documentation](https://business.paytm.com/docs/api/settlement/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm Subscriptions API

Creates and manages recurring payment subscriptions and mandates across cards, UPI AutoPay, and netbanking e-mandates. Supports plan creation, subscription activation, renewal charging, and cancellation.

- **Human URL:** [https://business.paytm.com/docs/api/subscription/](https://business.paytm.com/docs/api/subscription/)
- **Base URL:** `https://securegw.paytm.in`

#### Tags

- Subscriptions
- Recurring
- Mandates

#### Properties

- [Documentation](https://business.paytm.com/docs/api/subscription/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm Auto-Debit API

Auto-debit mandate APIs for recurring collections, enabling merchants to register, authenticate, and debit customer accounts on a schedule under RBI's e-mandate framework.

- **Human URL:** [https://business.paytm.com/docs/api/auto-debit/](https://business.paytm.com/docs/api/auto-debit/)
- **Base URL:** `https://securegw.paytm.in`

#### Tags

- Auto Debit
- Mandates
- Recurring

#### Properties

- [Documentation](https://business.paytm.com/docs/api/auto-debit/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm Pre-Auth API

Authorize and later capture or release card holds. Used for travel, hospitality, and rental flows that need to block funds before final settlement.

- **Human URL:** [https://business.paytm.com/docs/api/pre-auth/](https://business.paytm.com/docs/api/pre-auth/)
- **Base URL:** `https://securegw.paytm.in`

#### Tags

- Pre Auth
- Authorization
- Capture

#### Properties

- [Documentation](https://business.paytm.com/docs/api/pre-auth/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm Payment Links API

Generate shareable payment links for collection over email, SMS, WhatsApp, or social channels. Supports expiry, partial payments, and callback notifications on completion.

- **Human URL:** [https://business.paytm.com/docs/api/payment-links/](https://business.paytm.com/docs/api/payment-links/)
- **Base URL:** `https://securegw.paytm.in`

#### Tags

- Payment Links
- Collection

#### Properties

- [Documentation](https://business.paytm.com/docs/api/payment-links/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm Token Gateway API

Card tokenization service compliant with RBI guidelines. Exchanges raw card PANs for network or issuer tokens that merchants can store and use for repeat charging and CVV-less flows.

- **Human URL:** [https://business.paytm.com/docs/api/token-gateway/](https://business.paytm.com/docs/api/token-gateway/)
- **Base URL:** `https://securegw.paytm.in`

#### Tags

- Tokenization
- Card on File
- PCI

#### Properties

- [Documentation](https://business.paytm.com/docs/api/token-gateway/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm Bank Offers / EMI API

Returns available bank offers, instant discounts, no-cost EMI plans, and EMI subvention metadata for the customer's card or netbanking option at checkout.

- **Human URL:** [https://business.paytm.com/docs/api/bank-offers/](https://business.paytm.com/docs/api/bank-offers/)
- **Base URL:** `https://securegw.paytm.in`

#### Tags

- Offers
- EMI
- Affordability

#### Properties

- [Documentation](https://business.paytm.com/docs/api/bank-offers/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm Disputes / Chargeback API

Lists, retrieves, and responds to chargebacks and disputes raised against merchant transactions, including evidence upload and status tracking.

- **Human URL:** [https://business.paytm.com/docs/api/disputes/](https://business.paytm.com/docs/api/disputes/)
- **Base URL:** `https://securegw.paytm.in`

#### Tags

- Disputes
- Chargebacks

#### Properties

- [Documentation](https://business.paytm.com/docs/api/disputes/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm Dynamic QR API

Generates per-order dynamic UPI / Bharat QR codes for in-store and contactless collection, with order-linked status callbacks.

- **Human URL:** [https://business.paytm.com/docs/api/dynamic-qr/](https://business.paytm.com/docs/api/dynamic-qr/)
- **Base URL:** `https://securegw.paytm.in`

#### Tags

- QR
- UPI
- In Store

#### Properties

- [Documentation](https://business.paytm.com/docs/api/dynamic-qr/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm Status Notification Webhook

Server-to-server notification posted to a merchant-configured URL when a transaction reaches a terminal state. Includes signed payload with transaction, refund, or subscription event details.

- **Human URL:** [https://business.paytm.com/docs/api/webhook/](https://business.paytm.com/docs/api/webhook/)
- **Base URL:** `customer-configured`

#### Tags

- Webhooks
- Events
- Callbacks

#### Properties

- [Documentation](https://business.paytm.com/docs/api/webhook/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm All-in-One SDK (Android)

Native Android SDK that hosts the Paytm payment experience inside the merchant app, supporting UPI, cards, netbanking, wallet, and Paytm Postpaid in a single flow.

- **Human URL:** [https://business.paytm.com/docs/all-in-one-sdk/](https://business.paytm.com/docs/all-in-one-sdk/)
- **Base URL:** `https://business.paytm.com/docs/all-in-one-sdk/`

#### Tags

- SDK
- Android
- Mobile

#### Properties

- [Documentation](https://business.paytm.com/docs/all-in-one-sdk/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm All-in-One SDK (iOS)

Native iOS SDK that hosts the Paytm payment experience inside the merchant app across all supported payment methods.

- **Human URL:** [https://business.paytm.com/docs/all-in-one-sdk/](https://business.paytm.com/docs/all-in-one-sdk/)
- **Base URL:** `https://business.paytm.com/docs/all-in-one-sdk/`

#### Tags

- SDK
- iOS
- Mobile

#### Properties

- [Documentation](https://business.paytm.com/docs/all-in-one-sdk/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paytm JS Checkout

Browser JavaScript checkout that renders the Paytm payment page in two steps - server-side token creation followed by client-side invocation of the hosted checkout overlay.

- **Human URL:** [https://business.paytm.com/docs/js-checkout/](https://business.paytm.com/docs/js-checkout/)
- **Base URL:** `https://securegw.paytm.in`

#### Tags

- JavaScript
- Checkout
- Web

#### Properties

- [Documentation](https://business.paytm.com/docs/js-checkout/)
- [Postman Collection](collections/paytm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://business.paytm.com/)
- [Documentation](https://business.paytm.com/docs/)
- [LinkedIn](https://www.linkedin.com/company/paytm)
- [Git Hub](https://github.com/Paytm-Payments)
- [L L Ms Txt](https://paytm.com/llms.txt)

## Maintainers

**FN:** API Evangelist
**URL:** https://apievangelist.com
