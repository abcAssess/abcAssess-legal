---
layout: default
title: Sub-Processor Registry
description: Version 2.4 · Last Reviewed September 4, 2026
---

<style>
  .btn { display: none !important; }
  header .project-tagline { margin-bottom: 2rem; }
</style>

[Return to Support Center](index.md)

---

*Published in accordance with GDPR Article 28 and [abcAssess Data Processing Agreement Section 4](dpa.md#4-sub-processors)*

---

This registry lists all third-party sub-processors engaged by abcAssess to process personal data in connection with the abcAssess educational assessment platform. All sub-processors are bound by contractual data processing obligations no less protective than those in the abcAssess Data Processing Agreement. Subscribers are notified at least 14 days in advance of any additions or changes to this list, consistent with [Section 4.2 of the Data Processing Agreement](dpa.md#4-sub-processors).

**Important:** abcAssess applies client-side encryption to sensitive student data before it is transmitted to any sub-processor. This means that student names and assessment results are encrypted at the application level and are unreadable to sub-processor infrastructure personnel. The data transmitted column below reflects what each sub-processor receives — which in most cases is encrypted, unreadable data rather than plain-text student information.

---

## Table of Contents

- [Current Sub-Processor Registry](#current-sub-processor-registry)
  - [MongoDB Atlas](#mongodb-atlas-mongodb-inc)
  - [Railway](#railway-railway-corp)
  - [Vercel](#vercel-inc)
  - [Resend](#resend-resend-inc)
  - [Google LLC](#google-llc-sign-in-with-google)
  - [Loops](#loops-astrodon-corporation)
  - [Apple Inc.](#apple-inc-sign-in-with-apple)
  - [Stripe](#stripe-inc)
  - [PostHog](#posthog-inc)
  - [Sentry](#functional-software-inc-sentry)
- [Infrastructure and Development Tools — Not Sub-Processors](#infrastructure-and-development-tools--not-sub-processors)
- [Sub-Processor Change Log](#sub-processor-change-log)
- [Sub-Processor Change Notification Process](#sub-processor-change-notification-process)
- [Contact and Documentation Requests](#contact-and-documentation-requests)

---

## Current Sub-Processor Registry

### MongoDB Atlas (MongoDB, Inc.)

| Field | Detail |
|---|---|
| **Role** | Encrypted database storage for all student records, assessment data, and account information. |
| **Data Transmitted** | Encrypted student identifiers, encrypted assessment scores, and teacher account data. All sensitive fields are encrypted before reaching this layer. |
| **Data Location** | United States. An EU region is not currently planned, but may be considered in the future if sufficient interest arises from UK/EU users. |
| **Transfer Mechanism** | Standard Contractual Clauses (SCCs) for EU/UK transfers. EU-U.S. Data Privacy Framework certified. |
| **Certifications** | SOC 2 Type II, ISO 27001, AES-256 at rest, TLS 1.3 in transit |
| **Privacy Policy** | [mongodb.com/legal/privacy-policy](https://mongodb.com/legal/privacy-policy) |

[Back to top ↑](#)

---

### Railway (Railway Corp.)

| Field | Detail |
|---|---|
| **Role** | Backend application server and encryption key management. Processes encrypted data payloads between application and database. |
| **Data Transmitted** | Encrypted JSON data payloads in transit. Encryption key material managed in secure vaults. No plain-text student data processed. |
| **Data Location** | United States |
| **Transfer Mechanism** | SCCs for EU/UK transfers where applicable. |
| **Certifications** | SOC 2 Type II |
| **Privacy Policy** | [railway.app/legal/privacy](https://railway.app/legal/privacy) |

[Back to top ↑](#)

---

### Vercel Inc.

| Field | Detail |
|---|---|
| **Role** | Application user interface hosting and global edge delivery. Serves the abcAssess web frontend to end users. |
| **Data Transmitted** | Non-identifiable web navigation events and page performance metrics. No student data or assessment results transmitted. |
| **Data Location** | Global CDN. Primary infrastructure in United States. Edge caching may occur in other regions; no data stored permanently in EU regions. |
| **Transfer Mechanism** | SCCs for EU/UK transfers. GDPR DPA available. EU-U.S. Data Privacy Framework certified. |
| **Certifications** | SOC 2 Type II, ISO 27001:2022, GDPR compliant |
| **Privacy Policy** | [vercel.com/legal/privacy-policy](https://vercel.com/legal/privacy-policy) |

[Back to top ↑](#)

---

### Resend (Resend Inc.)

| Field | Detail |
|---|---|
| **Role** | Transactional email delivery for system notifications including password resets, account alerts, and inactivity warnings. |
| **Data Transmitted** | Teacher email address, email subject and body content for transactional messages only. No student data transmitted. |
| **Data Location** | United States |
| **Transfer Mechanism** | SCCs for EU/UK transfers where applicable. |
| **Certifications** | SOC 2 Type II |
| **Privacy Policy** | [resend.com/legal/privacy-policy](https://resend.com/legal/privacy-policy) |

[Back to top ↑](#)

---

### Loops (Astrodon Corporation)
 
| Field | Detail |
|---|---|
| **Role** | Automated onboarding email sequence delivery. Sends a scheduled series of educational/feature-focus emails to teachers over their first weeks after signing up, separate from Resend's transactional messages. |
| **Data Transmitted** | Teacher email address and teacher name for the purpose of sequence enrollment and email personalization. No student names, assessment scores, or student PII transmitted. |
| **Data Location** | United States |
| **Transfer Mechanism** | SCCs for EU/UK transfers. EU-U.S. Data Privacy Framework certified (including UK Extension and Swiss-U.S. DPF). |
| **Certifications** | SOC 2 (verified via independent trust portal) |
| **Privacy Policy** | [loops.so/privacy](https://loops.so/privacy) |
 
[Back to top ↑](#)
 
---

### Google LLC (Sign in with Google)

| Field | Detail |
|---|---|
| **Role** | Federated authentication service. Used when teachers choose to sign in with their Google account. |
| **Data Transmitted** | Teacher name, email address, and Google account identifier provided by Google upon authentication. No student data transmitted. |
| **Data Location** | Global (per Google infrastructure). Google Cloud DPA governs processing. |
| **Transfer Mechanism** | SCCs for EU/UK transfers. GDPR DPA available. EU-U.S. Data Privacy Framework certified. |
| **Certifications** | ISO 27001, SOC 2 Type II, GDPR compliant |
| **Privacy Policy** | [policies.google.com/privacy](https://policies.google.com/privacy) |

[Back to top ↑](#)

---

### Apple Inc. (Sign in with Apple)

| Field | Detail |
|---|---|
| **Role** | Federated authentication service. Used when teachers choose to sign in with their Apple ID. |
| **Data Transmitted** | Teacher email address and Apple account identifier provided by Apple upon authentication. No student data transmitted. |
| **Data Location** | Global (per Apple infrastructure). Apple DPA governs processing. |
| **Transfer Mechanism** | SCCs for EU/UK transfers. GDPR DPA available. |
| **Certifications** | ISO 27001, SOC 2, GDPR compliant |
| **Privacy Policy** | [apple.com/legal/privacy](https://apple.com/legal/privacy) |

[Back to top ↑](#)

---

### Stripe, Inc.

| Field | Detail |
|---|---|
| **Role** | Payment processing and subscription management. Handles all billing transactions, subscription renewals, plan changes, and tax collection (VAT/GST). Integration planned for end of beta period — not yet active while beta participants receive free access. |
| **Data Transmitted** | Teacher name, email address, payment card details, billing address, and subscription status. No student data transmitted. |
| **Data Location** | United States / Global |
| **Transfer Mechanism** | SCCs for EU/UK transfers. EU-U.S. Data Privacy Framework certified. GDPR DPA available. |
| **Certifications** | SOC 2 Type II, PCI DSS Level 1 |
| **Privacy Policy** | [stripe.com/privacy](https://stripe.com/privacy) |

[Back to top ↑](#)

---

### PostHog, Inc.

| Field | Detail |
|---|---|
| **Role** | Anonymized product analytics and feature usage tracking. Records high-level application events to inform product development decisions. |
| **Data Transmitted** | Anonymized event data only — no student names, scores, or PII transmitted. Events include anonymized actions such as assessment completed, report downloaded, and feature used. IP addresses are anonymized before processing. Person profiles are disabled. |
| **Data Location** | United States (U.S. Cloud). An EU Cloud option is not currently in use, but may be considered in the future if sufficient interest arises from UK/EU users. |
| **Transfer Mechanism** | SCCs for EU/UK transfers. GDPR DPA available. |
| **Certifications** | SOC 2 Type II |
| **Privacy Policy** | [posthog.com/privacy](https://posthog.com/privacy) |

[Back to top ↑](#)

---

### Functional Software, Inc. (Sentry)

| Field | Detail |
|---|---|
| **Role** | Application error monitoring and stability tracking. Captures anonymized error reports to support debugging and platform reliability. |
| **Data Transmitted** | Anonymized error logs, stack traces, and performance metrics. Student data fields are masked before transmission — no student names, scores, or PII transmitted. Session replay is configured with student data masking enabled. |
| **Data Location** | United States |
| **Transfer Mechanism** | SCCs for EU/UK transfers. GDPR DPA available. |
| **Certifications** | SOC 2 Type II |
| **Privacy Policy** | [sentry.io/privacy](https://sentry.io/privacy) |

[Back to top ↑](#)

---

## Infrastructure and Development Tools — Not Sub-Processors

The following tools are used by abcAssess in connection with platform development, monitoring, and infrastructure management. These tools do not process personal data of abcAssess users (teachers or students) and are therefore not classified as sub-processors under GDPR Article 28. They are listed here in the interest of full transparency.

---

### Uptime Robot

**Category:** Infrastructure monitoring

**Use:** Monitors the availability and response time of abcAssess URLs (app, domain, API health endpoint, backend). Sends alerts when services are unavailable.

**Data processed:** URLs and HTTP response codes only. No personal data, student data, or teacher data processed.

---

### GitHub (GitHub, Inc. / Microsoft)

**Category:** Source code management

**Use:** Hosts the abcAssess application source code repository and private compliance documentation repository.

**Data processed:** Source code, commit history, and development documentation. No student data or teacher personal data from abcAssess users processed. Compliance documents stored in private repository contain references to data handling practices but not actual personal data records.

---

### Emergent AI

**Category:** AI-assisted development tool

**Use:** Used as the primary AI-assisted software development tool during construction of the abcAssess platform. Danielle Andrist directed all product and architectural decisions.

**Data processed:** Development prompts and product direction provided by the founder. No student data, no teacher personal data from abcAssess users processed.

---

### Anthropic (Claude AI)

**Category:** AI-assisted development tool

**Use:** Used for AI-assisted product strategy, legal document drafting, UX review, and business planning during development of abcAssess.

**Data processed:** Product strategy discussions and document drafting context. Founder name and business information referenced in document drafting. No student data, no abcAssess user personal data processed.

---

### Cloudflare, Inc.

**Category:** DNS management

**Use:** Domain Name System (DNS) management for abcassess.app. Used for DNS routing only — not as a traffic proxy or CDN layer.

**Data processed:** DNS queries and routing only. No personal data, student data, or teacher data processed.

[Back to top ↑](#)

---

## Sub-Processor Change Log

| Date | Version | Change Type | Description |
|---|---|---|---|
| September 4, 2026 | 2.4 | Update | Softened EU region language for MongoDB Atlas and PostHog to accurately reflect no current plans. Added end-of-beta qualifier to Stripe entry, since payment processing is not yet active during the beta period. Added Loops to the registry (previously missing despite being added elsewhere). Corrected Change Log ordering. |
| August 24, 2026 | 2.3 | Addition | Added Loops (Astrodon Corporation) as a new sub-processor for automated onboarding email sequence delivery. Clarified Resend's role to distinguish its transactional/one-time-welcome scope from Loops' ongoing sequence scope. |
| July 27, 2026 | 2.2 | Update | Expanded Resend scope description to reflect full email template suite (invitations, transfers, assessment sharing, onboarding sequence). Updated next scheduled review date. No new sub-processors added. |
| June 7, 2026 | 2.1 | Addition / Expansion | Added Stripe (payment processing), PostHog (anonymized analytics), and Sentry (error monitoring) to main registry. Added Infrastructure and Development Tools section listing five tools that process no personal data: Uptime Robot, GitHub, Emergent AI, Anthropic (Claude AI), and Cloudflare. Updated contact email to legal@abcassess.app. Removed mailing address. Updated company name to abcAssess (pending LLC formation). |
| May 30, 2026 | 2.0 | Addition / Expansion | Added Google LLC and Apple Inc. as authentication sub-processors. Added data location, transfer mechanism, and privacy policy columns. Added client-side encryption note. Corrected Vercel certification to ISO 27001:2022. |
| May 18, 2026 | 1.0 | Initial Publication | Registry first published with four sub-processors: MongoDB Atlas, Railway, Vercel, Resend. |

[Back to top ↑](#)

---

## Sub-Processor Change Notification Process

In accordance with [Section 4.2](dpa.md#4-sub-processors) of the abcAssess Data Processing Agreement, abcAssess will:

- Notify all active Subscribers by email at least 14 days before adding, removing, or making material changes to any sub-processor.
- Update this registry and increment the version number upon any change.
- Allow Subscribers to object to a new sub-processor within 14 days of notification by contacting [legal@abcassess.app](mailto:legal@abcassess.app).
- Where a legitimate objection cannot be resolved, allow the Subscriber to terminate their account without penalty within 30 days of the original notification.

[Back to top ↑](#)

---

## Contact and Documentation Requests

For questions about this registry, requests for sub-processor DPA documentation, or to submit a sub-processor objection:

| | |
|---|---|
| **Email** | [legal@abcassess.app](legal@abcassess.app) |
| **Subject Line** | Include "Sub-Processor" in your subject line |
| **Response Time** | Within 2 business days for general inquiries; within 14 days for formal objections |
| **DPA Documentation** | Available upon request — include "DPA Documentation Request" in subject line |
| **Next Scheduled Review** | November 30, 2026 |

[Back to top ↑](#)

---

[Accessibility Statement](accessibility.md) &nbsp;-&nbsp; [Data Processing Agreement](dpa.md) &nbsp;-&nbsp; [Privacy Policy](privacy-policy.md) &nbsp;-&nbsp; [Technical FAQs](technical-and-privacy-faqs.md) &nbsp;-&nbsp; [Terms of Service](terms-of-service.md) &nbsp;-&nbsp; [User Guide](User-guide.md)


[Return to Support Center](index.md)


*© 2026 abcAssess. All rights reserved.*
