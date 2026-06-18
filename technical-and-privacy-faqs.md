---
layout: default
title: Technical and Privacy FAQs
description: Version 2.1 · June 18, 2026
---

<style>
  .btn { display: none !important; }
  header .project-tagline { margin-bottom: 2rem; }
</style>


[Return to Support Center](index.md)

This page answers the most common questions from teachers, school administrators, and IT departments about how abcAssess handles data, security, and privacy. Questions marked with an IT Administrator note include additional technical detail for IT evaluation purposes.

For full details, see our Privacy Policy, Terms of Service, and Data Processing Agreement.

---

## Table of Contents

### Privacy & Legal Compliance
1. [Is abcAssess FERPA and COPPA compliant?](#1-is-abcassess-ferpa-and-coppa-compliant)
2. [Is abcAssess compliant with GDPR, UK GDPR, or other international privacy laws?](#2-is-abcassess-compliant-with-gdpr-uk-gdpr-or-other-international-privacy-laws)
3. [Does abcAssess use student data to train AI or machine learning models?](#3-does-abcassess-use-student-data-to-train-ai-or-machine-learning-models)
4. [What student data does abcAssess collect — and what does it not collect?](#4-what-student-data-does-abcassess-collect--and-what-does-it-not-collect)
5. [Who can see student data inside abcAssess?](#5-who-can-see-student-data-inside-abcassess)
6. [Can teachers share access with assistants or co-teachers?](#6-can-teachers-share-access-with-assistants-or-co-teachers)

### Security
7. [How is student data secured?](#7-how-is-student-data-secured)
8. [Are emails from abcAssess genuine and secure?](#8-are-emails-from-abcassess-genuine-and-secure)
9. [What happens if there is a data breach?](#9-what-happens-if-there-is-a-data-breach)

### Data Practices
10. [How do you track application usage?](#10-how-do-you-track-application-usage)
11. [Do you use student data for advertising?](#11-do-you-use-student-data-for-advertising)
12. [Where is my data hosted, and who handles it?](#12-where-is-my-data-hosted-and-who-handles-it)

### Account & Data Management
13. [Can I export my data?](#13-can-i-export-my-data)
14. [What are backup files and how do they work?](#14-what-are-backup-files-and-how-do-they-work)
15. [Can I share my backup file with a colleague?](#15-can-i-share-my-backup-file-with-a-colleague)
16. [How do student transfers between teachers work?](#16-how-do-student-transfers-between-teachers-work)
17. [What happens to student data when a teacher leaves a school?](#17-what-happens-to-student-data-when-a-teacher-leaves-a-school)
18. [What happens if I delete my account?](#18-what-happens-if-i-delete-my-account)
19. [Does abcAssess work offline?](#19-does-abcassess-work-offline)

### Subscriptions & Billing
20. [What happens to my students' data if I don't subscribe after the free trial?](#20-what-happens-to-my-students-data-if-i-dont-subscribe-after-the-free-trial)
21. [What subscription plans are available?](#21-what-subscription-plans-are-available)
22. [What happens if my subscription lapses?](#22-what-happens-if-my-subscription-lapses)
23. [Is abcAssess available outside the United States?](#23-is-abcassess-available-outside-the-united-states)
24. [What if I still have more questions?](#24-still-have-questions)
---

# Privacy and Legal Compliance

## 1. Is abcAssess FERPA and COPPA compliant?

### Yes - fully.

#### abcAssess acts as a "School Official" under FERPA, meaning we process student data only for legitimate educational purposes and only under the direction of the teacher or school. We practice strict data minimization: to identify students, we collect only a first name and last initial (optional) and birth month and year (optional, stored as a YYYY-MM value). We never collect full legal names, exact birth dates, home addresses, or any student-generated media such as photos or videos. Under COPPA, we never use student data for advertising, profiling, or any commercial purpose. Students do not create accounts or interact with the platform directly.

[Back to top ↑](#)

---

## 2. Is abcAssess compliant with GDPR, UK GDPR, or other international privacy laws?

### Yes — we are designed for compliance across all markets we serve.

#### abcAssess currently serves educators in the United States, Canada (English-speaking provinces), Australia, New Zealand, the United Kingdom, and Ireland.

- **EU users:** abcAssess complies with GDPR and acts as a Data Processor under GDPR Article 28. We use Standard Contractual Clauses (SCCs) for data transfers outside the EEA. We intend to appoint an EU Representative as required by GDPR Article 27 — this will be updated in our DPA when the appointment is made.
   **UK users:** abcAssess complies with UK GDPR. We use the UK International Data Transfer Agreement (IDTA) for applicable transfers. We intend to appoint a UK Representative as required by UK GDPR Article 27.
- **Canadian users:** abcAssess complies with PIPEDA.
- **Australian users:** abcAssess complies with the Privacy Act 1988 (Cth) and Australian Privacy Principles (APPs).
- **New Zealand users:** abcAssess complies with the Privacy Act 2020.

Our full Data Processing Agreement, which satisfies GDPR Article 28 requirements and addresses all applicable jurisdictions, is available upon request at [legal@abcassess.app](mailto:legal@abcassess.app)

[Back to top ↑](#)

---

## 3. Does abcAssess use student data to train AI or machine learning models?

### Never — this is explicitly prohibited.

#### Student data entered into abcAssess is never used to train, fine-tune, or improve any artificial intelligence or machine learning model — by us or by any third party. This prohibition is written into our Data Processing Agreement and our sub-processor contracts. Student data is used solely to deliver the assessment features you have requested. This will not change without explicit notice and consent.

[Back to top ↑](#)

---

## 4. Who owns the data I enter into abcAssess?

### You do — or your school district does.

#### abcAssess does not claim ownership of any student records or assessment data you enter. Under FERPA, student education records belong to the school or district. We are a service provider — we hold and process your data on your behalf. We will never sell, share, or use student data for any purpose outside of delivering the Service to you.

[Back to top ↑](#)

---

## 5. Can my school administrator or district see my classroom data?

### No — your classroom data is isolated to your account.

#### abcAssess enforces strict multi-tenant data isolation at the server level. Records from your classroom are filtered through server-side controls tied to your unique account identifier. No other teacher, administrator, or district user can access your classroom data through the platform unless you explicitly invite them as a co-teacher or assistant on your account. abcAssess staff cannot view student names or scores in plain text due to our client-side encryption architecture.

#### School-level or district-level administrator accounts are not currently available. Teachers control their own data independently.

- **IT Administrator note:** Data isolation is enforced through server-side query middleware using unique organizational and teacher identifiers. Records from one account cannot be accessed by another account at the database query level, independent of application-layer controls.

[Back to top ↑](#)

---

## 6. What access do co-teachers and assistants have?

### It depends on the role — abcAssess has two levels of shared access.
- Co-Teachers share full ownership of the class. They can run assessments, manage students, view all reports, change assessment settings, and invite others.
- Assistant Teachers can run assessments and add assessment notes only. They cannot view reports, edit the student roster, change assessment settings, or invite other teachers.

#### Access is granted by the Lead Teacher or Co-Teacher through the Manage Teachers feature. The teacher who grants access is responsible for ensuring that shared users are authorized by their institution and understand their obligations under applicable privacy law.

[Back to top ↑](#)

---

# Security

## 7. How is student data secured?

### With multiple layers of protection — including encryption that even we cannot read through.

#### abcAssess uses a database-blind encryption architecture. Sensitive student data — including names and assessment scores — is encrypted at the application level before it is ever sent to our database. This means our own database administrators cannot view student information in plain text. All data is also encrypted during transmission and encrypted again at rest in our database. This layered approach means that even if our database were somehow accessed by an unauthorized party, the data would be unreadable without the application-level encryption keys.

- **IT Administrator note:** Student identifiers and score arrays are protected using Client-Side Field-Level Encryption (CSFLE) with AES-256 encryption. Encryption keys are managed through Railway and are separate from the MongoDB Atlas database cluster. Data is encrypted in transit using TLS 1.3 and at rest using AES-256 within MongoDB Atlas (SOC 2 Type II, ISO 27001 certified).

[Back to top ↑](#)

---

## 8. Are emails from abcAssess genuine and secure?

### Yes — we use standard email authentication protocols to prevent spoofing.

#### All outbound emails from abcAssess — including password resets, system notifications, and account alerts — are sent through authenticated channels. We implement DMARC, SPF, and DKIM email authentication protocols, which means your email provider can verify that messages claiming to be from abcAssess are genuine. If you ever receive a suspicious email claiming to be from abcAssess, do not click any links — contact us directly at [support@abcassess.app](mailto:support@abcassess.app).

- **IT Administrator note:** Outbound email is handled through Resend using dedicated sending subdomains protected by HSTS. DMARC policy enforcement, unified SPF records, and DKIM signing are configured to prevent spoofing and ensure deliverability and authenticity of all system messages.

[Back to top ↑](#)

---

## 9. What happens if there is a data breach?

### We notify you promptly and take immediate action.

#### In the event of a confirmed data breach affecting personal data, abcAssess will notify affected account holders by email as quickly as possible — and within 72 hours of becoming aware of the breach, consistent with GDPR and UK GDPR requirements. Our notification will clearly explain what happened, what data was affected, and what steps we are taking to address it. We will notify relevant supervisory authorities as required by applicable law in each affected jurisdiction and cooperate fully with any regulatory inquiries.

[Back to top ↑](#)

---

# Data Practices

## 10. How do you track application usage?

### We use privacy-first analytics that collect no personally identifiable information.

#### abcAssess uses PostHog for internal product analytics and Sentry for error monitoring. These tools record only anonymized, high-level events — such as when an assessment is completed or a report is generated — and do not collect any personally identifiable information from teachers or students. We do not use Google Analytics, Meta Pixel, or any behavioral advertising tracking tools. If this changes in a future version, we will update our Privacy Policy and notify users in advance.

[Back to top ↑](#)

---

## 11. Do you use student data for advertising?

### Never — not now, not ever.

#### abcAssess does not engage in behavioral advertising of any kind. We do not build marketing profiles based on student data or teacher usage. We do not share data with advertising networks. Student data exists in abcAssess for one purpose only: to help you assess and support your students.

[Back to top ↑](#)

---

## 12. Where is my data hosted, and who handles it?

### In secure, certified cloud infrastructure.

#### abcAssess uses a small set of carefully selected infrastructure providers, each with strong security certifications:

| Provider | Role | Data Location | Certification |
|---|---|---|---|
| MongoDB Atlas | Encrypted database storage | United States (EU region planned for UK/EU users) | SOC 2 Type II, ISO 27001 |
| Railway | Backend processing and encryption key management | United States | SOC 2 Type II |
| Vercel | Application hosting and edge delivery | Global CDN / U.S. primary | SOC 2 Type II |
| Resend | Transactional email delivery | United States | SOC 2 Type II |
| Stripe | Payment processing | United States / Global | SOC 2 Type II, PCI DSS Level 1 |
| PostHog | Anonymized product analytics — no student PII collected | U.S. / EU | SOC 2 Type II |
| Sentry | Anonymized error monitoring — no student PII collected | United States | SOC 2 Type II |

#### Data is stored in the United States by default. We are planning to expand to EU/UK-based database infrastructure as our user base in those regions grows. UK and EU Subscribers should review our Data Processing Agreement for details on applicable international transfer mechanisms.

[Back to top ↑](#)

---

# Account & Data Management

## 13. Can I export my data?

### Yes — full data portability is built into the app.

#### You can generate PDF reports for individual students or full classes at any time from the Reports page. You can also download a complete backup of all your account data — including classes, student records, and assessment histories — from the Reports page.

#### We do not store copies of exported files on our servers after delivery. Once downloaded, you are responsible for storing your data securely in accordance with your school or district's policies and applicable privacy law.

[Back to top ↑](#)

---

## Q14. What are backup files and how do they work?

### Backup files are a complete portable copy of your account data.

#### A backup file contains all your classes, student records, and assessment histories. Backup files can be imported into any abcAssess account — not only the originating account. This enables legitimate use cases such as account migration, end-of-year class handoff to a colleague, or account recovery if you are locked out.
Important things to know about backup files:
- A confirmation acknowledgment is required before downloading. By downloading, you confirm that you will handle the file in accordance with FERPA and applicable privacy law.
- Backup files contain student data and should be treated with the same care as any other document containing student records. Do not share backup files with unauthorized individuals.
- You are legally responsible for ensuring that any educator you share a backup with has a legitimate educational interest in those student records.
- Co-teacher and assistant teacher links, pending invitations, and pending transfer requests are not included in backup files and will not carry over on import.
- Student names are encrypted and tied to the originating deployment. If a backup is imported into a different abcAssess deployment, student names may display as unreadable — but classes, scores, and assessment histories will import cleanly. You would need to re-enter student names manually in that scenario.

[Back to top ↑](#)

---

## 15. Can I share my backup file with a colleague?

### Technically yes — but you carry the legal responsibility.

#### Because backup files can be imported into any abcAssess account, you could share one with a colleague. However, by downloading the backup you have already acknowledged your responsibility under FERPA and applicable privacy law to ensure the receiving educator has a legitimate educational interest in those student records.

#### For most end-of-year handoffs, we recommend using the built-in student transfer feature instead. It requires the receiving teacher to explicitly accept the transfer, creates an auditable record, and is the more compliant approach for transferring student records between educators.

[Back to top ↑](#)

---

## 16. How do student transfers between teachers work?

### Through a consent-based request and acceptance flow.

#### A teacher can transfer individual students or an entire class to another abcAssess educator. The receiving teacher must explicitly accept the transfer before any data moves. Transfer requests expire automatically after 30 days if not accepted.
#### When initiating a transfer, the sending teacher must confirm that the receiving educator has a legitimate educational interest in those student records, in compliance with FERPA and applicable privacy law.
#### The sending teacher can choose to keep a copy of the data, archive their copy, or remove their copy entirely. Archive and remove actions are held until the recipient accepts — so if the transfer is never accepted, the sending teacher's data remains unchanged.

[Back to top ↑](#)

---

## 17. What happens to student data when a teacher leaves a school?

### The teacher retains their account and data — the school does not automatically receive it.

#### abcAssess is a teacher-account-based tool. When a teacher leaves a school, their account and all associated student data remains under their control. The school does not automatically receive or retain access to that data.
#### If a teacher is leaving and wants to hand off their students to a colleague, they should use the built-in student or class transfer feature before their last day. If a teacher's account is simply abandoned, it will be flagged for deletion after 12 months of inactivity following a 30-day warning email.
#### Schools and districts concerned about data continuity and ownership should review our Data Processing Agreement and consider establishing a formal data governance policy for use of third-party edtech tools.

[Back to top ↑](#)

---

## 18. What happens if I delete my account?

### Your data is permanently and immediately deleted.

#### When you delete your account through App Settings, abcAssess immediately initiates a cascade deletion process that permanently removes your teacher profile and all associated student records, assessment histories, and uploaded media from our active database. This process begins immediately upon your confirmation and cannot be undone.

#### We recommend exporting your data before deleting your account if you wish to keep records. Encrypted system backups may retain data for up to 30 days as part of our standard backup rotation before being permanently overwritten — during this period the data is not accessible or restorable under normal circumstances.

#### *Note: Cancelling your subscription and deleting your account are separate actions. You can cancel billing without deleting your data.*

[Back to top ↑](#)

---

## 19. Does abcAssess work offline?

### Yes — with two layers of local protection.

#### abcAssess supports offline data capture so you can record assessments in low-connectivity environments such as playgrounds, hallways, or areas with poor reception.
How it works:
- While you are mid-assessment, the app automatically saves a draft snapshot of your responses to your device's local storage every second. If your phone closes or the app is interrupted, your progress is saved and you can resume when you reopen the app.
- When you complete an assessment, the app immediately attempts to sync to our servers. If you are offline, the completed assessment is held in a persistent local queue on your device and syncs automatically as soon as connectivity is restored. Each assessment stays in the queue until our server confirms receipt — so there is no risk of double-posting.
The one limitation to be aware of:
- If your device is lost, stolen, wiped, or factory reset before unsynced assessments have been uploaded, that data cannot be recovered by abcAssess. Local storage is device-specific and cannot be restored remotely. We recommend checking that assessments have synced (visible in the Pending Sync section of Settings) before retiring or resetting a device.

[Back to top ↑](#)

---

## 20. What happens to my students' data if I don't subscribe after the free trial?

### Your data is protected during a grace period, then permanently deleted.

#### When your 14-day free trial ends without a subscription being purchased, your account enters a suspended state with read-only access — you can still log in and export your data but cannot run new assessments or add students. You'll receive an immediate email letting you know your trial has ended with options to subscribe or export and delete your data.

#### If no subscription is purchased within 90 days of your trial ending, your account and all associated data — including all student records and assessment histories — are permanently deleted. You'll receive a warning email before this happens.

#### During the 90-day grace period you can log back in at any time to export your data, subscribe, or manually delete your account. We recommend exporting any data you want to keep before the grace period ends.

[Back to top ↑](#)

---

## 21. What subscription plans are available?

### Two individual plans plus school and district options.
- 14-day free trial: All new accounts start with a full-featured free trial. No payment information required during the trial — a valid payment method is needed at the end to continue.
- Monthly Plan — $5/month: Full access to all features, billed month-to-month. Cancel anytime.
- Annual Plan — $50/year: Full access to all features for 12 months. Saves $10 versus monthly. Renews automatically each year.
- School and district pricing: Available for organizations with multiple teachers. Contact us at [support@abcassess.app](mailto:support@abcassess.app) for pricing information.
- Beta participant pricing: Teachers who participated in the abcAssess beta program receive the following benefits:
  - One full year of free access following public launch, upon completion of the end-of-beta survey
  - Founding Member rate — a permanent 20% discount off the then-current subscription price for as long as they maintain an active subscription
  - Beta centers receive a permanent 20% discount off center licensing when that option becomes available

#### See Section 6.10 of the Terms of Service for full details.

[Back to top ↑](#)

---

## 22. What happens if my subscription lapses?

### You have a 90-day window before any data is affected.

#### If your subscription lapses for any reason — including non-renewal, a failed payment, or school procurement delays — here is what happens:
- Days 1–30: Full access continues. You'll receive reminder emails at lapse, day 14, and day 25.
- Days 31–90: Your account enters read-only mode. You can view all your data, download reports, and export records, but cannot run new assessments or add students.
- Day 85: A final warning email is sent.
- Day 90: Your account and all associated student data are permanently deleted.

#### You can resubscribe at any time during the 90-day window to immediately restore full access with all your data intact.

#### This grace period is intentionally generous — we know school procurement timelines, fiscal year resets, and PO processing can cause brief lapses that are entirely outside a teacher's control. We don't want an administrative delay to cost you your data.

[Back to top ↑](#)

---

## 23. Is abcAssess available outside the United States?

### Yes — we currently serve six English-speaking markets.

#### abcAssess is available to educators in the United States, Canada (English-speaking provinces), Australia, New Zealand, the United Kingdom, and Ireland. The app is available in English only at this time.

#### Each market has its own applicable privacy law compliance — see Q2 for details. Pricing is displayed in USD. Applicable taxes including VAT (UK/Ireland) and GST (Australia/New Zealand) are calculated and collected automatically at checkout.

[Back to top ↑](#)

---

## 24. Still Have Questions?

### If you have a question that isn't answered here — or if you're an IT administrator evaluating abcAssess for your district or center — we're happy to help.

| | |
|---|---|
| **General Support** | [support@abcassess.app](mailto:support@abcassess.app) |
| **Legal & Privacy** | [legal@abcassess.app](mailto:legal@abcassess.app) |
| **DPA Requests** | [legal@abcassess.app](mailto:legal@abcassess.app) — include "DPA Request" in subject |
| **Security Questions** | [legal@abcassess.app](mailto:legal@abcassess.app) — include "Security" in subject |
| **Response Time** | We aim to respond within 2 business days |
| **Full Documentation** | Privacy Policy, Terms of Service, DPA, and Accessibility Statement at abcassess.app |

[Back to top ↑](#)

---
  
[Accessibility Statement](accessibility.md) &nbsp;-&nbsp; [Data Processing Agreement](dpa.md) &nbsp;-&nbsp; [Privacy Policy](privacy-policy.md) &nbsp;-&nbsp; [Terms of Service](terms-of-service.md) &nbsp;-&nbsp; [User Guide](User-guide.md) 


[Return to Support Center](index.md)


