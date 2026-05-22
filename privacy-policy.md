# Privacy Policy — Quota

**Effective date:** 2026-05-17

This Privacy Policy explains how Quota ("we", "us", "our") collects, uses, and shares information when you use our mobile application. By using Quota you agree to the practices described here.

---

## 1. Who we are

Quota is operated as an independent service. For privacy questions, contact **snogard2014@gmail.com**.

## 2. Information we collect

### 2.1 Information you give us

- **Account information.** Email address; optional full name; optional avatar image.
- **Financial data.** Transactions (amount, date, category, description), budgets, recurring subscriptions, savings goals, and any transaction notes you record.
- **Receipt images.** When you use the receipt-scanning feature, the photograph is uploaded to our processing pipeline.
- **App-lock PIN.** If you set one, we store only an irreversible hash on your device.

### 2.2 Information we generate

- **Insights and summaries** computed over your transactions.
- **Subscription / entitlement state** indicating whether you are on a free, trial, or paid plan.
- **Native crash reports** collected by Apple (iOS) and Google (Android) when the operating system terminates the app unexpectedly. We do not run a third-party error-reporting SDK inside the app; the only diagnostic data we receive is whatever the platform vendors expose to developers through Xcode Organizer and Google Play Console → Android Vitals.

### 2.3 Information we do NOT collect

- We do not connect to your bank or store any banking credentials, card numbers, or account numbers.
- We do not collect precise location data.
- We do not collect contacts, calendar entries, or your photo library beyond a single camera capture for receipts.

## 3. How we use information

- **Provide the service.** Show your transactions, generate insights, manage your subscription.
- **Receipt parsing.** Send receipt images to our AI provider (Anthropic) to extract structured data.
- **Quality and reliability.** Identify crashes via the platform-native crash reporters provided by Apple and Google so we can fix them. We do not record session replays.
- **Account management.** Authenticate you, enforce your plan, comply with legal obligations.

## 4. Legal basis (GDPR)

| Purpose | Legal basis |
|---|---|
| Operating the app | Contract — Art. 6(1)(b) |
| Receipt OCR | Consent — Art. 6(1)(a); granted by enabling AI features |
| Anonymous analytics | Consent — Art. 6(1)(a); off by default |
| Account deletion / regulatory | Legal obligation — Art. 6(1)(c) |

## 5. Sub-processors

We share information with the following processors:

| Processor | Purpose | Region | Notes |
|---|---|---|---|
| Supabase | Authentication, database, file storage, server-side functions | EU | Standard DPA |
| RevenueCat | Subscription management | US | Standard DPA |
| Anthropic | Receipt OCR (only when AI features are enabled) | US | Anthropic Commercial Terms |
| Apple | App distribution, in-app purchase processing, and iOS crash reporting (Xcode Organizer) | US | Apple DPA |
| Google | Android distribution, Play in-app purchase processing, and Android crash reporting (Android Vitals) | US | Google DPA |

## 6. International transfers

Personal data may be transferred outside Bulgaria and the EU/EEA, including to the United States. Where the destination is outside the EEA/UK and not subject to an adequacy decision, transfers rely on the European Commission's Standard Contractual Clauses (SCCs) and the UK International Data Transfer Addendum where applicable.

## 7. Retention

| Data | Retention |
|---|---|
| Account and financial data | While your account is active. After deletion: 30-day soft-delete window, then irreversibly purged. |
| Receipt images | Same as account data. |
| Backup files exported by you | We do not retain server copies. |
| Native crash reports (Apple / Google) | Retained by the platform vendor under their own policies; we do not store them on our infrastructure. |
| Subscription events (RevenueCat) | 12 months (vendor default). |
| Audit log of security-relevant events | 7 years (SOC 2 evidence retention). |
| Sign-in event log | 90 days. |

## 8. Your rights

Under the EU General Data Protection Regulation (GDPR) and equivalent national laws, you have the following rights. You can exercise them either in-app where indicated, or by emailing **snogard2014@gmail.com**.

- **Access** — Profile → Export my data returns a machine-readable JSON copy and fulfils your access request.
- **Rectification** — edit your data directly in the app.
- **Erasure** — Profile → Delete account soft-deletes immediately and triggers permanent purge after 30 days. You can cancel during that window by signing back in.
- **Restriction / objection** — toggles in Profile → Privacy preferences.
- **Portability** — the export is in standard JSON.
- **Withdraw consent** — at any time for AI features and analytics.
- **Lodge a complaint** — with the Bulgarian **Commission for Personal Data Protection** (CPDP, [www.cpdp.bg](https://www.cpdp.bg/)) or the supervisory authority in your country of residence.

We respond to verified rights requests within **30 days** (up to 45 in complex cases, with notice). To prevent account takeover, we verify identity before fulfilling requests received outside the in-app export.

## 9. Security

- Row-Level Security on every owner-scoped database table.
- Authentication tokens stored in iOS Keychain or Android Keystore.
- App-lock PINs hashed with PBKDF2-SHA256, 600 000 iterations.
- Backups exported from the app can be optionally AES-256-GCM encrypted with a passphrase you choose.
- We do not store payment-card information.

## 10. Children

Quota is not directed at users under **16**, and we do not knowingly collect their data. If you are under 16, please do not use the Service. If you believe a child has provided us with personal data, contact **snogard2014@gmail.com** and we will delete it.

## 11. Changes to this policy

We will post an in-app notice and update the "Effective date" above when we make material changes. Continued use after a change constitutes acceptance.

## 12. Contact

**snogard2014@gmail.com** for any privacy question, complaint, or rights request.
