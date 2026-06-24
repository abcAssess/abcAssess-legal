---
layout: default
title: Privacy Policy
description: Version 1.3 · Updated June 24, 2026
---

<style>
  .btn { display: none !important; }
  header .project-tagline { margin-bottom: 2rem; }
</style>

[Return to Support Center](index.md)

---

## Table of Contents

1. [Our Commitment to Student Privacy](#1-our-commitment-to-student-privacy)
2. [Information We Collect (Data Minimization)](#2-information-we-collect-data-minimization)
3. [How We Use Your Data](#3-how-we-use-your-data)
4. [Security Architecture](#4-security-architecture)
5. [Data Sub-Processors](#5-data-sub-processors)
6. [Data Portability, Exports, and Backups](#6-data-portability-exports-and-backups)
7. [Your Rights](#7-your-rights)
8. [Legal Compliance](#8-legal-compliance)
9. [Data Retention and Deletion](#9-data-retention-and-deletion)
10. [Changes to This Policy](#10-changes-to-this-policy)
11. [Contact](#11-contact)

---

#### abcAssess is built specifically for educators. We do not sell student data, use it for behavioral advertising, or build marketing profiles of children. We operate as a "School Official" under FERPA and as a "Data Processor" under GDPR/UK GDPR.

#### abcAssess is available to educators in the United States, Canada (English-speaking provinces), Australia, New Zealand, the United Kingdom, and Ireland.

---

## 1. Our Commitment to Student Privacy

#### abcAssess is an educational assessment platform designed exclusively for teachers and schools. Privacy is not an afterthought — it is a foundational design principle of our product. We are committed to the following core principles:

* We do not sell student data to any third party, for any purpose, ever.
* We do not use student data for behavioral advertising, interest profiling, or marketing of any kind.
* We collect only the minimum data necessary to deliver educational assessment functionality.
* Student data belongs to the teacher and school — not to us.
* We provide full data portability and permanent deletion on request.
  
[Back to top ↑](#)

---

## 2. Information We Collect (Data Minimization)

#### We apply a strict data minimization policy, collecting only what is essential for educational assessment functionality.

- **2.1 Teacher Account Data**  
  We support local email/password sign-in, Google Sign-In, and Sign in with Apple. We collect your provider-supplied name, email address, and unique account identifier. We do not collect payment information, phone numbers, or physical addresses.

- **2.2 Student Assessment Data**  
  Teachers may enter the following minimal student identifiers: a student's first name and last initial (optional), birth month and year (optional, used solely to calculate age for assessment accuracy), or alternatively a student ID number or other non-name identifier. We deliberately avoid collecting exact birth dates, full legal names, addresses, or any other personally identifiable information beyond what is listed above.

- **2.3 Instructional Media**  
  To support custom and multimodal assessments (such as color identification or auditory phonemic checks), teachers may securely upload custom instructional images and audio recording prompts. All uploaded media must be strictly instructional in nature. We explicitly prohibit the collection, upload, or storage of any student photos, student videos, or student-generated audio recordings. Any media upload that appears to contain student likeness or student-generated content may be removed without notice.

- **2.4 Technical and Diagnostic Logs**  
  We collect non-identifiable diagnostic and performance data solely to maintain application stability and improve service reliability. This data does not include student names, scores, or identifiable information and is not linked to individual user accounts.

- **2.5 Cookies and Tracking**  
  abcAssess does not use third-party advertising cookies, behavioral tracking scripts, or cross-site tracking technologies. We use only technically necessary session cookies required for authentication and application function. We do not use Google Analytics, Meta Pixel, or similar behavioral tracking tools. If this changes in a future version, this policy will be updated and users will be notified in advance.

[Back to top ↑](#)

---

## 3. How We Use Your Data

#### We use the data we collect exclusively for the following purposes, consistent with our GDPR lawful basis for each category:

| Data Category | Purpose | Lawful Basis |
|---|---|---|
| Teacher Account Data | Account creation, authentication, and account management | Contract performance (Art. 6(1)(b)) |
| Student Assessment Data | Delivering assessment functionality and generating reports | Legitimate interests (Art. 6(1)(f)) |
| Instructional Media | Displaying teacher-uploaded content during assessments | Contract performance (Art. 6(1)(b)) |
| Technical Logs | Application stability, error diagnosis, and security monitoring | Legitimate interests (Art. 6(1)(f)) |

We do not use any data collected through abcAssess for purposes other than those listed above without obtaining prior written consent from the affected users.

[Back to top ↑](#)

---

## 4. Security Architecture
* **4.1 Client-Side Encryption**  
  Sensitive student data — including names and assessment scores — is encrypted at the application level before being transmitted to or stored in our database. This means that even our own developers and database administrators cannot view student names or results in plain text. We use AES-256 encryption for data at rest and TLS 1.3 for all data in transit.

* **4.2 Database Architecture**  
  Our encryption keys are managed separately from our database infrastructure (MongoDB Atlas), creating a database-blind architecture in which the underlying data store cannot be read without application-level decryption. This architectural separation significantly limits exposure in the event of a database-level security incident.

  Our primary database infrastructure is hosted in the United States. We intend to expand to EU/UK-based database infrastructure as our user base in those regions grows, in order to better serve data residency expectations for UK and EU users.

* **4.3 Access Controls**  
  Access to production systems and data infrastructure is restricted to authorized personnel only, protected by multi-factor authentication, and subject to the principle of least privilege. We conduct periodic reviews of access permissions.

* **4.4 Data Breach Notification**
  In the event of a confirmed data breach that affects personal data, we will:
  - (a) notify affected users by email as soon as reasonably practicable and no later than 72 hours after becoming aware of the breach, in compliance with GDPR Article 33 and UK GDPR requirements;
  - (b) notify relevant supervisory authorities as required by applicable law in each affected jurisdiction; and
  - (c) provide a plain-language description of the nature of the breach, the categories of data affected, and the steps we are taking to address it.  

  Notifications will be sent to the email address associated with the affected account. We encourage teachers to keep their account email addresses current.
  
[Back to top ↑](#)

---

## 5. Data Sub-Processors

#### We use a limited number of carefully selected sub-processors, each bound by contractual data processing agreements and their own security and privacy standards. We do not share data with sub-processors beyond what is necessary to deliver our service.

| Sub-Processor | Purpose | Data Location | Privacy Link |
|---|---|---|---|
| MongoDB Atlas | Encrypted database storage | Configurable (US by default) | [mongodb.com/legal/privacy-policy](https://mongodb.com/legal/privacy-policy) |
| Railway | Backend processing and encryption key management | US | [railway.app/legal/privacy](https://railway.app/legal/privacy) |
| Vercel | Application UI hosting and edge delivery | Global CDN / US primary | [vercel.com/legal/privacy-policy](https://vercel.com/legal/privacy-policy) |
| Google / Apple | Federated authentication (Sign-In) | Per provider policy | [policies.google.com](https://policies.google.com) |
| Resend | Transactional email (password resets, notifications) | US | [resend.com/legal/privacy-policy](https://resend.com/legal/privacy-policy) |
| Stripe | Payment processing and subscription management | US / Global | [stripe.com/privacy](https://stripe.com/privacy) |
| PostHog | Anonymized product analytics and feature usage tracking | US / EU | [posthog.com/privacy](https://posthog.com/privacy) |
| Sentry | Anonymized error monitoring and application stability | US | [sentry.io/privacy](https://sentry.io/privacy) |

Teachers and schools located in the European Union, United Kingdom, Australia, New Zealand, or Canada should be aware that some sub-processors may process data outside their home jurisdiction. Where this occurs, we rely on Standard Contractual Clauses (SCCs), adequacy decisions, or other approved transfer mechanisms as required by applicable law. Upon request, we will provide documentation of applicable transfer safeguards.

[Back to top ↑](#)

---

## 6. Data Portability, Exports, and Backups

- **6.1 PDF Reports**  
  Teachers may generate custom PDF reports, individual deep-dives, or class-wide summaries at any time. Reports are generated on demand and streamed directly to your browser session. We do not store copies of generated reports on our servers.
  
- **6.2 Full Data Export and Backup Files**  
  Teachers may download a complete backup of their account data at any time, including all classes, student records, and assessment histories. Exported files are downloaded directly to your local device. *We do not retain duplicate copies of exported data on our systems after the export is delivered.*  
  
  Backup files contain student data including names, assessment scores, and class records. Backup files can be imported into any abcAssess account, not only the originating account. This enables legitimate use cases such as account migration, end-of-year class handoff to a colleague, or account recovery. When a backup is imported into a different account, all data is rebound to the importing user. Co-teacher and assistant teacher links, pending invitations, and pending transfer requests are not included in backup exports and will not carry over on import.  
  
  **By downloading a backup file, you assume full responsibility for its secure storage, handling, and disposal in accordance with your school's data privacy policies and applicable law, including FERPA and any applicable local privacy legislation.** Backup files should be treated with the same care as any other document containing student records. Do not share backup files with unauthorized individuals. A confirmation acknowledgment is required within the app before a backup file can be downloaded.
  
- **6.3 Data Responsibility After Export**  
  Once data is exported or downloaded, the teacher or school assumes full responsibility for its secure storage, handling, and disposal in accordance with applicable local, national, and federal policies and regulations, including FERPA and any applicable local privacy legislation.
  
[Back to top ↑](#)

---

## 7. Your Rights

#### Depending on your jurisdiction, you have the following rights with respect to your data and the student data associated with your account. We honor these rights for all users regardless of location.

- **7.1 Access and Portability**  
  You have the right to request a complete copy of the personal data we hold about you and your associated student records. Use the full data export feature in the Reports section of the app or contact us at [legal@abcassess.app](mailto:legal@abcassess.app).
  
- **7.2 Rectification**  
  You have the right to correct inaccurate or incomplete personal data. Teacher account information can be updated directly within the app. Student records can be edited or corrected by the account holder at any time.
  
- **7.3 Erasure (Right to Be Forgotten)**  
  You have the right to permanently delete your account and all associated data. See [Section 9](#9-data-retention-and-deletion) for details on our cascade deletion process. Deletion requests are processed immediately upon confirmation within the app or within 30 days of a written request to [legal@abcassess.app](mailto:legal@abcassess.app).
  
- **7.4 Restriction and Objection**  
  You have the right to request that we restrict processing of your data or to object to certain types of processing. Contact us at [legal@abcassess.app](mailto:legal@abcassess.app) to make such a request. We will respond within 30 days.
  
- **7.5 Withdrawal of Consent**  
  Where processing is based on consent, you may withdraw consent at any time by deleting your account, which immediately halts all processing of your personal data and associated student records.
  
- **7.6 CCPA / CPRA Rights (California Residents)**  
  California residents have the right to know what personal information is collected, to delete personal information, to opt out of the sale of personal information (we do not sell personal information), and to non-discrimination for exercising these rights. To submit a California privacy request, contact [legal@abcassess.app](mailto:legal@abcassess.app).
  
- **7.7 GDPR and UK GDPR Rights (EU and UK Users)**  
  If you are located in the European Union or United Kingdom, you have additional rights under GDPR and UK GDPR including the right to data portability, the right to object to automated decision-making, and the right to lodge a complaint with your local supervisory authority. We encourage you to contact us first at [legal@abcassess.app](mailto:legal@abcassess.app) so we have the opportunity to address your concern directly. Please include "GDPR Request" in your subject line.
  
- **7.8 Australian Privacy Rights (Australian Users)**  
  If you are located in Australia, you have rights under the Privacy Act 1988 and Australian Privacy Principles (APPs), including the right to access and correct your personal information and the right to complain to the Office of the Australian Information Commissioner (OAIC). To exercise these rights contact [legal@abcassess.app](mailto:legal@abcassess.app) with "Australian Privacy Request" in the subject line.

- **7.9 New Zealand Privacy Rights (New Zealand Users)**  
  If you are located in New Zealand, you have rights under the Privacy Act 2020, including the right to access and correct your personal information and the right to complain to the Office of the Privacy Commissioner. To exercise these rights contact [legal@abcassess.app](mailto:legal@abcassess.app) with "NZ Privacy Request" in the subject line.
  
- **7.10 PIPEDA Rights (Canadian Users)**  
  If you are located in Canada, you have rights under the Personal Information Protection and Electronic Documents Act (PIPEDA), including the right to access your personal information and the right to challenge our compliance with the Privacy Commissioner of Canada. To exercise these rights contact [legal@abcassess.app](mailto:legal@abcassess.app) with "Canadian Privacy Request" in the subject line.
  
[Back to top ↑](#)

---

## 8. Legal Compliance

- **8.1 FERPA (United States)**  
  abcAssess operates as a "School Official" with a legitimate educational interest as defined under the Family Educational Rights and Privacy Act (FERPA), 20 U.S.C. § 1232g. The school or teacher retains complete legal ownership of and responsibility for all student education records. We access student records only as directed by the teacher or school and solely for the purpose of providing our educational assessment service.
  
- **8.2 COPPA (United States)**  
  abcAssess does not knowingly collect personal information directly from children under the age of 13. Student data is entered by teachers or school officials acting in their professional capacity. We rely on the teacher or school to serve as the operator obtaining verifiable parental consent on behalf of parents, consistent with the Children's Online Privacy Protection Act (COPPA), 15 U.S.C. § 6501 et seq., and FTC guidance on school-based consent. abcAssess does not communicate directly with students, and students do not create accounts or interact with our platform.

- **8.3 GDPR and UK GDPR (EU and UK Users)**  
  abcAssess operates as a Data Processor under the EU General Data Protection Regulation (GDPR) and UK GDPR. The teacher or school acts as the Data Controller. We process personal data only on documented instructions from the controller and implement appropriate technical and organizational measures to ensure data security. Where data is transferred outside the EEA or UK, we rely on Standard Contractual Clauses or other approved transfer mechanisms. We intend to appoint EU and UK Representatives as required by GDPR Article 27 and UK GDPR Article 27 respectively.
  
- **8.4 PIPEDA (Canada)**  
  abcAssess complies with the Personal Information Protection and Electronic Documents Act (PIPEDA) with respect to Canadian users. We collect, use, and disclose personal information only for the purposes identified in this policy, with the knowledge and consent of the individual where required, and we retain information only as long as necessary for those purposes.

- **8.5 Australian Privacy Principles (Australia)**  
  abcAssess complies with the Privacy Act 1988 (Cth) and the Australian Privacy Principles (APPs) with respect to Australian users. We handle personal information in accordance with APP requirements including collection, use, disclosure, data quality, and security obligations.

- **8.6 New Zealand Privacy Act (New Zealand)**  
  abcAssess complies with the Privacy Act 2020 with respect to New Zealand users. We collect personal information directly from individuals where reasonably practicable, use it only for the purposes for which it was collected, and protect it with reasonable security safeguards.

- **8.7 Teacher Warranty**  
  By using abcAssess, you represent and warrant that:
  - (a) you have the authority from your school or district to use this tool and to log student performance data;
  - (b) your use of abcAssess complies with your school's or institution's applicable data privacy policies and any applicable national, state, or provincial privacy legislation; and
  - (c) you have obtained or your institution has obtained all consents required by applicable law for the collection and processing of student data through our platform.

[Back to top ↑](#)

---

## 9. Data Retention and Deletion

- **9.1 Active Accounts**  
  We retain your account data and associated student records for as long as your account is active and in use. You may delete individual student records, classes, or your entire account at any time through App Settings.
  
- **9.2 Cascade Deletion**  
  Upon account deletion, our systems immediately trigger an automated cascade deletion process that permanently and irreversibly removes your teacher profile and all associated student records, assessment histories, and uploaded media from our active database. This process is initiated immediately upon your confirmation and cannot be undone. We recommend exporting your data before deleting your account if you wish to retain records.
  
  If your account has pending outgoing student or class transfer requests at the time of deletion, those transfers will be automatically cancelled and the intended recipients will be notified by email. Transfer requests that have already been accepted and completed are not affected by account deletion.
  
- **9.3 Free Trial Expiry**  
  When a 14-day free trial ends without a subscription being purchased, the account enters a suspended state with read-only access. An immediate email notification is sent advising the teacher to subscribe to continue or export and delete their data. If no subscription is purchased within 90 days of trial expiry, a final warning email is sent and the account and all associated data are permanently deleted pursuant to the cascade deletion process described in [Section 9.2](#9-data-retention-and-deletion). Teachers may log back in at any time during the 90-day grace period to export their data, subscribe, or manually delete their account.
  
- **9.4 Subscription Lapse**  
  When a paid subscription lapses — for any reason including non-renewal, failed payment, or school procurement delays — the account retains full access for 30 days from the lapse date to allow time for renewal. Reminder emails are sent at lapse, at 14 days, and at 25 days. If the subscription is not renewed within 30 days, the account enters a read-only suspended state for a further 60 days during which the teacher may view data, download reports, and export records but cannot run new assessments or add students. A final warning email is sent at day 85. If no renewal is made by day 90 from the original lapse date, the account and all associated data are permanently deleted pursuant to the cascade deletion process described in [Section 9.2](#9-data-retention-and-deletion). Teachers may resubscribe at any time during the grace period to immediately restore full access.
  
- **9.5 Inactivity**  
  Accounts that remain completely inactive for 12 consecutive months will be flagged for archival deletion. We will send a written warning notice to the account's registered email address 30 days prior to scheduled deletion. If no response or login activity is recorded within that 30-day window, the account and all associated data will be permanently deleted pursuant to the cascade deletion process described above. Free assistant accounts that have no active class connections are subject to the same 12-month inactivity policy. Free accounts hold no student data — deletion of a free account has no impact on student records, which remain with the class owner.
  
- **9.6 Backup and Recovery**  
  Following account deletion, data may persist in encrypted system backups for up to 30 days before being permanently overwritten in the ordinary course of our backup rotation cycle. During this period, data in backups is not accessible or restorable except in the event of a system-wide catastrophic failure, and only to the extent required to restore overall system integrity.
  
- **9.7 Transfer Request Expiry**  
  Pending student and class transfer requests expire automatically after 30 days if not accepted by the recipient. Upon expiry, the transfer is cancelled and the sending teacher retains their original data unchanged. The sending teacher and intended recipient are both notified by email when a transfer request expires. This 30-day limit applies regardless of whether the sending teacher's account remains active.
  
[Back to top ↑](#)

---

## 10. Changes to This Policy

#### We may update this Privacy Policy from time to time to reflect changes in our practices, technology, legal requirements, or other factors. When we make material changes, we will: 
- (a) update the Effective Date and Version number at the top of this policy;
- (b) notify active account holders by email at least 14 days before the changes take effect; and
- (c) maintain a changelog of prior versions available upon request.

Your continued use of abcAssess after the effective date of any update constitutes your acceptance of the revised policy. If you do not agree with a material change, you may delete your account prior to the effective date.

[Back to top ↑](#)

---

## 11. Contact

If you have questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

| | |
|---|---|
| **General Support** | [support@abcassess.app](mailto:support@abcassess.app) |
| **Legal & Privacy Requests** | [legal@abcassess.app](mailto:legal@abcassess.app) |
| **Response Time** | We aim to respond within 2 business days |

#### For jurisdiction-specific privacy requests please include the following in your subject line:
- GDPR/UK GDPR inquiries: "GDPR Request"
- COPPA inquiries: "COPPA Inquiry"
- Australian privacy inquiries: "Australian Privacy Request"
- New Zealand privacy inquiries: "NZ Privacy Request"
- Canadian privacy inquiries: "Canadian Privacy Request"

[Back to top ↑](#)

---

[Accessibility Statement](accessibility.md) &nbsp;-&nbsp; [Data Processing Agreement](dpa.md) &nbsp;-&nbsp; [Sub-Processor Registry](subprocessor-registry.md) &nbsp;-&nbsp; [Technical FAQs](technical-and-privacy-faqs.md) &nbsp;-&nbsp; [Terms of Service](terms-of-service.md) &nbsp;-&nbsp; [User Guide](User-guide.md)


[Return to Support Center](index.md)


