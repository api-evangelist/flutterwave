# Flutterwave (flutterwave)

Flutterwave is a pan-African payment infrastructure company providing the rails for businesses to accept, send, and manage money across Africa and globally. The Flutterwave for Business (F4B) v4 API exposes a unified surface for collections (cards, mobile money, bank transfer, USSD, OPay, virtual NUBANs), payouts (bank, mobile money, wallet-to-wallet across 30+ countries), real-time FX conversion, settlements, refunds, chargebacks, multi-currency wallets, KYC, card issuing, and bill payments. Flutterwave is one of the most valuable African fintech companies (unicorn status) and processes 20M+ API calls and 500k+ payments per day.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flutterwave/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flutterwave/refs/heads/main/apis.yml)

## Scope

- **Position:** Producing
- **Access:** 3rd-Party

## Tags

- Payments
- Payouts
- Mobile Money
- Cards
- Africa
- Fintech
- Remittance
- Virtual Accounts
- Chargebacks
- Multi-Currency

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-30

## APIs

### Flutterwave Payments API

Collect payments across cards, mobile money (M-Pesa, MTN, Airtel, Tigo), bank transfers, USSD, OPay, and virtual NUBANs. Includes customers, charges, payment methods, orchestrator helpers, orders, and virtual accounts. The primary surface for accepting money on Flutterwave.

- **Human URL:** [https://developer.flutterwave.com/reference](https://developer.flutterwave.com/reference)
- **Base URL:** `https://api.flutterwave.cloud/f4b/production`

#### Tags

- Payments
- Charges
- Customers
- Orders
- Virtual Accounts
- Cards
- Mobile Money

#### Properties

- [Documentation](https://developer.flutterwave.com/docs/introduction-1.md)
- [Documentation](https://developer.flutterwave.com/reference/charges_post.md)
- [OpenAPI](openapi/flutterwave-payments-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flutterwave-payments-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flutterwave-payments-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flutterwave-charge-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flutterwave-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/flutterwave-charge-structure.json)
- [JSON-LD](json-ld/flutterwave-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/flutterwave-create-charge-example.json)
- [Example](examples/flutterwave-create-customer-example.json)

### Flutterwave Transfers API

Disburse funds globally across bank account transfers, mobile money transfers, and wallet-to-wallet transfers spanning 30+ African countries plus US/UK/EU/Asia corridors. Manage transfer recipients, transfer senders (KYC for cross-border), and real-time FX conversion via the Rates endpoints.

- **Human URL:** [https://developer.flutterwave.com/docs/introduction-3.md](https://developer.flutterwave.com/docs/introduction-3.md)
- **Base URL:** `https://api.flutterwave.cloud/f4b/production`

#### Tags

- Payouts
- Transfers
- Remittance
- FX
- Cross-Border
- Mobile Money

#### Properties

- [Documentation](https://developer.flutterwave.com/docs/introduction-3.md)
- [Documentation](https://developer.flutterwave.com/reference/transfers_post.md)
- [OpenAPI](openapi/flutterwave-transfers-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flutterwave-transfers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flutterwave-transfers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flutterwave-transfer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/flutterwave-create-transfer-example.json)

### Flutterwave Settlements API

Reconcile transaction volume with merchant payouts. Manage settlements, refunds, chargebacks (dispute handling), and fee computation for cards, mobile money, and other rails. The finance-and-ops surface of the F4B platform.

- **Human URL:** [https://developer.flutterwave.com/docs/settlements.md](https://developer.flutterwave.com/docs/settlements.md)
- **Base URL:** `https://api.flutterwave.cloud/f4b/production`

#### Tags

- Settlements
- Refunds
- Chargebacks
- Disputes
- Fees
- Reconciliation

#### Properties

- [Documentation](https://developer.flutterwave.com/docs/settlements.md)
- [Documentation](https://developer.flutterwave.com/docs/refunds.md)
- [Documentation](https://developer.flutterwave.com/docs/chargebacks-1.md)
- [OpenAPI](openapi/flutterwave-settlements-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flutterwave-settlements-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flutterwave-settlements-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flutterwave-settlement-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/flutterwave-create-refund-example.json)

### Flutterwave Wallets API

Inspect multi-currency wallet balances, retrieve wallet statements, and resolve mobile money wallet account details. Backs the FAAS (Finance as a Service) and capital flows for merchants holding balances in NGN, USD, EUR, GBP, KES, GHS, ZAR, UGX, TZS, RWF, XAF, XOF and other supported currencies.

- **Human URL:** [https://developer.flutterwave.com/reference/fetch_wallet_balances.md](https://developer.flutterwave.com/reference/fetch_wallet_balances.md)
- **Base URL:** `https://api.flutterwave.cloud/f4b/production`

#### Tags

- Wallets
- Balances
- Statements
- Multi-Currency

#### Properties

- [Documentation](https://developer.flutterwave.com/reference/fetch_wallet_balances.md)
- [Documentation](https://developer.flutterwave.com/reference/get_wallet_statement.md)
- [Documentation](https://developer.flutterwave.com/reference/wallet_account_resolve_post.md)
- [OpenAPI](openapi/flutterwave-wallets-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flutterwave-wallets-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flutterwave-wallets-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flutterwave-wallet-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Flutterwave Banks API

Reference data for banks, bank branches, and mobile networks supported by country, plus bank account name-enquiry endpoints. Used to populate checkout dropdowns and validate destination accounts before initiating payouts.

- **Human URL:** [https://developer.flutterwave.com/reference/banks_get.md](https://developer.flutterwave.com/reference/banks_get.md)
- **Base URL:** `https://api.flutterwave.cloud/f4b/production`

#### Tags

- Banks
- Reference Data
- Mobile Networks
- Account Resolution

#### Properties

- [Documentation](https://developer.flutterwave.com/reference/banks_get.md)
- [Documentation](https://developer.flutterwave.com/reference/mobile_networks_get.md)
- [Documentation](https://developer.flutterwave.com/reference/bank_account_resolve_post.md)
- [OpenAPI](openapi/flutterwave-banks-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flutterwave-banks-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flutterwave-banks-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flutterwave Webhooks API

Outbound webhook callbacks delivered by Flutterwave for charges, transfers, refunds, chargebacks, and virtual account funding. Receivers validate the `verif-hash` header against the merchant's configured secret hash before trusting the payload.

- **Human URL:** [https://developer.flutterwave.com/docs/webhooks.md](https://developer.flutterwave.com/docs/webhooks.md)
- **Base URL:** `https://your-webhook-endpoint.example.com`

#### Tags

- Webhooks
- Events
- Asynchronous

#### Properties

- [Documentation](https://developer.flutterwave.com/docs/webhooks.md)
- [OpenAPI](openapi/flutterwave-webhooks-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flutterwave-webhooks-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flutterwave-webhooks-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Example](examples/flutterwave-charge-completed-webhook-example.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://flutterwave.com)
- [Portal](https://developer.flutterwave.com)
- [Documentation](https://developer.flutterwave.com/docs)
- [Documentation](https://developer.flutterwave.com/reference)
- [Documentation](https://developer.flutterwave.com/llms.txt)
- [Getting Started](https://developer.flutterwave.com/docs/getting-started.md)
- [Documentation](https://developer.flutterwave.com/docs/authentication.md)
- [Documentation](https://developer.flutterwave.com/docs/api-headers.md)
- [Documentation](https://developer.flutterwave.com/docs/encryption.md)
- [Errors](https://developer.flutterwave.com/docs/common-errors.md)
- [Documentation](https://developer.flutterwave.com/docs/webhooks.md)
- [Documentation](https://developer.flutterwave.com/docs/idempotency.md)
- [Documentation](https://developer.flutterwave.com/docs/testing.md)
- [Documentation](https://developer.flutterwave.com/docs/best-practices.md)
- [Documentation](https://developer.flutterwave.com/docs/environments.md)
- [Sign Up](https://onboarding.flutterwave.com/signup)
- [Status Page](https://status.flutterwave.com)
- [Support](https://support.flutterwave.com)
- [Pricing](https://flutterwave.com/us/pricing)
- [Blog](https://flutterwave.com/us/blog)
- [Terms of Service](https://flutterwave.com/us/terms)
- [Privacy Policy](https://flutterwave.com/us/privacy-notice)
- [Contact](https://flutterwave.com/us/contact-sales)
- [LinkedIn](https://www.linkedin.com/company/flutterwave)
- [Twitter](https://twitter.com/theflutterwave)
- [GitHub Organization](https://github.com/Flutterwave)
- [SDK](https://github.com/Flutterwave/Node-v3)
- [SDK](https://github.com/Flutterwave/PHP-v3)
- [SDK](https://github.com/Flutterwave/Python-v2)
- [SDK](https://github.com/Flutterwave/Ruby-v3)
- [SDK](https://github.com/Flutterwave/Java-v3)
- [SDK](https://github.com/Flutterwave/Dotnet-v2)
- [SDK](https://github.com/Flutterwave/React-v3)
- [SDK](https://github.com/Flutterwave/Angular-v3)
- [SDK](https://github.com/Flutterwave/Vue-v3)
- [SDK](https://github.com/Flutterwave/Flutter-v3)
- [SDK](https://github.com/Flutterwave/React-Native)
- [SDK](https://github.com/Flutterwave/AndroidSDK)
- [SDK](https://github.com/Flutterwave/iOS-v3)
- [Plugin](https://github.com/Flutterwave/WordPress-v2)
- [Plans](plans/flutterwave-plans-pricing.yml)
- [Rate Limits](rate-limits/flutterwave-rate-limits.yml)
- [Fin Ops](finops/flutterwave-finops.yml)
- [Spectral Rules](rules/flutterwave-rules.yml)
- [Vocabulary](vocabulary/flutterwave-vocabulary.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
