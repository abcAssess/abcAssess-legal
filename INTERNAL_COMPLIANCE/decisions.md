# DECISIONS.md
## abcAssess Product & Design Decision Log
 
*Maintained by: Danielle Andrist, Founder*
*Started: June 2026*
*Purpose: Documents original creative, pedagogical, and business decisions made in the development of abcAssess. Supports establishment of human authorship and trade secret status per the abcAssess IP Assignment Agreement.*
 
---
 
### How to add an entry:
Add new entries at the top of the relevant section. Be specific — the more detail the better, especially where teaching expertise drove the decision.
 
---
 
## Pedagogy & Assessment Design
 
---
 
### Keyboard Shortcuts for Invisible Scoring
**Date:** May 2026 (discovered in classroom) / June 2026 (documented)
**Decision:** Added left/right arrow keyboard shortcuts for Unknown/Known responses during live assessments, in addition to on-screen buttons.
**Alternatives considered:** On-screen buttons only — standard approach for mobile apps.
**Reasoning:** Discovered through direct classroom use with Pre-K students in May 2026. When using on-screen buttons, students could see the teacher's reaction and figure out when they answered incorrectly, which was discouraging. With keyboard shortcuts, the teacher can record responses invisibly — to the student it looks like the teacher is simply watching them proudly while cards appear. Students described it as "playing a game on the teacher's phone" with no awareness they were being assessed or that they got answers wrong.
**Impact:** Core assessment UX, used in every live assessment session. Also identified as a key marketing differentiator — no competing tool appears to have thought of this.
**Source:** Direct classroom experience assessing Pre-K students; understanding of child psychology around failure and discouragement in early childhood settings.
 
---
 
### Font Selection for Assessment Flashcards
**Date:** [Add date when implemented]
**Decision:** Selected a specific font for assessment flashcards that includes a single-story lowercase 'a', a standard manuscript 'g', and an uppercase 'I' with serifs (horizontal lines at top and bottom).
**Alternatives considered:** Default system fonts, standard sans-serif fonts (e.g. Helvetica, Roboto).
**Reasoning:** Young children learning letter recognition are taught specific letterforms in manuscript print. Many common digital fonts use a double-story 'a' (like a typed 'a') which differs from the handwritten/print 'a' that Pre-K and Kindergarten students learn. Similarly, the standard typed 'g' differs from the manuscript 'g' taught in early literacy. An uppercase 'I' without serifs is indistinguishable from a lowercase 'l' in many fonts. Using the wrong font would actually invalidate the assessment for some students who know their letters but don't recognize the digital version. Spent significant time finding a font that matched classroom print standards.
**Impact:** Assessment validity — directly affects accuracy of letter recognition assessments. A developer would never have identified this without early childhood literacy expertise.
**Source:** Direct teaching experience + knowledge of early literacy instruction and manuscript print standards.
 
---
 
### Flashcard as the Assessment Interface
**Date:** [Add date — initial product conception]
**Decision:** Designed the core assessment interface as a digital flashcard — one item at a time, large and centered, with simple Known/Unknown response buttons.
**Alternatives considered:** List-based assessment, grid-based assessment, quiz-style interface.
**Reasoning:** Mirrors the physical flashcard assessment method already used by most early childhood teachers. Reduces learning curve — teachers immediately understand the interaction because it matches their existing practice. Also appropriate for the assessment context: one item at a time prevents students from seeing upcoming items or looking ahead.
**Impact:** Core product design — shapes the entire assessment experience.
**Source:** 20 years of classroom experience, 13 years specifically in Pre-K assessment.
 
---
 
### "Known/Unknown" Language Instead of "Correct/Incorrect"
**Date:** [Add date]
**Decision:** Used "Known" and "Unknown" as the response labels rather than "Correct/Incorrect," "Right/Wrong," or "Yes/No."
**Alternatives considered:** Correct/Incorrect (standard quiz language), Right/Wrong, Yes/No, Got It/Needs Work.
**Reasoning:** Early childhood assessment philosophy emphasizes developmental progress rather than pass/fail judgment. "Known" and "Unknown" frames the assessment as documenting what a child knows at this moment, not grading their performance. More appropriate for Pre-K developmental assessment context and consistent with how early childhood educators are trained to think about assessment.
**Impact:** Assessment UX language, report language, parent-facing communication.
**Source:** MS in Early Childhood Education + 13 years Pre-K teaching experience + knowledge of developmentally appropriate practice.
 
---
 
### Audio Prompts for Beginning Sounds Assessment
**Date:** [Add date]
**Decision:** Added optional audio prompts for the Beginning Sounds assessment that show a picture (e.g. a ball) and can say "What is the first sound in the word 'ball'?"
**Alternatives considered:** Visual only (show picture, no audio), text only, audio only.
**Reasoning:** Showing a picture without audio creates ambiguity — a picture of a bat could be a baseball bat or a flying bat, both starting with /b/ but representing different phonemic contexts. The audio prompt anchors the specific word being used so the assessment is unambiguous. Combining visual and audio also supports diverse learners including children with different learning styles.
**Impact:** Beginning Sounds assessment accuracy and accessibility.
**Source:** Knowledge of phonemic awareness assessment best practices in early childhood literacy instruction.
 
---
 
### Teacher-Recorded Audio Option
**Date:** [Add date]
**Decision:** Added the ability for teachers to record their own audio prompts for custom assessment items, in addition to system-provided audio.
**Alternatives considered:** System audio only, text-to-speech only.
**Reasoning:** Three specific use cases identified from teaching experience: (1) Dual language learners — a teacher could record prompts in Spanish for students still acquiring English; (2) Student comfort — hearing a familiar teacher's voice is more comfortable for young children than a generic recorded voice; (3) Special education — specific phrasing may be required for a student's IEP and needs to be consistent across all assessments.
**Impact:** Custom assessment builder, accessibility, dual language learner support.
**Source:** Direct classroom experience with dual language learners and students with IEPs.
 
---
 
### Assessment Randomization Option
**Date:** [Add date]
**Decision:** Added an optional randomization setting that shuffles item order during assessment.
**Alternatives considered:** Fixed order only, always random.
**Reasoning:** Fixed order allows students to memorize the sequence rather than actually knowing the content — a student who has been assessed multiple times might learn "the third card is always C" without being able to identify the letter independently. Randomization ensures each assessment genuinely measures knowledge. Made it optional rather than mandatory because some teachers prefer sequential order for specific pedagogical reasons.
**Impact:** Assessment validity, assessment settings.
**Source:** Knowledge of assessment design principles and how young children respond to repeated assessments.
 
---
 
### Individual Assessment Overrides Per Student
**Date:** [Add date]
**Decision:** Built a system allowing teachers to override class-wide assessment settings for individual students — enabling or disabling specific assessment types per child.
**Alternatives considered:** Class-wide settings only, no individual customization.
**Reasoning:** In real Pre-K classrooms, students are at vastly different developmental stages. A student who just joined the class might not be ready for letter sounds while others are. A student with a specific IEP goal might need only certain assessments tracked. Forcing all students through the same assessment set doesn't reflect how early childhood educators actually differentiate instruction.
**Impact:** Core assessment architecture, Manage Assessments feature.
**Source:** 13 years of Pre-K teaching experience with diverse learners at different developmental stages.
 
---
 
### "What's Next" Screen After Assessment Completion
**Date:** [Add date]
**Decision:** Added a "What's Next" screen after every completed assessment offering four exit paths: Another Assessment Same Student, Same Assessment Next Student, Return to Student Profile, Return to Student List.
**Alternatives considered:** Auto-return to student list, auto-return to student profile, single back button.
**Reasoning:** Teachers assess in different workflow patterns. Some go through all assessments for one student at a time. Some go through the whole class on one assessment type. Some finish one and check the student profile before deciding what to do next. A single back button would force all teachers into one workflow that doesn't match how they actually work. Four clearly labeled options with descriptive subtitles serve all real use cases without requiring teachers to think.
**Impact:** Assessment flow UX, teacher workflow efficiency.
**Source:** Direct teaching experience + classroom observation of different assessment workflow patterns.
 
---
 
### Items to Practice Shown on Results Screen
**Date:** [Add date]
**Decision:** Display the specific items a student answered incorrectly on the assessment results screen under "Items to Practice."
**Alternatives considered:** Score only, link to student profile for details.
**Reasoning:** A teacher sitting with a student right after assessment needs to immediately know which specific letters or sounds to focus on — not just a percentage score. Showing the specific items means the teacher can make an immediate instructional decision or note it for targeted practice without navigating to another screen. Actionable in the moment.
**Impact:** Assessment results UX, instructional utility.
**Source:** Direct teaching experience — knowing which specific items to target is more useful than an overall score immediately after assessing.
 
---
 
### Opportunistic Assessment Design — Phone First
**Date:** May 2026 (discovered in classroom)
**Decision:** Designed the assessment flow to work fully on a phone, not just on tablets or computers.
**Alternatives considered:** Tablet-first design, desktop-first design.
**Reasoning:** Discovered through real classroom use that the most valuable assessment moments happen opportunistically — a student sitting out at recess, a quiet moment in the hallway, snack time. Teachers always have their phone in their pocket. They don't always have a tablet. A tool that requires a tablet would miss these high-value moments. During May 2026 classroom testing, conducted assessments with the entire class using only a phone.
**Impact:** Core product positioning, mobile design priority, marketing copy.
**Source:** Direct classroom experience — "To your students, it's a game on your phone. To you, it's data."
 
---
 
### Manual Entry Flow
**Date:** [Add date]
**Decision:** Built a manual entry flow allowing teachers to log assessment results after the fact — for assessments completed on paper, with physical flashcards, or in situations where the app wasn't available.
**Alternatives considered:** Digital assessment only, no retroactive entry.
**Reasoning:** Real teaching practice involves assessments that happen in various contexts. A teacher doing a paper-based reading assessment, a substitute teacher using physical flashcards, or an assessment completed before the teacher had abcAssess — all represent legitimate data that should be capturable. Excluding manual entry would make abcAssess an incomplete record of student progress.
**Impact:** Manual entry feature, data completeness.
**Source:** Direct teaching experience with multiple assessment modalities.
 
---
 
### Select All Then Uncheck Workflow for Manual Entry
**Date:** June 2026 (identified during real data entry in May 2026)
**Decision:** Manual entry defaults to all items unselected with a Select All option, rather than all selected or a neutral state.
**Alternatives considered:** Default all selected, default all unselected without Select All, requiring individual selection for each item.
**Reasoning:** Discovered during real classroom data entry in May 2026. For a student who got 7/26 correct, checking 7 boxes is faster than unchecking 19. For a student who got 20/26, Select All and uncheck 6 is much faster. Both workflows are efficient. The combination of "start empty with Select All available" serves both high-scoring and low-scoring student entry efficiently.
**Impact:** Manual entry UX efficiency.
**Source:** Direct experience entering assessment data for a class of 18 students.
 
---
 
## Privacy & Data Design
 
---
 
### Student Data Minimization — First Name Only Required
**Date:** [Add date — initial product conception]
**Decision:** Required only a first name to create a student record. Last initial, birth month, and birth year are all optional. No full names, no exact birth dates, no addresses, no photos.
**Alternatives considered:** Full name required (standard for most edtech), full birth date, more comprehensive student profiles.
**Reasoning:** FERPA and COPPA compliance — minimizing PII reduces risk for teachers and schools. Also reduces barrier to adoption since teachers may be cautious about entering full student information into third-party tools. First name is sufficient for classroom use. A teacher could use a number, a nickname, or any identifier — the system doesn't care. Deliberately chose not to collect what we don't need.
**Impact:** Core data model, privacy policy, COPPA compliance, marketing positioning ("we collect the minimum").
**Source:** Awareness of school data privacy concerns + FERPA/COPPA knowledge + teaching experience.
 
---
 
### No Day Field for Birth Date
**Date:** [Add date]
**Decision:** Birth date collection limited to month and year only — no day field available.
**Alternatives considered:** Full birth date (day/month/year), no birth date at all.
**Reasoning:** Day of birth is not needed for any assessment functionality — month and year is sufficient for age-grouping and developmental benchmarking. Removing the day field reduces the specificity of PII collected without any loss of functionality. A month/year combination is significantly less individually identifying than a full birth date, especially combined with a first name only.
**Impact:** Data model, privacy policy, COPPA compliance, FERPA risk reduction.
**Source:** Privacy-first design philosophy + knowledge of what data is actually needed for educational assessment.
 
---
 
### Students Don't Create Accounts or Interact With the Platform
**Date:** [Add date — initial product conception]
**Decision:** Students have no accounts, no login, no direct interaction with abcAssess in any form.
**Alternatives considered:** Student-facing assessment interface, student login for self-assessment.
**Reasoning:** COPPA compliance — direct collection of personal information from children under 13 triggers significant legal requirements. By keeping abcAssess entirely teacher-facing, we eliminate this risk entirely. Also appropriate for the age group — Pre-K students are 3-5 years old and would not be operating software independently.
**Impact:** Core product architecture, COPPA compliance, privacy policy.
**Source:** Knowledge of COPPA requirements + developmental appropriateness for Pre-K age group.
 
---
 
### Explicit Prohibition on Student Photos, Videos, and Audio Recordings
**Date:** [Add date]
**Decision:** Explicitly prohibited the upload, storage, or collection of any student-generated media including photos, videos, facial recognition data, and voice recordings.
**Alternatives considered:** Allow teacher-uploaded student photos for identification, allow student voice recordings for reading assessments.
**Reasoning:** Student biometric data represents the highest risk category of student PII. Photos enable facial recognition. Voice recordings are biometric data. These categories attract the most regulatory scrutiny and create the most significant liability. The assessment functionality of abcAssess does not require any of these — teachers can identify students by name and avatar. The prohibition is absolute and documented in legal agreements.
**Impact:** Data model, privacy policy, DPA, Terms of Service, instructional media restrictions.
**Source:** Privacy-first design + COPPA + FERPA + awareness of biometric data legal risk.
 
---
 
### Database-Blind Encryption Architecture
**Date:** [Add date]
**Decision:** Implemented client-side field-level encryption (CSFLE) so that student data is encrypted before it reaches the database — meaning even abcAssess staff cannot read student names or scores in plain text.
**Alternatives considered:** Standard database encryption (at-rest only), application-layer encryption without key separation.
**Reasoning:** Standard encryption protects data from external attackers but not from the database provider or internal staff. A database-blind architecture means that even in the event of a database breach, student data is unreadable. Also means abcAssess can credibly state that we cannot access student data — which is both true and a significant trust signal for schools and districts.
**Impact:** Security architecture, trust positioning, privacy policy, DPA.
**Source:** Privacy-first design philosophy + understanding of what schools and districts need to trust an edtech vendor.
 
---
 
### Backup FERPA Acknowledgment Dialog
**Date:** June 2026
**Decision:** Required teachers to check a confirmation checkbox acknowledging their FERPA responsibility before downloading a backup file.
**Alternatives considered:** No confirmation, simple "are you sure" dialog, terms acceptance at account creation only.
**Reasoning:** Backup files can be imported into any abcAssess account, creating a potential vector for student data to move to unauthorized parties. Requiring explicit acknowledgment at the moment of download creates a logged record of the teacher's confirmation of responsibility and ensures they are aware of their obligations at the exact moment they're about to exercise them.
**Impact:** Backup download flow, FERPA compliance, database logging.
**Source:** Privacy-first design + understanding of FERPA teacher responsibility + legal documentation needs.
 
---
 
### Transfer Acceptance Requirement
**Date:** [Add date]
**Decision:** Student record transfers require explicit acceptance by the receiving teacher before any data moves. No silent or automatic transfers.
**Alternatives considered:** Automatic transfer on send, transfer with simple notification.
**Reasoning:** Student data should never move to another account without the receiving party actively accepting responsibility for it. Requiring acceptance creates a clear moment of data custody transfer, creates an auditable record, and ensures the receiving teacher is aware they are accepting student records and the associated responsibilities.
**Impact:** Transfer flow, FERPA compliance, DPA.
**Source:** FERPA data custody principles + privacy-first design.
 
---
 
### 30-Day Transfer Request Expiry
**Date:** June 2026
**Decision:** Pending student and class transfer requests automatically expire after 30 days if not accepted.
**Alternatives considered:** No expiry, manual cancellation only, 14-day expiry, 60-day expiry.
**Reasoning:** A pending transfer represents student data in a kind of limbo state — the sending teacher may have chosen to archive or delete their copy, contingent on the transfer being accepted. Without an expiry, transfers could float indefinitely, creating ambiguity about data ownership and preventing teachers from cleaning up their accounts. 30 days is long enough for a receiving teacher to respond while short enough to prevent indefinite limbo.
**Impact:** Transfer flow, Privacy Policy Section 9.5, Terms of Service, DPA.
**Source:** Privacy-first design + practical data governance.
 
---
 
## UX & Product Design
 
---
 
### Colorblind Accessibility Symbol System
**Date:** June 2026
**Decision:** Implemented a combined color AND symbol system for the assessment tracking chart so that proficiency information is never conveyed by color alone: ✓ Proficient (sage), ~ Developing (amber), ! Emerging (terracotta), — Not Applicable (grey).
**Alternatives considered:** Color only (red/yellow/green), color + text labels, color + icons.
**Reasoning:** Color-only systems exclude users with color vision deficiencies — approximately 8% of men and 0.5% of women have some form of colorblindness. In a classroom context, teachers, administrators, and specialists reviewing reports may have color vision differences. Also meets WCAG 2.1 Success Criterion 1.4.1 (Use of Color). The symbol system was designed so that even in a black and white printout, proficiency levels remain distinguishable.
**Impact:** Tracking chart, assessment history, reports, accessibility statement.
**Source:** Accessibility awareness + UX review with Claude June 2026.
 
---
 
### Dark Mode as Default, Light Mode as Opt-In
**Date:** June 2026
**Decision:** Set dark mode as the default experience with light mode available as an opt-in setting.
**Alternatives considered:** Light mode default (industry standard), system preference detection, no mode switching.
**Reasoning:** After reviewing both modes in detail, dark mode was significantly more polished and visually cohesive. The navy/slate color system was designed for dark mode and translates better there. Light mode requires additional polish work. Setting dark mode as default means new users see the best version of the product immediately.
**Impact:** Default user experience, settings page, onboarding.
**Source:** Direct product review June 2026.
 
---
 
### Fullscreen Mode During Assessments
**Date:** June 2026
**Decision:** Implemented the Fullscreen API so the app goes fullscreen when an assessment starts, hiding the browser chrome and all navigation.
**Alternatives considered:** Standard browser view, hiding navigation bar only.
**Reasoning:** During assessment the teacher needs complete focus on the student interaction. Any visible UI element that isn't part of the assessment — notification badges, browser tabs, navigation — is a potential distraction that could interrupt the flow or tempt the teacher to check something else. Fullscreen creates a focused, purpose-built environment. Also maximizes flashcard size on mobile which matters when showing cards to a student across a table.
**Impact:** Assessment flow UX, mobile experience.
**Source:** UX review June 2026 + classroom experience with device distractions.
 
---
 
### Accidental Exit Protection During Assessment
**Date:** June 2026
**Decision:** Added a confirmation dialog when a teacher attempts to exit mid-assessment: "Exit assessment? Your progress will be lost."
**Alternatives considered:** No confirmation (immediate exit), auto-save and resume.
**Reasoning:** A 5-year-old grabbing a tablet mid-assessment is a real scenario. Losing 15 responses because of an accidental tap on the X button would be genuinely frustrating and could result in inaccurate data if the teacher has to re-assess from memory. The confirmation dialog creates a one-tap buffer against accidental exits. Combined with incremental auto-save, this ensures data is protected.
**Impact:** Assessment flow, data integrity.
**Source:** Direct classroom experience with young students and devices.
 
---
 
### Co-Teacher vs Assistant Permission Levels
**Date:** [Add date]
**Decision:** Created two levels of shared classroom access: Co-Teacher (full access) and Assistant (assessment only, no reports or management).
**Alternatives considered:** Single shared access level, three or more levels, no sharing.
**Reasoning:** Real classroom staffing structures have meaningful distinctions. A co-teacher is a fully qualified educator who shares instructional responsibility and needs full data access. A paraprofessional, student teacher, or classroom aide assists with activities (including assessments) but shouldn't necessarily have access to all student reports or the ability to modify the class roster. The two-level system matches how schools actually structure classroom access.
**Impact:** Multi-user access architecture, Manage Teachers feature, DPA, Terms of Service.
**Source:** 20 years of classroom experience with different staffing models.
 
---
 
### Assessment Window Concept
**Date:** [Add date — initial product conception]
**Decision:** Organized assessments around "assessment windows" — defined periods during which a teacher aims to assess all students — rather than individual assessment dates.
**Alternatives considered:** Date-based only, no window concept.
**Reasoning:** Early childhood teachers don't think about assessment in terms of individual dates — they think in terms of windows. "I need to get everyone assessed before the October parent conferences" is how teachers actually plan. Organizing the product around windows rather than dates matches teacher mental models and enables meaningful features like "not yet assessed this window" filtering and window completion tracking.
**Impact:** Core product concept, dashboard, tracking chart, assessment picker.
**Source:** 13 years of Pre-K assessment experience + knowledge of how teachers plan assessment cycles.
 
---
 
## Business & Legal
 
---
 
### Six Market Launch
**Date:** June 2026
**Decision:** Launched abcAssess in six English-speaking markets: United States, Canada (English-speaking), Australia, New Zealand, United Kingdom, and Ireland.
**Alternatives considered:** U.S. only, U.S. and Canada only, full international launch.
**Reasoning:** All six markets share English as the primary language of instruction, have similar early childhood education frameworks, are served natively by Stripe for payment processing, have manageable privacy law frameworks (PIPEDA, Australian Privacy Principles, NZ Privacy Act 2020, UK GDPR all compatible with existing GDPR compliance), and represent underserved markets for early childhood assessment tools. Full international expansion would add language barriers, complex tax registration, and more diverse legal requirements — not appropriate at launch stage.
**Impact:** Market strategy, legal compliance, pricing, internationalization.
**Source:** Strategic analysis June 2026.
 
---
 
### Two Plans at Launch — Monthly and Annual Only
**Date:** June 2026
**Decision:** Launched with only two subscription plans: Monthly ($5/month) and Annual ($50/year). Academic Year Plan deferred to Fall 2027.
**Alternatives considered:** Three plans including Academic Year Plan at launch, monthly only, annual only.
**Reasoning:** The Academic Year Plan requires complex billing infrastructure — prorated pricing, delayed charge on renewal, Summer Transition Mode access controls, hemisphere-specific timing. Building this before having real user data risks over-engineering for hypothetical demand. Launching with two simple plans reduces technical complexity, keeps the pricing page clean, and allows real user behavior to inform whether and how the Academic Year Plan should be built.
**Impact:** Billing infrastructure, pricing page, Stripe configuration.
**Source:** Strategic decision June 2026 — deliberately deferring complexity until validated by real users.
 
---
 
### 14-Day Free Trial, No Card Upfront
**Date:** June 2026
**Decision:** New accounts get a 14-day free trial with full access. Credit card is not required until the end of the trial.
**Alternatives considered:** No trial (paid from day one), 7-day trial, 30-day trial, card required upfront.
**Reasoning:** Teachers need to actually use abcAssess with real students to understand its value — reading about it isn't enough. 14 days is long enough to complete a meaningful assessment cycle and generate reports, but short enough to create reasonable urgency. Requiring a card upfront creates friction that would deter trial signups, especially from cautious educators. Not requiring a card upfront is now standard practice for SaaS tools targeting individual professionals.
**Impact:** Onboarding, Stripe configuration, conversion strategy.
**Source:** Strategic decision June 2026 + knowledge of SaaS conversion best practices.
 
---
 
### 48-Hour Refund Window for Annual Renewals
**Date:** June 2026
**Decision:** Offered a 48-hour satisfaction guarantee — full refund available within 48 hours of a new annual signup or annual renewal charge.
**Alternatives considered:** No refunds, 7-day refund window, 30-day refund window, monthly plans only.
**Reasoning:** Teachers on annual plans who forget to cancel before renewal deserve a reasonable window to request a refund. 48 hours is long enough to notice a charge and act on it, short enough to not create significant financial risk. This is the policy the founder would personally want from a subscription service. Builds goodwill and trust, especially important for a new product asking teachers to commit annually.
**Impact:** Refund policy, Terms of Service, Stripe configuration.
**Source:** Personal values around fair treatment of customers.
 
---
 
### Beta Participants Receive One Free Year Post-Launch
**Date:** [Add date]
**Decision:** All active beta participants receive one full year of abcAssess free after the official launch.
**Alternatives considered:** Discount only, no special treatment, lifetime free access.
**Reasoning:** Beta participants are taking a risk by using an unfinished product with real students. They're providing real usage data, real feedback, and real validation that the product works. A full year free is a meaningful thank-you that also keeps them engaged through the first school year — turning them into experienced users who can refer colleagues and provide testimonials at exactly the moment you need word-of-mouth marketing.
**Impact:** Beta program, launch strategy, word-of-mouth growth.
**Source:** Founder values + strategic thinking about early adopter loyalty.
 
---
 
### Summer Transition Mode — "Data Follows the Child"
**Date:** June 2026
**Decision:** Designed the Academic Year Plan's summer period around the core workflow of transferring students between teachers at end of year, not just as a "limited access" period.
**Alternatives considered:** Full access year-round (Annual Plan), no access in summer, read-only only.
**Reasoning:** The most valuable thing a Pre-K teacher can do for their students' kindergarten year is transfer complete assessment histories to the incoming kindergarten teacher before the year starts. The kindergarten teacher can then review data all summer, plan instruction, and walk into September already knowing which letters each student knows. This isn't a limitation — it's a feature. Reframing summer access as "Transition Mode" rather than "limited mode" reflects the actual value it provides.
**Impact:** Academic Year Plan design, marketing copy, product positioning.
**Source:** Direct teaching experience + understanding of how student transitions work in early childhood education.
 
---
 
*Add new entries above this line.*
*Last updated: June 2026*
 
