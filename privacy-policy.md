---
layout: default
title: abcAssess Privacy Policy
description: Updated May 18, 2026
logo: "{{ '/assets/images/full_logo.png' | relative_url }}"
---

<style>
  .btn { display: none !important; }
  header .project-tagline { margin-bottom: 2rem; }
</style>

[Return to Support Center](index.md)

---

## 1. Our Commitment to Student Privacy

#### abcAssess is built specifically for educators. We operate as a "School Official" under the Family Educational Rights and Privacy Act (FERPA) in the US and as a "Data Processor" under GDPR/UK GDPR. We do not sell student data, use it for behavioral advertising, or build marketing profiles of children.

---

## 2. Information We Collect (Data Minimization)

#### We apply a strict "Data Minimization" policy, collecting only what is essential for educational assessment: 

* **Teacher Account Data:** We use local email/password sign-in, Google Sign-In and Sign in with Apple. We collect your provider-provided name, email address, and unique identifier.
* **Student Assessment Data:** Teachers may enter student's First Name, Last Initial (optional), and Birth Month/Year (optional). Alternatively, they may enter a student id or other identifier instead of the student's name. Birth Month/Year are used solely to calculate age for assessment accuracy and avoids the collection of exact birth dates.
* **Instructional Media Storage:** To support custom and multimodal assessments (such as Spanish colors or auditory phonemic checks), the platform allows teacher to securely uplaod custom inmages and recording prompts. **We strickly exclude and prohibit the collection, request, or storage of any student photos, videos, or student-generated audio recordings.** All uploaded media must be strictly instructional.
* **Technical Logs:** We collect non-identifiable diagnostic data to maintain app stability.

---

## 3. Advanced Security & "Zero-Knowledge" Architecture

#### We utilize a "Zero-Knowledge" security model to ensure that student results remain private, even from us: 

* **Client-Side Field Level Encryption (CSFLE):** Sensitive student data, including names, are encrypted at the application level *before* being sent to the database.
* **Encryption Standards:** Data is encrypted in transit (TLS 1.3) and at rest using AES-256.
* **Database Blindness:** Because encryption keys are managed separately from the database, the developers and database administrators cannot view student names or scores in plain text within MongoDB Atlas.

---

## 4. Data Sub-Processors

#### We use a limited number of "Sub-Processors" bound by strict privacy and security standards: 

* **MongoDB Atlas:** For secure, encrypted database storage.
* **Railway:** For secure backend processing and encryption key management.
* **Vercel:** For hosting our application user interface.
* **Google/Apple:** For secure federated authentication services.
* **Resend:** For handling system transactional email operations, including password resets and feedback protocols.

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


