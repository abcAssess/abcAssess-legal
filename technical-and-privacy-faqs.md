---
layout: default
title: Technical and Privacy FAQs
description: abcAssess
---

<style>
  .btn { display: none !important; }
  header .project-tagline { margin-bottom: 2rem; }
</style>

<p align="center">
  <img src="{{ '/assets/images/full_logo.png' | relative_url }}" alt="abcAssess Logo" width="120" />
</p>

[Return to Support Center](index.md)

---

## 1. Is abcAssess FERPA and COPPA compliant?

### Yes.

#### We act as a "School Official" under FERPA, and we assist schools in COPPA compliance by practicing strict Data Minimization. To identify students safely, we only collect a student's first name and their birth month/year (stored as a generic YYYY-MM string). We never collect full names, exact birthdays, or any student media like photos or videos.

---

## 2. How is student data secured?

### Data privacy is built directly into our database architecture. 

#### We enforce strict application-level multi-tenant isolation using unique organizational and teacher identifiers. This means all classroom data is tightly filtered through server-side query middleware so that records from one classroom can never be accessed or read by another. All data is encrypted in transit using industry-standard TLS protocols and encrypted at rest within our secured database environment.

---

## 3. Who owns the data I enter?

### You (the educator) or your school district own all student data.

#### abcAssess does not claim ownership of student records, nor do we ever sell or share data with third-party advertisers.

---

## 4. Can I export my data?

### Absolutely.

#### You can generate PDF reports for individual students or download data backups directly from the app for your own archives.

---

## 5. What happens if I delete my account?

### We utilize a Cascade Deletion process.

#### When you delete your account through the App Settings, your profile and all associated student records are permanently wiped from our servers.

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


