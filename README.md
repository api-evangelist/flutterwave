# Flutterwave

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

Flutterwave is a pan-African payment infrastructure company providing the rails for businesses to accept, send, and manage money across Africa and globally. The Flutterwave for Business (F4B) v4 API exposes a unified surface for collections (cards, mobile money, bank transfer, USSD, OPay, virtual NUBANs), payouts (bank, mobile money, wallet-to-wallet across 30+ countries), real-time FX conversion, settlements, refunds, chargebacks, multi-currency wallets, KYC, card issuing, and bill payments. Flutterwave is one of the most valuable African fintech companies (unicorn status) and processes 20M+ API calls and 500k+ payments per day.

**Areas:** Payments · Payouts · Mobile Money · Cards · Africa · Fintech · Remittances · Virtual Accounts · Chargebacks · Multi-Currency

## Flutterwave on APIs.io

Everything profiled for Flutterwave is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/flutterwave/](https://apis.io/providers/flutterwave/)** — or go straight to one of the APIs or properties below.

### APIs (19)

- [Flutterwave Transfers API](https://apis.io/apis/flutterwave/flutterwave-transfers-api/) — Disburse funds globally across bank account transfers, mobile money transfers, and wallet-to-wallet transfers spanning 30+ African countries plus…
- [Flutterwave Settlements API](https://apis.io/apis/flutterwave/flutterwave-settlements-api/) — Reconcile transaction volume with merchant payouts. Manage settlements, refunds, chargebacks (dispute handling), and fee computation for cards, mobile…
- [Flutterwave Wallets API](https://apis.io/apis/flutterwave/flutterwave-wallets-api/) — Inspect multi-currency wallet balances, retrieve wallet statements, and resolve mobile money wallet account details. Backs the FAAS (Finance as a Service)…
- [Flutterwave Banks API](https://apis.io/apis/flutterwave/flutterwave-banks-api/) — Reference data for banks, bank branches, and mobile networks supported by country, plus bank account name-enquiry endpoints. Used to populate checkout…
- [Flutterwave Webhooks API](https://apis.io/apis/flutterwave/flutterwave-webhooks-api/) — Outbound webhook callbacks delivered by Flutterwave for charges, transfers, refunds, chargebacks, and virtual account funding. Receivers validate the…
- [Flutterwave Chargebacks API](https://apis.io/apis/flutterwave/flutterwave-chargebacks-api/) — Manage and respond to chargebacks raised by customers.
- [Flutterwave Charges API](https://apis.io/apis/flutterwave/flutterwave-charges-api/) — Create and manage charges across supported payment methods.
- [Flutterwave Customers API](https://apis.io/apis/flutterwave/flutterwave-customers-api/) — Create and manage customers that own charges, orders, and transfers.
- [Flutterwave Fees API](https://apis.io/apis/flutterwave/flutterwave-fees-api/) — Retrieve Flutterwave's fee calculation for a transaction.
- [Flutterwave MobileNetworks API](https://apis.io/apis/flutterwave/flutterwave-mobilenetworks-api/) — Mobile money networks supported by country.
- [Flutterwave Orchestration API](https://apis.io/apis/flutterwave/flutterwave-orchestration-api/) — Orchestrator helpers that combine customer, payment method, and charge in one call.
- [Flutterwave Orders API](https://apis.io/apis/flutterwave/flutterwave-orders-api/) — Server-side cart and order objects backing checkout sessions.
- [Flutterwave Rates API](https://apis.io/apis/flutterwave/flutterwave-rates-api/) — Real-time FX conversion rates for international transfers.
- [Flutterwave Recipients API](https://apis.io/apis/flutterwave/flutterwave-recipients-api/) — Manage transfer recipients (the destination of a payout).
- [Flutterwave Refunds API](https://apis.io/apis/flutterwave/flutterwave-refunds-api/) — Initiate and inspect refunds against successful charges.
- [Flutterwave Senders API](https://apis.io/apis/flutterwave/flutterwave-senders-api/) — Manage transfer senders (the originator of a cross-border payout).
- [Flutterwave Account Resolution API](https://apis.io/apis/flutterwave/flutterwave-account-resolution-api/) — Bank account name resolution before initiating payouts.
- [Flutterwave Payment Methods API](https://apis.io/apis/flutterwave/flutterwave-payment-methods-api/) — Tokenize, register, and look up payment methods (cards, mobile money, bank, USSD).
- [Flutterwave Virtual Accounts API](https://apis.io/apis/flutterwave/flutterwave-virtual-accounts-api/) — Issue virtual NUBANs for pay-with-bank-transfer collections.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (20)

Multi-step workflows that chain operations into a business task.

- [Flutterwave Bank Directory Then Payout](https://apis.io/arazzos/flutterwave/flutterwave-bank-directory-then-payout-workflow/)
- [Flutterwave Charge And Verify Status](https://apis.io/arazzos/flutterwave/flutterwave-charge-and-verify-status-workflow/)
- [Flutterwave Charge Then Dispute Chargeback](https://apis.io/arazzos/flutterwave/flutterwave-charge-then-dispute-chargeback-workflow/)
- [Flutterwave Charge Then Refund](https://apis.io/arazzos/flutterwave/flutterwave-charge-then-refund-workflow/)
- [Flutterwave Create Recipient Transfer And Verify](https://apis.io/arazzos/flutterwave/flutterwave-create-recipient-transfer-verify-workflow/)
- [Flutterwave Cross-Border Rate-Locked Transfer](https://apis.io/arazzos/flutterwave/flutterwave-cross-border-rate-locked-transfer-workflow/)
- [Flutterwave Direct Orchestrator Transfer And Verify](https://apis.io/arazzos/flutterwave/flutterwave-direct-orchestrator-transfer-verify-workflow/)
- [Flutterwave Mobile Money Payout](https://apis.io/arazzos/flutterwave/flutterwave-mobile-money-payout-workflow/)
- [Flutterwave Orchestrator Charge And Verify](https://apis.io/arazzos/flutterwave/flutterwave-orchestrator-charge-and-verify-workflow/)
- [Flutterwave Orchestrator Order And Verify](https://apis.io/arazzos/flutterwave/flutterwave-orchestrator-order-and-verify-workflow/)
- [Flutterwave Order Checkout And Verify](https://apis.io/arazzos/flutterwave/flutterwave-order-checkout-and-verify-workflow/)
- [Flutterwave Quote Fee Then Charge](https://apis.io/arazzos/flutterwave/flutterwave-quote-fee-then-charge-workflow/)
- [Flutterwave Resolve Account Then Payout](https://apis.io/arazzos/flutterwave/flutterwave-resolve-account-then-payout-workflow/)
- [Flutterwave Reuse Recipient Payout](https://apis.io/arazzos/flutterwave/flutterwave-reuse-recipient-payout-workflow/)
- [Flutterwave Settlement Reconciliation Refund](https://apis.io/arazzos/flutterwave/flutterwave-settlement-reconciliation-refund-workflow/)
- [Flutterwave Tokenized Recurring Charge](https://apis.io/arazzos/flutterwave/flutterwave-tokenized-recurring-charge-workflow/)
- [Flutterwave Transfer Verify And Retry](https://apis.io/arazzos/flutterwave/flutterwave-transfer-verify-and-retry-workflow/)
- [Flutterwave Upsert Customer And Charge](https://apis.io/arazzos/flutterwave/flutterwave-upsert-customer-and-charge-workflow/)
- [Flutterwave Virtual Account Collection](https://apis.io/arazzos/flutterwave/flutterwave-virtual-account-collection-workflow/)
- [Flutterwave Wallet Balance Guarded Payout](https://apis.io/arazzos/flutterwave/flutterwave-wallet-balance-guarded-payout-workflow/)

#### GraphQL (1)

GraphQL schemas.

- [Flutterwave GraphQL Schema](https://apis.io/graphqls/flutterwave/flutterwave-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Flutterwave Agentic Access](https://apis.io/agentic-access/flutterwave/flutterwave-agentic-access/)

#### JSON Schema (5)

The data models the API reads and writes.

- [Flutterwave Charge](https://apis.io/schemas/flutterwave/flutterwave-charge/)
- [Flutterwave Customer](https://apis.io/schemas/flutterwave/flutterwave-customer/)
- [Flutterwave Settlement](https://apis.io/schemas/flutterwave/flutterwave-settlement/)
- [Flutterwave Transfer](https://apis.io/schemas/flutterwave/flutterwave-transfer/)
- [Flutterwave Wallet Balance](https://apis.io/schemas/flutterwave/flutterwave-wallet/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Flutterwave Charge Structure](https://apis.io/json-structure/flutterwave/flutterwave-charge-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Flutterwave Context](https://apis.io/jsonld/flutterwave/flutterwave-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Flutterwave Vocabulary](https://apis.io/vocabularies/flutterwave/flutterwave-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Flutterwave Charge Completed Webhook Example](https://apis.io/examples/flutterwave/flutterwave-charge-completed-webhook-example/)
- [Flutterwave Create Charge Example](https://apis.io/examples/flutterwave/flutterwave-create-charge-example/)
- [Flutterwave Create Customer Example](https://apis.io/examples/flutterwave/flutterwave-create-customer-example/)
- [Flutterwave Create Refund Example](https://apis.io/examples/flutterwave/flutterwave-create-refund-example/)
- [Flutterwave Create Transfer Example](https://apis.io/examples/flutterwave/flutterwave-create-transfer-example/)

#### Collections (26)

Postman and Open Collection request collections.

- [Flutterwave Banks AccountResolution API](https://apis.io/collections/flutterwave/open-flutterwave-accountresolution-api/)
- [Flutterwave AccountResolution Banks API](https://apis.io/collections/flutterwave/open-flutterwave-banks-api/)
- [Flutterwave Banks AccountResolution Chargebacks API](https://apis.io/collections/flutterwave/open-flutterwave-chargebacks-api/)
- [Flutterwave Banks AccountResolution Charges API](https://apis.io/collections/flutterwave/open-flutterwave-charges-api/)
- [Flutterwave Banks AccountResolution Customers API](https://apis.io/collections/flutterwave/open-flutterwave-customers-api/)
- [Flutterwave Banks AccountResolution Fees API](https://apis.io/collections/flutterwave/open-flutterwave-fees-api/)
- [Flutterwave Banks AccountResolution MobileNetworks API](https://apis.io/collections/flutterwave/open-flutterwave-mobilenetworks-api/)
- [Flutterwave Banks AccountResolution Orchestration API](https://apis.io/collections/flutterwave/open-flutterwave-orchestration-api/)
- [Flutterwave Banks AccountResolution Orders API](https://apis.io/collections/flutterwave/open-flutterwave-orders-api/)
- [Flutterwave Banks AccountResolution PaymentMethods API](https://apis.io/collections/flutterwave/open-flutterwave-paymentmethods-api/)
- [Flutterwave Payments API](https://apis.io/collections/flutterwave/open-flutterwave-payments-api/)
- [Flutterwave Banks AccountResolution Rates API](https://apis.io/collections/flutterwave/open-flutterwave-rates-api/)
- [Flutterwave Banks AccountResolution Recipients API](https://apis.io/collections/flutterwave/open-flutterwave-recipients-api/)
- [Flutterwave Banks AccountResolution Refunds API](https://apis.io/collections/flutterwave/open-flutterwave-refunds-api/)
- [Flutterwave Banks AccountResolution Senders API](https://apis.io/collections/flutterwave/open-flutterwave-senders-api/)
- [Flutterwave Banks AccountResolution Settlements API](https://apis.io/collections/flutterwave/open-flutterwave-settlements-api/)
- [Flutterwave Banks AccountResolution Transfers API](https://apis.io/collections/flutterwave/open-flutterwave-transfers-api/)
- [Flutterwave Banks AccountResolution VirtualAccounts API](https://apis.io/collections/flutterwave/open-flutterwave-virtualaccounts-api/)
- [Flutterwave Banks AccountResolution Wallets API](https://apis.io/collections/flutterwave/open-flutterwave-wallets-api/)
- [Flutterwave Banks AccountResolution Webhooks API](https://apis.io/collections/flutterwave/open-flutterwave-webhooks-api/)
- [Flutterwave Banks API](https://apis.io/collections/flutterwave/postman-flutterwave-banks-api/)
- [Flutterwave Payments API](https://apis.io/collections/flutterwave/postman-flutterwave-payments-api/)
- [Flutterwave Settlements API](https://apis.io/collections/flutterwave/postman-flutterwave-settlements-api/)
- [Flutterwave Transfers API](https://apis.io/collections/flutterwave/postman-flutterwave-transfers-api/)
- [Flutterwave Wallets API](https://apis.io/collections/flutterwave/postman-flutterwave-wallets-api/)
- …and 1 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Flutterwave — jsonschema rules](https://apis.io/rules/flutterwave/flutterwave-jsonschema-spectral-rules/)
- [Flutterwave API Rules](https://apis.io/rules/flutterwave/flutterwave-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Flutterwave Authentication](https://apis.io/security/flutterwave/flutterwave-authentication/)
- [Flutterwave Domain Security](https://apis.io/security/flutterwave/flutterwave-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Flutterwave Scopes](https://apis.io/scopes/flutterwave/flutterwave-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Flutterwave Plans Pricing](https://apis.io/plans/flutterwave/flutterwave-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Flutterwave Rate Limits](https://apis.io/rate-limits/flutterwave/flutterwave-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Flutterwave Finops](https://apis.io/finops/flutterwave/flutterwave-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.flutterwave.com/)
- [Documentation](https://developer.flutterwave.com/docs)
- [Getting started](https://developer.flutterwave.com/docs/getting-started.md)
- [Pricing](https://flutterwave.com/us/pricing)
- [Support](https://support.flutterwave.com)
- [Blog](https://flutterwave.com/us/blog)
- [Terms of service](https://flutterwave.com/us/terms)
- [Privacy policy](https://flutterwave.com/us/privacy-notice)
- [GitHub](https://github.com/Flutterwave)
- [Status](https://status.flutterwave.com)

## API Evangelist rating

**Kin Score 54.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 58.9 |
| Contract governance | 27.3 |
| Operational transparency | 21.1 |
| Developer ergonomics | 67.9 |
| Access clarity | 60.5 |

**Agent readiness 33.4** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | verified |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | documented (partial credit) |
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
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 31.3** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/flutterwave/](https://apis.io/providers/flutterwave/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Flutterwave: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/flutterwave/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
