# Paytm

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

Paytm (One97 Communications) is India's leading digital payments and financial services company. Through Paytm for Business it operates a wide catalogue of payment APIs covering online payment gateway, UPI, payment links, subscriptions, auto-debit, pre-auth, refunds, settlement, payouts, token gateway, bank offers, EMI, disputes, and in-store retail solutions (Dynamic QR, EDC, Point-of-Sale). Backend integrations are exposed via REST APIs at the secure gateway (securegw.paytm.in), with first-party Android, iOS, Flutter, React Native, and Web JS / Custom Checkout / JS Elements SDKs, and server SDKs for S2S checksum-signed flows.

**Areas:** Payments · Payment Gateway · UPI · Payouts · Subscription · Refunds · Settlement · QR · EDC · Fintech · India

## Paytm on APIs.io

Everything profiled for Paytm is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/paytm/](https://apis.io/providers/paytm/)** — or go straight to one of the APIs or properties below.

### APIs (17)

- [Paytm Payments API](https://apis.io/apis/paytm/payments/) — Core server-to-server payment initiation and status APIs. Generates transaction tokens, processes payments across UPI, cards, netbanking, and wallet, and…
- [Paytm Refunds API](https://apis.io/apis/paytm/refunds/) — Initiates full and partial refunds against settled or unsettled Paytm transactions and exposes refund status retrieval. Supports instant refund flows for…
- [Paytm Settlement API](https://apis.io/apis/paytm/settlement/) — Returns settlement reports and merchant payout cycles for transactions collected through Paytm, including settlement IDs, UTRs, and per-order breakdowns for…
- [Paytm Subscriptions API](https://apis.io/apis/paytm/subscriptions/) — Creates and manages recurring payment subscriptions and mandates across cards, UPI AutoPay, and netbanking e-mandates. Supports plan creation, subscription…
- [Paytm Auto-Debit API](https://apis.io/apis/paytm/auto-debit/) — Auto-debit mandate APIs for recurring collections, enabling merchants to register, authenticate, and debit customer accounts on a schedule under RBI's…
- [Paytm Pre-Auth API](https://apis.io/apis/paytm/pre-auth/) — Authorize and later capture or release card holds. Used for travel, hospitality, and rental flows that need to block funds before final settlement.
- [Paytm Payment Links API](https://apis.io/apis/paytm/payment-links/) — Generate shareable payment links for collection over email, SMS, WhatsApp, or social channels. Supports expiry, partial payments, and callback notifications…
- [Paytm Token Gateway API](https://apis.io/apis/paytm/token-gateway/) — Card tokenization service compliant with RBI guidelines. Exchanges raw card PANs for network or issuer tokens that merchants can store and use for repeat…
- [Paytm Bank Offers / EMI API](https://apis.io/apis/paytm/bank-offers/) — Returns available bank offers, instant discounts, no-cost EMI plans, and EMI subvention metadata for the customer's card or netbanking option at checkout.
- [Paytm Disputes / Chargeback API](https://apis.io/apis/paytm/disputes/) — Lists, retrieves, and responds to chargebacks and disputes raised against merchant transactions, including evidence upload and status tracking.
- [Paytm Dynamic QR API](https://apis.io/apis/paytm/dynamic-qr/) — Generates per-order dynamic UPI / Bharat QR codes for in-store and contactless collection, with order-linked status callbacks.
- [Paytm Status Notification Webhook](https://apis.io/apis/paytm/webhook/) — Server-to-server notification posted to a merchant-configured URL when a transaction reaches a terminal state. Includes signed payload with transaction,…
- [Paytm All-in-One SDK (Android)](https://apis.io/apis/paytm/all-in-one-sdk-android/) — Native Android SDK that hosts the Paytm payment experience inside the merchant app, supporting UPI, cards, netbanking, wallet, and Paytm Postpaid in a…
- [Paytm All-in-One SDK (iOS)](https://apis.io/apis/paytm/all-in-one-sdk-ios/) — Native iOS SDK that hosts the Paytm payment experience inside the merchant app across all supported payment methods.
- [Paytm JS Checkout](https://apis.io/apis/paytm/js-checkout/) — Browser JavaScript checkout that renders the Paytm payment page in two steps - server-side token creation followed by client-side invocation of the hosted…
- [Paytm Payments API](https://apis.io/apis/paytm/paytm-payments-api/) — The Payments API from Paytm — 2 operation(s) for payments.
- [Paytm Refunds API](https://apis.io/apis/paytm/paytm-refunds-api/) — The Refunds API from Paytm — 1 operation(s) for refunds.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Paytm Agentic Access](https://apis.io/agentic-access/paytm/paytm-agentic-access/)

#### Collections (3)

Postman and Open Collection request collections.

- [Paytm Payment Gateway API](https://apis.io/collections/paytm/open-paytm/)
- [Paytm Payment Gateway Payments API](https://apis.io/collections/paytm/open-paytm-payments-api/)
- [Paytm Payment Gateway Payments Refunds API](https://apis.io/collections/paytm/open-paytm-refunds-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Paytm Authentication](https://apis.io/security/paytm/paytm-authentication/)
- [Paytm Domain Security](https://apis.io/security/paytm/paytm-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Paytm Plans Pricing](https://apis.io/plans/paytm/paytm-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Paytm Rate Limits](https://apis.io/rate-limits/paytm/paytm-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Paytm Finops](https://apis.io/finops/paytm/paytm-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://business.paytm.com/)
- [Documentation](https://business.paytm.com/docs/)
- [Blog](https://business.paytm.com/blog)

## API Evangelist rating

**Kin Score 23.9** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 67.9 |
| Contract quality | 47.8 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 23.8 |
| Access clarity | 5.3 |

**Agent readiness 22.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 10.7** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/paytm/](https://apis.io/providers/paytm/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Paytm: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/paytm/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
