# Privacy Policy

**Effective Date:** March 5, 2026
**Last Updated:** March 5, 2026

---

## 1. Introduction

Welcome to **Lazy Traveler** ("the App"), a mobile application developed and operated by **Lazy Traveler Ltd.** ("we", "us", or "our").

This Privacy Policy explains how we collect, use, disclose, and safeguard your personal information when you use our mobile application and related services. By using the App, you agree to the collection and use of information in accordance with this policy.

We are committed to protecting your privacy and complying with applicable data protection laws, including the General Data Protection Regulation (GDPR) and applicable privacy laws in your jurisdiction.

---

## 2. Information We Collect

### 2.1 Information You Provide Directly

- **Account Information:** When you register or log in via Auth0, we collect your email address and profile information (such as name and profile picture) provided through your authentication provider.
- **Social Media Content:** When you share a social media post URL or text content through the App, we process that content to extract travel landmark information on your behalf.

### 2.2 Information We Collect Automatically

- **Usage Data:** We collect information about how you interact with the App, including features used, screens visited, and actions taken.
- **Device Information:** We may collect device type, operating system version, and app version for diagnostic purposes.
- **Log Data:** Our servers automatically record request timestamps, error logs, and performance metrics when you use the App.

### 2.3 Information Derived from Your Content

When you share a social media post URL or text with the App:

- We extract **landmark and place names** mentioned in the content using AI-powered Named Entity Recognition (NER).
- The URL or text you submit is sent to our AI provider (OpenAI or Anthropic) for processing and may be temporarily retained on our servers for up to **7 days** to provide the feature and assist with troubleshooting. Only extracted landmark entities — not the original raw text — are stored beyond that period.
- We enrich extracted landmarks with publicly available geolocation data from OpenStreetMap and Google Places.
- We may fetch publicly available images, descriptions, and metadata (such as opening hours) associated with identified landmarks from third-party sources.

We do **not** store the raw video content of social media posts on our servers.

### 2.4 Data We Do NOT Collect

We want to be explicit about what we do **not** collect:

- **Precise or real-time location:** We do not track your GPS location. Any country or region context displayed in the App is derived from the travel content you voluntarily share, not from device location sensors.
- **Contacts:** We do not access your device contacts.
- **SMS or call logs:** We do not access messages or call history.
- **Camera or microphone:** We do not access your camera or microphone.
- **Financial or payment information:** We do not offer in-app purchases or subscriptions and do not process payment data.
- **Crash analytics via third-party services:** We do not use Firebase Crashlytics, Sentry, or any other third-party analytics or crash reporting SDK. Error information is captured only in our own server logs.

---

## 3. How We Use Your Information

We use the information we collect for the following purposes:

- **To provide and operate the App:** Creating and managing your account, processing your shared content, and delivering the core landmark discovery features.
- **To personalize your experience:** Displaying landmarks relevant to the countries you have visited and your travel history.
- **To improve our services:** Analyzing server-side usage patterns to identify bugs, improve performance, and develop new features.
- **To communicate with you:** Sending service-related notifications, updates, and responding to support inquiries.
- **To ensure security:** Detecting and preventing fraudulent activity, abuse, and unauthorized access.
- **To comply with legal obligations:** Meeting applicable legal, regulatory, and compliance requirements.

We do **not** use your personal data for advertising purposes, and we do **not** sell your data to third parties.

---

## 4. Legal Basis for Processing (GDPR)

If you are located in the European Economic Area (EEA), we process your personal data under the following legal bases:

- **Contractual Necessity:** Processing required to provide the services you have requested (e.g., creating your account, processing shared content).
- **Legitimate Interests:** Improving our services, ensuring security, and preventing fraud — where these interests are not overridden by your rights.
- **Legal Obligation:** Where we are required to process data to comply with applicable law.

---

## 5. How We Share Your Information

We do not sell, rent, or trade your personal information. We may share your data only in the following limited circumstances:

### 5.1 Service Providers

We engage trusted third-party service providers to help us operate the App:

| Provider | Purpose | Data Shared |
|---|---|---|
| **Auth0** | User authentication and identity management | Email, profile data |
| **OpenAI / Anthropic** | AI-powered entity extraction from shared content | URL or text content of shared posts (temporary) |
| **OpenStreetMap / Nominatim** | Geolocation enrichment of landmarks | Place name queries |
| **Google Places API** | Fallback geolocation enrichment | Place name queries |
| **Cloud Hosting Provider** | Infrastructure and data storage | Encrypted data at rest |

We do **not** use Firebase, Google Analytics, Sentry, Mixpanel, or any third-party analytics or crash reporting service. We do **not** offer in-app purchases or subscriptions and therefore use no payment processors.

All service providers are contractually obligated to protect your data and use it only for the specified purpose.

### 5.2 Legal Requirements

We may disclose your information if required to do so by law or in response to valid requests by public authorities (e.g., a court order or government agency).

### 5.3 Business Transfers

In the event of a merger, acquisition, or sale of all or a portion of our assets, your personal information may be transferred as part of that transaction. We will notify you via email and/or a prominent notice in the App before your data is transferred and becomes subject to a different privacy policy.

---

## 6. Data Retention

We retain your personal data for as long as necessary to provide you with the App's services and as required by applicable law.

- **Account data:** Retained for the lifetime of your account. Upon account deletion, your personal data is deleted or anonymized within 30 days, except where retention is required by law.
- **Shared content (URL / text):** Temporarily retained on our servers and with our AI providers for up to **7 days** for feature delivery and troubleshooting, then deleted.
- **Share request data:** Individual share requests expire automatically after **7 days**.
- **Landmark data:** Landmark information enriched from your shared content is retained as part of your travel history until you delete it or your account.
- **Log data:** Server and error logs are retained for up to **90 days** for security and debugging purposes.

---

## 7. Data Security

We implement industry-standard technical and organizational security measures to protect your personal information against unauthorized access, alteration, disclosure, or destruction:

- **Encryption in transit:** All data transmitted between the App and our servers is encrypted using TLS (Transport Layer Security).
- **Encryption at rest:** Personal data stored in our databases is encrypted at rest.
- **Access controls:** Access to personal data is restricted to authorized personnel only, on a need-to-know basis.
- **Authentication:** User accounts are secured via Auth0, which implements OAuth 2.0 and supports multi-factor authentication.
- **Regular reviews:** We conduct periodic security reviews of our systems and infrastructure.

While we take all reasonable precautions, no method of transmission or storage is 100% secure. We cannot guarantee absolute security of your data.

---

## 8. Your Rights

Depending on your location, you may have the following rights regarding your personal data:

- **Right of Access:** You have the right to request a copy of the personal data we hold about you.
- **Right to Rectification:** You have the right to request correction of inaccurate or incomplete personal data.
- **Right to Erasure ("Right to be Forgotten"):** You have the right to request deletion of your personal data, subject to certain legal exceptions.
- **Right to Restrict Processing:** You have the right to request that we limit how we use your data.
- **Right to Data Portability:** You have the right to receive your data in a structured, commonly used, machine-readable format.
- **Right to Object:** You have the right to object to processing of your personal data based on legitimate interests.

To exercise any of these rights, please contact us at **privacy@lazytravel.ai**. We will respond to your request within 30 days.

---

## 9. Account & Data Deletion

You can request deletion of your account and all associated personal data by:

1. **Email:** Send a deletion request to **privacy@lazytravel.ai** with the subject line "Account Deletion Request".
2. **In-App:** Navigate to **Settings → Account → Delete Account** (if available in your app version).

Upon receiving a valid request, we will delete or anonymize your personal data within **30 days**, except where retention is required by applicable law.

---

## 10. Children's Privacy

The App is not intended for use by children under the age of 13 (or 16 in the EEA). We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, please contact us at **privacy@lazytravel.ai** and we will promptly delete such information.

---

## 11. Third-Party Links and Services

The App may display information about third-party services (e.g., landmarks with links to their websites). This Privacy Policy does not apply to those third-party services. We encourage you to review their privacy policies before providing any personal information.

---

## 12. International Data Transfers

Your personal data may be transferred to and processed in countries outside of your country of residence, including countries that may not provide the same level of data protection as your home country. When we transfer data internationally, we implement appropriate safeguards such as Standard Contractual Clauses (SCCs) approved by the European Commission.

---

## 13. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices, technology, legal requirements, or other factors. We will notify you of any material changes by:

- Posting the updated policy in this repository with a new "Last Updated" date.
- Displaying an in-app notification on your next login.

Your continued use of the App after any changes constitutes your acceptance of the updated policy.

---

## 14. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

**Lazy Traveler Ltd.**
Email: **privacy@lazytravel.ai**

We are committed to resolving any complaints about our collection or use of your personal information. If you are not satisfied with our response, you have the right to lodge a complaint with your local data protection authority.

---

*This Privacy Policy was last updated on March 5, 2026.*
