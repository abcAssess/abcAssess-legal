# TIMELINE.md
## abcAssess Development Milestone Log
 
*Maintained by: Danielle Andrist, Founder*
*Started: June 2026*
*Purpose: Chronological record of abcAssess development milestones. Supports establishment of human authorship, trade secret status, and development history per the abcAssess IP Assignment Agreement.*
 
---
 
### How to add an entry:
Add entries chronologically. Include the date (even approximate), milestone, and brief description. Add new entries at the bottom.
 
---
 
## 2026
 
---
 
### [DATE — best estimate] — Initial Concept
abcAssess conceived by Danielle Andrist, Pre-K teacher at Fisher School, Grand Forks, ND.
 
Problem identified: existing assessment tools required a multi-step process of physical flashcards, paper packets, and manual spreadsheet and report transfers — too slow and cumbersome for real classroom use. Concept: a mobile-first assessment tool that allows a full class assessment in under 5 minutes with automatic report generation.
 
---
 
### March 2026 — Development Begins
Development of abcAssess begins using Emergent AI as primary development tool. Danielle Andrist directs all product decisions, feature design, and educational framework from initial concept.
 
Tech stack selected: Vercel (frontend), Railway (backend), MongoDB Atlas (database), Cloudflare (domain), Resend (email), GitHub (repository).
 
---
 
### [DATE] — Core Data Model Established
Student data model finalized: first name only required, last initial optional, birth month and year optional. Decision made to minimize PII collection from the start rather than collect broadly and restrict later.
 
---
 
### [DATE] — Assessment Flow First Working Version
Core assessment flow implemented: flashcard display, Known/Unknown response buttons, progress bar, results screen with score and items missed.
 
---
 
### [DATE] — Built-In Assessments Added
Built-in assessment categories implemented: Uppercase Letters, Lowercase Letters, Letter Sounds, Numerals (0-9), Numerals (10-30), Colors, Shapes, Beginning Sounds.
 
Font selected for flashcards — single-story 'a', standard manuscript 'g', uppercase 'I' with serifs — to match classroom print standards taught to Pre-K students.
 
---
 
### [DATE] — Custom Assessment Builder Added
Custom assessment creator implemented allowing teachers to build their own assessment categories with custom items, randomization settings, and optional audio prompts.
 
---
 
### [DATE] — Reports First Version
Teacher Report, Parent Report ("Learning Journey"), and Progress Report implemented as PDF downloads with customizable options.
 
---
 
### [DATE] — Tracking Chart Implemented
Class-wide tracking chart implemented showing student proficiency across all assessment types.
 
---
 
### [DATE] — Multi-Teacher Access Added
Co-teacher and assistant teacher invitation and access system implemented. Two permission levels: Co-Teacher (full access) and Assistant (assessment only).
 
---
 
### [DATE] — Student Transfer System Implemented
Student and class transfer system implemented with acceptance requirement, keep/archive/remove options, and sending to external teachers.
 
---
 
### [DATE] — Manual Entry Added
Manual assessment entry flow implemented for teachers who assess on paper or with physical flashcards and need to log results retroactively.
 
---
 
### [DATE] — Offline Support Implemented
Offline assessment capability added. Two-layer local persistence system: in-flight draft auto-save to AsyncStorage every second during assessment, plus completed-but-unsynced queue that persists through app close and device restart.
 
---
 
### [DATE] — Monitoring Stack Configured
Uptime Robot configured for app, root domain, API health, and Railway direct URL. Sentry configured for frontend and backend error monitoring with student data masking. PostHog configured for product analytics.
 
---
 
### May 2026 — First Real Classroom Use
Danielle Andrist uses abcAssess with her own Pre-K class at Fisher School during end-of-year assessment windows. 18 students assessed across multiple assessment types.
 
Key insight discovered: keyboard shortcuts allow teacher to record responses invisibly — students cannot tell when they answer incorrectly, preventing discouragement. Students describe the experience as "playing a game on the teacher's phone."
 
Key insight discovered: phone is the primary device for classroom assessment — not tablet. Opportunistic assessments conducted on playground, in hallway, during snack time.
 
---
 
### May 30, 2026 — Legal Documents v1.0 Published
Five core legal documents drafted and published to abcAssess support center:
- Privacy Policy v1.0
- Terms of Service v2.0
- Data Processing Agreement v2.0
- Technical & Privacy FAQ v2.0
- Accessibility Statement v2.0
---
 
### June 2026 — Beta Launch
abcAssess enters public beta. Initial beta cohort: 4 active teachers. Beta participants using tool with real students in real classrooms. All beta access provided free of charge.
 
Connections established with several early childhood centers interested in beta participation. Target: expanded beta cohort for Fall 2026 school year.
 
---
 
### June 2026 — Comprehensive UX Review
Full review of all app screens conducted. Major product decisions documented:
- Colorblind accessibility symbol system designed and implemented (✓ ~ ! —)
- Reports page restructure planned
- Settings page reorganization planned
- Subscription model designed (Monthly and Annual at launch, Academic Year Plan deferred to Fall 2027)
- International expansion decided: US, Canada, Australia, New Zealand, UK, Ireland
- 60+ item Emergent task list compiled
---
 
### June 2026 — Legal Documents v1.2 / v2.2 / v2.1
All five legal documents updated:
- Privacy Policy v1.2 — international compliance, backup policy, PostHog/Sentry added
- Terms of Service v2.2 — subscription section added, international compliance, transfer expiry
- Data Processing Agreement v2.1 — all six markets, PostHog/Sentry added, transfer expiry
- Technical & Privacy FAQ v2.1 — expanded to 21 questions, international coverage, offline detail
- Accessibility Statement v2.1 — international legal frameworks, symbol system documented
---
 
### June 2026 — IP Documentation Repository Created
Private GitHub compliance repository created containing:
- DECISIONS.md — product and design decision log
- PROMPTS.md — AI direction and creative contribution log
- TIMELINE.md — this document
- IP Assignment Agreement (draft — awaiting LLC formation)
- All legal documents
- Image Asset Tracker
- Pricing & Subscription Model
- Pre-Launch Master Checklist
---
 
### [DATE] — PostHog Analytics Live
PostHog Product Analytics and Web Analytics configured and verified. Events firing correctly with no student PII captured. IP anonymization enabled. Person profiles disabled.
 
---
 
### [DATE] — Beginning Sounds Images Sourced
Images sourced for Beginning Sounds assessment from [source]. All images verified as Pixabay License / commercial use approved. Logged in Image Asset Tracker.
 
---
 
### [DATE] — LLC Registered
abcAssess LLC formally registered with the State of North Dakota.
Filing number: [add]
Registered agent: [add]
Operating Agreement executed.
 
---
 
### [DATE] — IP Assignment Agreement Signed
Intellectual Property Assignment Agreement executed between Danielle Andrist (individual) and abcAssess LLC. All IP in abcAssess transferred to the LLC.
 
---
 
### [DATE] — Insurance Purchased
Business insurance policies purchased:
- General Liability: [carrier], [coverage amount]
- Errors & Omissions: [carrier], [coverage amount]
- Cyber Liability: [carrier], [coverage amount]
---
 
### [DATE] — Stripe Payment Processing Configured
Stripe account configured with Monthly Plan ($5/month) and Annual Plan ($50/year). 14-day free trial configured. Stripe Tax enabled for VAT (UK/Ireland) and GST (Australia/New Zealand). 48-hour refund window configured.
 
---
 
### [DATE] — Attorney Review Complete
Legal documents reviewed by [attorney name/firm]. Changes implemented: [note any changes made].
 
---
 
### [DATE] — EU and UK Representatives Appointed
EU GDPR Representative appointed: [name/service]
UK GDPR Representative appointed: [name/service]
 
---
 
### [DATE] — App UX Revamp Complete
All 60+ items from June 2026 Emergent task list implemented and verified. Key changes:
- Fullscreen assessment mode
- Colorblind symbol system
- Reports page restructure
- Settings page restructure
- Sticky save bars throughout
- Manual entry tile grid
- Assessment picker improvements
---
 
### [DATE] — Mobile and Tablet Review Complete
Full mobile and tablet review completed. All screens verified across iPhone, Android, iPad, and Android tablet. Date format localization confirmed for all six markets.
 
---
 
### [DATE] — Security Review Complete
Pre-launch security and code quality review completed. Staging environment verified. Automated database backup verification confirmed. Offline sync end-to-end test passed.
 
---
 
### [DATE] — User Guide Published
abcAssess User Guide published to support center covering: Getting Started, Assessment Flow, Understanding Your Data, Managing Your Class, Reports, Assessment Settings, Privacy & Student Data, FAQs.
 
---
 
### [DATE — Fall 2026] — Official Launch
abcAssess officially launches for Fall 2026 school year.
- Monthly Plan ($5/month) available
- Annual Plan ($50/year) available
- 14-day free trial for all new accounts
- Available in: US, Canada (English), Australia, New Zealand, UK, Ireland
- Beta participants notified of free year
---
 
## Future Milestones (Planned)
 
---
 
### Spring 2027 — Academic Year Plan Announced
Academic Year Plan announced to existing users. Pre-registration opens for Fall 2027 launch. Northern Hemisphere campaign: May 2027. Southern Hemisphere campaign: October/November 2027.
 
---
 
### Fall 2027 — Academic Year Plan Launches
Academic Year Plan ($40/year) launches with Summer Transition Mode. Hemisphere-specific campaigns run.
 
---
 
### [DATE] — First School/District Contract
First formal school or district contract signed. Data Processing Agreement executed with institution.
 
---
 
### [DATE] — MongoDB Atlas EU Region Cluster
EU/UK region database cluster configured for UK and Ireland users as those markets grow.
 
---
 
*This document is updated as milestones are reached.*
*Last updated: June 2026*
 
