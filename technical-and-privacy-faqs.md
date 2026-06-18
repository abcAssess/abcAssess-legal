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
22. [What happens if my subscription lapses?](#21-what-happens-if-my-subscription-lapses)
23. [Is abcAssess available outside the United States?](#22-is-abcassess-available-outside-the-united-states)

---

# Privacy and Legal Compliance

## 1. Is abcAssess FERPA and COPPA compliant?

### Yes - fully.

#### abcAssess acts as a "School Official" under FERPA, meaning we process student data only for legitimate educational purposes and only under the direction of the teacher or school. We practice strict data minimization: to identify students, we collect only a first name and last initial (optional) and birth month and year (optional, stored as a YYYY-MM value). We never collect full legal names, exact birth dates, home addresses, or any student-generated media such as photos or videos. Under COPPA, we never use student data for advertising, profiling, or any commercial purpose. Students do not create accounts or interact with the platform directly.

---

## 2. Is abcAssess compliant with GDPR, UK GDPR, or other international privacy laws?

### Yes — we are designed for compliance across all markets we serve.

#### abcAssess currently serves educators in the United States, Canada (English-speaking provinces), Australia, New Zealand, the United Kingdom, and Ireland.

- **EU users:** abcAssess complies with GDPR and acts as a Data Processor under GDPR Article 28. We use Standard Contractual Clauses (SCCs) for data transfers outside the EEA. We intend to appoint an EU Representative as required by GDPR Article 27 — this will be updated in our DPA when the appointment is made.
   **UK users:** abcAssess complies with UK GDPR. We use the UK International Data Transfer Agreement (IDTA) for applicable transfers. We intend to appoint a UK Representative as required by UK GDPR Article 27.
- **Canadian users:** abcAssess complies with PIPEDA.
- **Australian users:** abcAssess complies with the Privacy Act 1988 (Cth) and Australian Privacy Principles (APPs).
- **New Zealand users:** abcAssess complies with the Privacy Act 2020.

Our full Data Processing Agreement, which satisfies GDPR Article 28 requirements and addresses all applicable jurisdictions, is available upon request at legal@abcassess.app.

---

## 3. Does abcAssess use student data to train AI or machine learning models?

### Never — this is explicitly prohibited.

#### Student data entered into abcAssess is never used to train, fine-tune, or improve any artificial intelligence or machine learning model — by us or by any third party. This prohibition is written into our Data Processing Agreement and our sub-processor contracts. Student data is used solely to deliver the assessment features you have requested. This will not change without explicit notice and consent.

---

## 4. Who owns the data I enter into abcAssess?

### You do — or your school district does.

#### abcAssess does not claim ownership of any student records or assessment data you enter. Under FERPA, student education records belong to the school or district. We are a service provider — we hold and process your data on your behalf. We will never sell, share, or use student data for any purpose outside of delivering the Service to you.

---

## 5. Can my school administrator or district see my classroom data?

### No — your classroom data is isolated to your account.

#### abcAssess enforces strict multi-tenant data isolation at the server level. Records from your classroom are filtered through server-side controls tied to your unique account identifier. No other teacher, administrator, or district user can access your classroom data through the platform unless you explicitly invite them as a co-teacher or assistant on your account. abcAssess staff cannot view student names or scores in plain text due to our client-side encryption architecture.

#### School-level or district-level administrator accounts are not currently available. Teachers control their own data independently.

- **IT Administrator note:** Data isolation is enforced through server-side query middleware using unique organizational and teacher identifiers. Records from one account cannot be accessed by another account at the database query level, independent of application-layer controls.

---

## 6. Do you use student data for advertising?

### Never.

#### We do not engage in behavioral advertising, and we do not build marketing profiles based on student performance or information.

---

## 7. Does this app work offline?

### Yes.

#### You can record assessments offline, and the data will sync securely to our servers once you have a stable internet connection.

---

## 8. How do you track application usage?

### We utilize privacy-first, event-based analytics to measure app performance, track system stability, and understand which tools educators use most. 

#### This telemetry logs only high-level actions (such as when an assessment is completed or when a PDF report is generated) and does not harvest any Personally Identifiable Information (PII) from teachers or students.

---

## 9. Where is my data hosted, and who handles it?

### Our data layer is deployed securely via MongoDB Atlas. The frontend user interface is hosted using Vercel, and our supporting application backend environments run on Railway. 

#### All critical infrastructure configurations, database keys, and environment variables are strictly managed through secure provider dashboards rather than being exposed within raw application files.

---

## 10. Are communications from abcAssess secure?

### Yes. 

#### All outbound transactional notifications and system updates are managed using dedicated subdomains protected by strict network security policies. This includes standard HSTS data defenses, automated DMARC protocols, and unified SPF verification records to prevent email spoofing and guarantee that any system messages originating from our code are authentic and securely transmitted.
---

## Contact

#### &nbsp;&nbsp;&nbsp;&nbsp;E-mail: [hello@abcassess.app](mailto:hello@abcassess.app)

*We aim to respond to all inquiries within 2 business days.*

---
  
[Accessibility Statement](accessibility.md) &nbsp;-&nbsp; [Data Processing Agreement](dpa.md) &nbsp;-&nbsp; [Privacy Policy](privacy-policy.md) &nbsp;-&nbsp; [Terms of Service](terms-of-service.md) &nbsp;-&nbsp; [User Guide](User-guide.md) 


[Return to Support Center](index.md)


