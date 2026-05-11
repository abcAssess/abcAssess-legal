---
layout: default
title: Privacy Policy
description: How we protect student data.
---

***Last Updated: May 5, 2026***

[Technical and Privacy FAQs](technical-and-privacy-faqs.md) | [Terms of Service](terms-of-service.md) | [User Guide](User-guide.md)

---

## 1. Our Commitment to Student Privacy

### abcAssess is built specifically for educators. We operate as a "School Official" under the Family Educational Rights and Privacy Act (FERPA) in the US and as a "Data Processor" under GDPR/UK GDPR. We do not sell student data, use it for behavioral advertising, or build marketing profiles of children.

---

## 2. Information We Collect (Data Minimization)

### We apply a strict "Data Minimization" policy, collecting only what is essential for educational assessment: 

* **Teacher Account Data:** We use local sign-in, Google Sign-In and Sign in with Apple. We collect your provider-provided name, email address, and unique identifier.
* **Student Assessment Data:** Teachers may enter student's First Name, Last Initial (optional), and Birth Month/Year (optional). Alternatively, they may enter a student id or other identifier instead of the student's name. Birth Month/Year are used solely to calculate age for assessment accuracy and avoids the collection of exact birth dates.
* **Media Exclusion:** We do not collect, request, or store any student photos, videos, or audio recordings.
* **Technical Logs:** We collect non-identifiable diagnostic data to maintain app stability.

---

## 3. Advanced Security & "Zero-Knowledge" Architecture

### We utilize a "Zero-Knowledge" security model to ensure that student results remain private, even from us: 

* **Client-Side Field Level Encryption (CSFLE):** Sensitive student data, including names, are encrypted at the application level before being sent to the database.
* **Encryption Standards:** Data is encrypted in transit (TLS 1.3) and at rest using AES-256.
* **Database Blindness:** Because encryption keys are managed separately from the database, the developers and database administrators cannot view student names or scores in plain text within MongoDB Atlas.

---

## 4. Data Sub-Processors

### We use a limited number of "Sub-Processors" bound by strict privacy and security standards: 

* **MongoDB Atlas:** For secure, encrypted database storage.
* **Railway:** For secure backend processing and encryption key management.
* **Vercel:** For hosting our application interface.
* **Google/Apple:** For secure authentication services.
* **Sentry:** For anonymous technical debugging.

---

## 5. Data Portability, Backups, and Exports

* **PDF Reports:** Teachers may generate PDF reports. These are generated in-memory and streamed directly to the user; we do not store copies of these reports on our servers.
* **Data Backups:** Teachers may download a backup of their account data, including classes, students, and assessment results. These backups are downloaded locally by the use and no copies are stored in our servers.
* **Data Responsibility:** Once data is exported or downloaded, the teacher or school assumes responsibility for its secure storage in accordance with local policies.

---

## 6. International Compliance & Rights (GDPR / CCPA / CPRA)

### We respect data rights worldwide. Depending on your location, you have the following rights: 

* **Access & Portability:** The right to request a copy of your data.
* **Rectification & Erasure:** The right to correct or delete your personal and student data.
* **Withdrawal of Consent:** The right to stop processing by deleting your account.

---

## 7. Legal Compliance (FERPA & COPPA)

*	**FERPA:** We act as a service provider; the school/teacher retains ownership of student records.
*	**COPPA:** We rely on the teacher or school to provide consent on behalf of parents for the collection of minimal student identifiers for educational purposes. 
*	**Teacher Warranty:** By using abcAssess, you warrant that you have the authority from your school/district to use this tool and enter student data.

---

## 8. Data Retention & "Cascade Deletion"

*	**Right to Delete:** Teachers can delete records or their account at any time in App Settings. 
*	**Cascade Deletion:** Upon account deletion, our system immediately triggers a "Cascade Delete," which permanently wipes all teacher profile data and all associated student records from our database. 
*	**Inactivity:** Accounts inactive for 12 months will be scheduled for deletion after a 30-day email notice.

---

## 9. Contact Information

#### &nbsp;&nbsp;&nbsp;&nbsp;Email: *noreply.abcassess@gmail.com*

---

<div align="center">
  
#### See also: [Technical and Privacy FAQs](technical-and-privacy-faqs.md) | [Terms of Service](terms-of-service.md) | [User Guide](User-guide.md)

</div>

