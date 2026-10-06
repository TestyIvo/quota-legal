# Privacy Policy — Quota

**Effective date:** 2026-10-06

This Privacy Policy explains how Quota ("we", "us", "our") collects, uses, and shares information when you use our mobile application. Please read it to understand how your data is handled.

---

## 1. Who we are

Quota is operated as an independent service. For privacy questions, contact **snogard2014@gmail.com**.

## 2. Information we collect

### 2.1 Information you give us

- **Account information.** Email address; optional full name; optional profile picture.
- **Financial data.** Transactions (amount, date, category, description), budgets and their monthly limits, recurring payments, savings goals and their history, and quick actions you save.
- **Preferences.** Your currency, theme, tab layout, notification settings, custom categories, and your answer to the AI receipt-scanning question, stored with your account so they follow you to another device.
- **Receipt images.** When you scan a receipt, the photo is sent to our server and on to our AI provider to read it. We do not store the photo.
- **Profile picture.** If you add one, it is resized to 512 × 512 pixels and stored with your account. It is kept at an address that includes your account's random identifier; anyone who has that exact address can view the picture, but the pictures cannot be listed or searched.
- **App-lock PIN.** If you set one, we store only an irreversible hash on your device, and a count of wrong attempts on our server to enforce a lockout.

### 2.2 Information we generate

- **Insights and summaries** computed over your transactions. These are worked out on your device.
- **Subscription / entitlement state** indicating whether you are on a free, trial, or paid plan.
- **Native crash reports** collected by Apple (iOS) and Google (Android) when the operating system terminates the app unexpectedly. We do not run a third-party error-reporting SDK inside the app; the only diagnostic data we receive is whatever the platform vendors expose to developers through Xcode Organizer and Google Play Console → Android Vitals.

### 2.3 Information we do NOT collect

- We do not connect to your bank or store any banking credentials, card numbers, or account numbers.
- We do not collect precise location data.
- We do not collect contacts, calendar entries, or your photo library beyond the single photo you choose for a receipt or a profile picture.
- **Face ID and fingerprints** used for App lock are checked by your phone's operating system; we never receive them.
- **Notifications** (bill reminders, budget alerts, the weekly recap and the logging reminder) are scheduled on your phone. We do not use push notifications or store a device token, and nothing about them is sent to us.
- We do not use analytics, advertising or tracking SDKs.

## 3. How we use information

- **Provide the service.** Show your transactions, generate insights, manage your subscription.
- **Receipt parsing.** Send receipt images to our AI provider (Anthropic) to extract structured data.
- **Quality and reliability.** Identify crashes via the platform-native crash reporters provided by Apple and Google so we can fix them. We do not record session replays.
- **Account management.** Authenticate you, enforce your plan, comply with legal obligations.

## 4. Legal basis (GDPR)

| Purpose | Legal basis |
|---|---|
| Operating the app | Contract — Art. 6(1)(b) |
| Receipt scanning with AI | Consent — Art. 6(1)(a); asked the first time you scan a receipt |
| Account deletion / regulatory | Legal obligation — Art. 6(1)(c) |

## 5. Sub-processors

We share information with the following processors:

| Processor | Purpose | Region | Notes |
|---|---|---|---|
| Supabase | Authentication, database, file storage, server-side functions | Switzerland (Zurich) | Standard DPA |
| RevenueCat | Subscription management | US | Standard DPA |
| Anthropic | Reading receipt photos (only when you scan one, after agreeing) | US | Anthropic Commercial Terms |
| Apple | App distribution, in-app purchase processing, and iOS crash reporting (Xcode Organizer) | US | Apple DPA |
| Google | Android distribution, Play in-app purchase processing, and Android crash reporting (Android Vitals) | US | Google DPA |

## 6. International transfers

Your account and financial data are stored by Supabase in Zurich, Switzerland. The European Commission recognises Switzerland as providing an adequate level of data protection, so this transfer needs no additional safeguards.

Personal data may also be transferred to the United States. Where the destination is outside the EEA/UK and not subject to an adequacy decision, transfers rely on the European Commission's Standard Contractual Clauses (SCCs) and the UK International Data Transfer Addendum where applicable.

## 7. Retention

| Data | Retention |
|---|---|
| Account and financial data | While your account is active. After you delete your account: 24 hours in which you can restore it by signing back in, then permanently deleted. |
| Receipt images | Not stored by us. Photos stored before 2 October 2026 are deleted with your account. |
| Profile picture | While your account is active; deleted with your account, or when you remove it in Profile. |
| Data downloads you make | We do not retain server copies. |
| Native crash reports (Apple / Google) | Retained by the platform vendor under their own policies; we do not store them on our infrastructure. |
| Subscription events (RevenueCat) | 12 months (vendor default). |
| Audit log of security-relevant events | 7 years (SOC 2 evidence retention). |
| Sign-in event log | 90 days. |

## 8. Your rights

Under the EU General Data Protection Regulation (GDPR) and equivalent national laws, you have the following rights. You can exercise them either in-app where indicated, or by emailing **snogard2014@gmail.com**.

- **Access** — Profile → Download my data returns a machine-readable JSON copy, free of charge, and fulfils your access request.
- **Rectification** — edit your data directly in the app. To change your email address, use Profile → Change Email; until the app can send confirmation emails, this sends us a request from your mail app, and we make the change once we have confirmed it came from your current address.
- **Erasure** — Profile → Delete account signs you out on every device and permanently deletes your account and all its data 24 hours later. Until then you can cancel by signing back in and choosing Restore. See also our [account deletion page](./delete-account).
- **Restriction / objection** — email us at the address below.
- **Portability** — the download is in standard JSON.
- **Withdraw consent** — for AI receipt scanning, at any time, by emailing us; we will turn it off for your account, and Quota asks again before your next scan.
- **Lodge a complaint** — with the Bulgarian **Commission for Personal Data Protection** (CPDP, [www.cpdp.bg](https://www.cpdp.bg/)) or the supervisory authority in your country of residence.

We respond to verified rights requests within **30 days** (up to 45 in complex cases, with notice). To prevent account takeover, we verify identity before fulfilling requests received outside the in-app download.

## 9. Security

- Row-Level Security on every owner-scoped database table.
- Authentication tokens stored in iOS Keychain or Android Keystore.
- App-lock PINs hashed with PBKDF2-SHA256, 100 000 iterations. The PIN is a 4-digit code, so the practical protection comes from the hardware-backed keystore and server-side attempt lockout rather than the work factor alone.
- App lock asks for Face ID, a fingerprint or your PIN when you open Quota after a minute or more away.
- Changing your password in the app asks for your phone's lock and your current password, and signs out your other devices.
- Changing your email in the app asks for Face ID or a fingerprint, or your password on a phone without them.
- Data downloads are plain JSON files so you can open them; store them somewhere safe.
- We do not store payment-card information.

## 10. Children

Quota is not directed at users under **16**, and we do not knowingly collect their data. If you are under 16, please do not use the Service. If you believe a child has provided us with personal data, contact **snogard2014@gmail.com** and we will delete it.

## 11. Changes to this policy

When we make material changes, we publish the new version at this address and update the "Effective date" above before it takes effect. The current version is always linked from the app (Profile → Privacy Policy).

## 12. Contact

**snogard2014@gmail.com** for any privacy question, complaint, or rights request.
