---
layout: default
title: Privacy Policy
description: Version 1.2 · Updated June 9, 2026
---

<style>
  .btn { display: none !important; }
  header .project-tagline { margin-bottom: 2rem; }
</style>

[Return to Support Center](index.md)

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

---

## 2. Information We Collect (Data Minimization)

#### We apply a strict data minimization policy, collecting only what is essential for educational assessment functionality.

- **2.1 Teacher Account Data**  
  We support local email/password sign-in, Google Sign-In, and Sign in with Apple. We collect your provider-supplied name, email address, and unique account identifier. We do not collect payment information, phone numbers, or physical addresses.

- **2.2 Student Assessment Data**  
  Teachers may enter the following minimal student identifiers: a student's first name and last initi/al (optional), birth month and year (optional, used solely to calculate age for assessment accuracy), or alternatively a student ID number or other non-name identifier. We deliberately avoid collecting exact birth dates, full legal names, addresses, or any other personally identifiable information beyond what is listed above.

- **2.3 Instructional Media**
  To support custom and multimodal assessments (such as color identification or auditory phonemic checks), teachers may securely upload custom instructional images and audio recording prompts. All uploaded media must be strictly instructional in nature. We explicitly prohibit the collection, upload, or storage of any student photos, student videos, or student-generated audio recordings. Any media upload that appears to contain student likeness or student-generated content may be removed without notice.

- **2.4 Technical and Diagnostic Logs**
  We collect non-identifiable diagnostic and performance data solely to maintain application stability and improve service reliability. This data does not include student names, scores, or identifiable information and is not linked to individual user accounts.

* **2.5 Cookies and Tracking**
  abcAssess does not use third-party advertising cookies, behavioral tracking scripts, or cross-site tracking technologies. We use only technically necessary session cookies required for authentication and application function. We do not use Google Analytics, Meta Pixel, or similar behavioral tracking tools. If this changes in a future version, this policy will be updated and users will be notified in advance.

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

---

## 5. Data Portability, Backups, and Exports

* **PDF Reports:** Teachers may generate custom PDF reports, individual deep-dives, or class-wide summaries. These are generated on-the-fly and streamed directly to the browser session; we do not store copies of these reports on our cloud servers.
* **Data Backups:** Teachers may download an on-demand full backup of their account data, including classes, students, and assessment histories. These files are downloaded locally by the user; no duplicate copies are cached or maintained on our systems.
* **Data Responsibility:** Once data is exported or downloaded, the teacher or school assumes full responsibility for its secure storage in accordance with local policies.

---

## 6. International Compliance & Rights (GDPR / CCPA / CPRA)

#### We respect data rights worldwide. Depending on your regional jurisdiction, you have the following rights: 

* **Access & Portability:** The right to request a complete copy of your structural account data.
* **Rectification & Erasure:** The right to correct inaccuracies or delete your personal and classroom data.
* **Withdrawal of Consent:** The right to immediately halt processing by choosing to delete your account.

---

## 7. Legal Compliance (FERPA & COPPA)

*	**FERPA:** We act as a service provider; the school/teacher retains complete legal ownership of all student records.
*	**COPPA:** We rely on the teacher or school to provide consent on behalf of parents for the collection of minimal student identifiers for educational purposes. 
*	**Teacher Warranty:** By using abcAssess, you warrant that you have the authority from your school/district to use this tool and log student performance data.

---

## 8. Data Retention & "Cascade Deletion"

*	**Right to Delete:** Teachers can delete individual records or their account at any time within the App Settings. 
*	**Cascade Deletion:** Upon account deletion, our backend systems immediately trigger an automated "Cascade Delete," which permanently wipes all teacher profile assets and all associated student records from our database. 
*	**Inactivity:** Accounts remaining completely inactive for 12 consectuive months will automatically be scheduled for archival deletion after a 30-day email warning notice.

---

## Contact

#### &nbsp;&nbsp;&nbsp;&nbsp;E-mail: [hello@abcassess.app](mailto:hello@abcassess.app)

*We aim to respond to all inquiries within 2 business days.*

---

[Accessibility Statement](accessibility.md) &nbsp;-&nbsp; [Data Processing Agreement](dap.md) &nbsp;-&nbsp; [Technical FAQs](technical-and-privacy-faqs.md) &nbsp;-&nbsp; [Terms of Service](terms-of-service.md) &nbsp;-&nbsp; [User Guide](User-guide.md)


[Return to Support Center](index.md)


