# Flutterwave (flutterwave)

Flutterwave is a pan-African payment infrastructure company providing the rails for businesses to accept, send, and manage money across Africa and globally. The Flutterwave for Business (F4B) v4 API exposes a unified surface for collections (cards, mobile money, bank transfer, USSD, OPay, virtual NUBANs), payouts (bank, mobile money, wallet-to-wallet across 30+ countries), real-time FX conversion, settlements, refunds, chargebacks, multi-currency wallets, KYC, card issuing, and bill payments. Flutterwave is one of the most valuable African fintech companies (unicorn status) and processes 20M+ API calls and 500k+ payments per day.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/flutterwave/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Payments, Payouts, Mobile Money, Cards, Africa, Fintech, Remittance, Virtual Accounts, Chargebacks, Multi-Currency

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## Coverage Snapshot

| Surface | Production base URL |
|---|---|
| All v4 APIs | `https://api.flutterwave.cloud/f4b/production` |
| OAuth Token | `https://idp.flutterwave.com/realms/flutterwave/protocol/openid-connect/token` |
| Sandbox | `https://api.flutterwave.cloud/f4b/sandbox` |

| Area | Channels |
|---|---|
| Collections | Card (local + international), Mobile Money (M-Pesa, MTN, Airtel, Vodafone, Tigo), Bank Transfer (Virtual NUBAN), USSD, OPay, QR |
| Payouts | Bank Account, Mobile Money, Wallet-to-Wallet, Cross-Border with FX |
| Geography | Nigeria, Ghana, Kenya, Uganda, Tanzania, Rwanda, Cameroon, Senegal, Ivory Coast, South Africa, Zambia, Malawi, Mauritius, Egypt + UK, US, EU corridors |
| Currencies | NGN, USD, EUR, GBP, KES, GHS, ZAR, UGX, TZS, RWF, XAF, XOF, MWK, MUR and 15+ more |

## APIs

### Flutterwave Payments API
Collect payments across cards, mobile money, bank transfers, USSD, OPay, and virtual NUBANs. Customers, charges, payment methods, orchestrator helpers, orders, and virtual accounts.

**Human URL:** [https://developer.flutterwave.com/reference](https://developer.flutterwave.com/reference)

- [Documentation — Payments Intro](https://developer.flutterwave.com/docs/introduction-1.md)
- [Documentation — Create A Charge](https://developer.flutterwave.com/reference/charges_post.md)
- [OpenAPI](openapi/flutterwave-payments-api-openapi.yml)
- [Naftiko Capability — Customers](capabilities/payments-customers.yaml)
- [Naftiko Capability — Charges](capabilities/payments-charges.yaml)
- [Naftiko Capability — Payment Methods](capabilities/payments-payment-methods.yaml)
- [Naftiko Capability — Orders](capabilities/payments-orders.yaml)
- [Naftiko Capability — Virtual Accounts](capabilities/payments-virtual-accounts.yaml)
- [JSON Schema — Charge](json-schema/flutterwave-charge-schema.json)
- [JSON Schema — Customer](json-schema/flutterwave-customer-schema.json)
- [JSON Structure — Charge](json-structure/flutterwave-charge-structure.json)
- [JSON-LD](json-ld/flutterwave-context.jsonld)
- [Example — Create Customer](examples/flutterwave-create-customer-example.json)
- [Example — Create Charge](examples/flutterwave-create-charge-example.json)

### Flutterwave Transfers API
Disburse funds globally across bank, mobile money, and wallet-to-wallet rails spanning 30+ African countries. Manage transfer recipients, transfer senders (KYC for cross-border), and real-time FX conversion.

**Human URL:** [https://developer.flutterwave.com/docs/introduction-3.md](https://developer.flutterwave.com/docs/introduction-3.md)

- [Documentation — Transfers Intro](https://developer.flutterwave.com/docs/introduction-3.md)
- [OpenAPI](openapi/flutterwave-transfers-api-openapi.yml)
- [Naftiko Capability — Transfers](capabilities/transfers-transfers.yaml)
- [Naftiko Capability — Recipients](capabilities/transfers-recipients.yaml)
- [Naftiko Capability — Senders](capabilities/transfers-senders.yaml)
- [Naftiko Capability — Rates](capabilities/transfers-rates.yaml)
- [JSON Schema — Transfer](json-schema/flutterwave-transfer-schema.json)
- [Example — Create Transfer](examples/flutterwave-create-transfer-example.json)

### Flutterwave Settlements API
Reconcile transaction volume with merchant payouts. Settlements, refunds, chargebacks, and fee computation for cards, mobile money, and other rails.

**Human URL:** [https://developer.flutterwave.com/docs/settlements.md](https://developer.flutterwave.com/docs/settlements.md)

- [Documentation — Settlements](https://developer.flutterwave.com/docs/settlements.md)
- [Documentation — Refunds](https://developer.flutterwave.com/docs/refunds.md)
- [Documentation — Chargebacks](https://developer.flutterwave.com/docs/chargebacks-1.md)
- [OpenAPI](openapi/flutterwave-settlements-api-openapi.yml)
- [Naftiko Capability — Settlements](capabilities/settlements-settlements.yaml)
- [Naftiko Capability — Refunds](capabilities/settlements-refunds.yaml)
- [Naftiko Capability — Chargebacks](capabilities/settlements-chargebacks.yaml)
- [Naftiko Capability — Fees](capabilities/settlements-fees.yaml)
- [JSON Schema — Settlement](json-schema/flutterwave-settlement-schema.json)
- [Example — Create Refund](examples/flutterwave-create-refund-example.json)

### Flutterwave Wallets API
Inspect multi-currency wallet balances, retrieve wallet statements, and resolve mobile money wallet account details. Backs FAAS (Finance as a Service) for merchants holding balances across 30+ currencies.

**Human URL:** [https://developer.flutterwave.com/reference/fetch_wallet_balances.md](https://developer.flutterwave.com/reference/fetch_wallet_balances.md)

- [Documentation — Wallet Balances](https://developer.flutterwave.com/reference/fetch_wallet_balances.md)
- [Documentation — Wallet Statement](https://developer.flutterwave.com/reference/get_wallet_statement.md)
- [OpenAPI](openapi/flutterwave-wallets-api-openapi.yml)
- [Naftiko Capability — Wallets](capabilities/wallets-wallets.yaml)
- [Naftiko Capability — Account Resolution](capabilities/wallets-account-resolution.yaml)
- [JSON Schema — Wallet Balance](json-schema/flutterwave-wallet-schema.json)

### Flutterwave Banks API
Reference data for banks, bank branches, and mobile networks supported by country, plus bank account name-enquiry endpoints.

**Human URL:** [https://developer.flutterwave.com/reference/banks_get.md](https://developer.flutterwave.com/reference/banks_get.md)

- [OpenAPI](openapi/flutterwave-banks-api-openapi.yml)
- [Naftiko Capability — Banks](capabilities/banks-banks.yaml)
- [Naftiko Capability — Mobile Networks](capabilities/banks-mobile-networks.yaml)
- [Naftiko Capability — Account Resolution](capabilities/banks-account-resolution.yaml)

### Flutterwave Webhooks API
Outbound webhook callbacks for charges, transfers, refunds, chargebacks, and virtual account funding. Receivers must validate the `verif-hash` header against the merchant's configured secret.

**Human URL:** [https://developer.flutterwave.com/docs/webhooks.md](https://developer.flutterwave.com/docs/webhooks.md)

- [Documentation](https://developer.flutterwave.com/docs/webhooks.md)
- [OpenAPI](openapi/flutterwave-webhooks-api-openapi.yml)
- [Example — charge.completed](examples/flutterwave-charge-completed-webhook-example.json)

## SDKs

| Stack | Repo |
|---|---|
| Node.js (v3) | [Flutterwave/Node-v3](https://github.com/Flutterwave/Node-v3) |
| PHP (v3) | [Flutterwave/PHP-v3](https://github.com/Flutterwave/PHP-v3) |
| Python (v2) | [Flutterwave/Python-v2](https://github.com/Flutterwave/Python-v2) |
| Ruby (v3) | [Flutterwave/Ruby-v3](https://github.com/Flutterwave/Ruby-v3) |
| Java (v3) | [Flutterwave/Java-v3](https://github.com/Flutterwave/Java-v3) |
| .NET (v2) | [Flutterwave/Dotnet-v2](https://github.com/Flutterwave/Dotnet-v2) |
| React (v3) | [Flutterwave/React-v3](https://github.com/Flutterwave/React-v3) |
| Angular (v3) | [Flutterwave/Angular-v3](https://github.com/Flutterwave/Angular-v3) |
| Vue.js (v3) | [Flutterwave/Vue-v3](https://github.com/Flutterwave/Vue-v3) |
| Flutter (v3) | [Flutterwave/Flutter-v3](https://github.com/Flutterwave/Flutter-v3) |
| React Native | [Flutterwave/React-Native](https://github.com/Flutterwave/React-Native) |
| Android | [Flutterwave/AndroidSDK](https://github.com/Flutterwave/AndroidSDK) |
| iOS (v3) | [Flutterwave/iOS-v3](https://github.com/Flutterwave/iOS-v3) |
| WordPress | [Flutterwave/WordPress-v2](https://github.com/Flutterwave/WordPress-v2) |

## Commercial & Operational

- [Pricing](https://flutterwave.com/us/pricing) — see [plans/flutterwave-plans-pricing.yml](plans/flutterwave-plans-pricing.yml)
- [Rate Limits guidance](rate-limits/flutterwave-rate-limits.yml)
- [FinOps model](finops/flutterwave-finops.yml)
- [Status](https://status.flutterwave.com)
- [Support](https://support.flutterwave.com)
- [Sign Up](https://onboarding.flutterwave.com/signup)
- [Terms](https://flutterwave.com/us/terms) · [Privacy](https://flutterwave.com/us/privacy-notice)

## Authentication

OAuth 2.0 Client Credentials. POST to `https://idp.flutterwave.com/realms/flutterwave/protocol/openid-connect/token` with `client_id`, `client_secret`, `grant_type=client_credentials`. Bearer tokens are valid for 10 minutes; refresh at least 60 seconds before expiry. Include `Authorization: Bearer {{ACCESS_TOKEN}}` on every API call.

Sensitive card data (PAN, expiry, CVV) must be encrypted client-side with AES-256 plus a 12-character nonce before being sent in `payment_method.card`. Official SDKs handle this transparently.

## Idempotency

All POST endpoints accept `X-Idempotency-Key` (UUID). Retried requests return the original response with `X-Idempotency-Cache-Hit: true`.

## Vocabulary & Rules

- [Vocabulary](vocabulary/flutterwave-vocabulary.yml) — concepts, payment rails, payout rails, geographies
- [Spectral Rules](rules/flutterwave-rules.yml) — Flutterwave-specific OpenAPI conventions
