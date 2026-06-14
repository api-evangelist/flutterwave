# Flutterwave GraphQL Schema

## Overview

This document describes a GraphQL schema representation of the Flutterwave Payments API. Flutterwave's native interface is REST-based; this schema is a conceptual mapping of core domain types to GraphQL for tooling, documentation, and integration purposes.

## Domain Coverage

The schema covers the following Flutterwave domains:

- **Payments & Charges** — CardCharge, BankTransfer, MobileMoneyCharge, USSD, QRCode, Transaction, RecurringPayment
- **Plans & Subscriptions** — Plan, Subscription
- **Transfers & Disbursements** — Transfer, BulkTransfer, Beneficiary, PayoutConfiguration, Disbursement
- **Refunds & Webhooks** — Refund, Webhook
- **Verification & KYC** — AccountVerification, BVNVerification, CardNumber
- **Customers** — Customer
- **Cards** — VirtualCard
- **Accounts** — VirtualAccount, SubAccount
- **Settlements** — Settlement
- **Bills & Utilities** — Bill, Airtime, DataBundle, Electricity
- **Commerce** — Invoice, PaymentLink, SplitPayment
- **Auditing** — Audit
- **Reference Data** — Bank

## Schema File

See [`flutterwave-schema.graphql`](./flutterwave-schema.graphql) for the full type definitions.

## Key Types

| Type | Description |
|------|-------------|
| `Transaction` | Core record for any completed payment event |
| `Charge` | Generic charge object linking to specific charge method types |
| `CardCharge` | Card-specific charge including card metadata and auth model |
| `BankTransfer` | Bank transfer collection via virtual account or direct transfer |
| `MobileMoneyCharge` | Mobile money charge (M-Pesa, MTN, Airtel, Tigo, OPay) |
| `USSD` | USSD-initiated payment with phone and bank code |
| `QRCode` | QR-initiated payment with rendered image URL |
| `RecurringPayment` | Tokenized recurring charge against a saved payment method |
| `Plan` | Subscription billing plan (amount, interval, currency) |
| `Subscription` | Customer enrollment on a Plan |
| `Webhook` | Outbound event callback with signature verification |
| `Refund` | Refund issued against a settled Transaction |
| `Transfer` | Single payout to a bank account or mobile money wallet |
| `BulkTransfer` | Batch of Transfer objects dispatched together |
| `Bank` | Reference bank record (code, name, country) |
| `AccountVerification` | Bank account name-enquiry result |
| `BVNVerification` | BVN identity lookup result |
| `CardNumber` | Tokenized card reference (last four, brand, expiry) |
| `Customer` | Merchant customer record (email, name, phone, metadata) |
| `Beneficiary` | Saved payout destination for a Customer |
| `VirtualCard` | Issued virtual card with balance and limits |
| `VirtualAccount` | Dedicated NUBAN or mobile money collection account |
| `Settlement` | Merchant settlement batch with fees, net amount, and payout date |
| `SubAccount` | Split-payment sub-merchant account |
| `PayoutConfiguration` | Default payout rules for an account |
| `Disbursement` | Tracked mass-payout disbursement record |
| `Bill` | Bill payment record (cable, internet, betting) |
| `Airtime` | Airtime top-up record |
| `DataBundle` | Mobile data bundle purchase record |
| `Electricity` | Electricity token purchase record |
| `Invoice` | Merchant-issued invoice with line items |
| `PaymentLink` | Hosted checkout payment link |
| `SplitPayment` | Split payment configuration across sub-accounts |
| `Audit` | Audit log entry for account activity |

## Source

- Flutterwave Developer Portal: https://developer.flutterwave.com/docs
- Flutterwave API Reference: https://developer.flutterwave.com/reference
