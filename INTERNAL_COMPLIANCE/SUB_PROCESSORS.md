# abcAssess Third-Party Sub-Processor Registry
Last Reviewed: May 18, 2026

To deliver secure, real-time early childhood assessment services, abcAssess utilizes the following infrastructure sub-processors. Each vendor has been vetted for compliance with FERPA and COPPA data privacy frameworks.

| Vendor Name | Corporate Purpose | Data Transmitted | Data Security Standard |
| :--- | :--- | :--- | :--- |
| **Vercel Inc.** | Application Interface Frontend Hosting | User page-views, non-identifiable web navigation events. | SOC 2 Type II / ISO 27001 |
| **Railway** | API Backend Application Server Management | Secure transit pipeline for encrypted JSON payloads. | SOC 2 Type II |
| **MongoDB Atlas** | Database Architecture & Document Cloud Storage | Encrypted student identifiers (first names/birth months) and raw metrics. | SOC 2 / ISO 27001 / AES-256 at-rest |
| **Resend** | Transactional Outbound Email Dispatch | Teacher authentication emails, password resets, notification headers. | SOC 2 Type II Compliance |
