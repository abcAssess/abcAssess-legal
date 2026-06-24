# abcAssess Ideas & Future Features
*A running list of ideas that aren't ready for the Emergent task list yet but are worth capturing.*
*Last updated: June 10, 2026*
 
---
 
## How to Use This Document
- Add ideas here as they come up — no matter how half-formed
- When an idea is ready to build, move it to the Emergent Master Task List
- When an idea becomes a firm decision, add it to DECISIONS.md
- Ideas don't need to be fully thought through to live here — that's the point
---
 
## In-App Feature Discovery
 
### Periodic Tips & Feature Highlights
After login, show a periodic tip — either as a dismissable banner at the top of the screen or a small dialog — that highlights features teachers might not have discovered yet. Tips should be:
 
- **Strategically ordered** — introduce features in the order a teacher would naturally need them, not randomly
- **Actionable** — each tip includes two options: "Take me there" (deep links directly to the feature) and "Learn more" (opens the relevant section of the User Guide)
- **Dismissable** — teacher can close it immediately with no friction
- **Not annoying** — show once per session maximum, or every few logins, not every single time
- **Contextually relevant** — don't show a tip about sharing custom assessments until the teacher has actually created a custom assessment
**Possible tip topics (in suggested order):**
1. Keyboard shortcuts for invisible scoring
2. Setting proficiency thresholds for your class
3. Randomizing assessment item order
4. Per-student assessment overrides for differentiation
5. Manual entry for paper-based assessments
6. Creating a custom assessment
7. Sharing a custom assessment with a colleague
8. Timed assessment mode for fluency benchmarks
9. Downloading a class backup
10. Generating a progress report to show growth over time
11. The parent-friendly Learning Journey report
12. Inviting a co-teacher or assistant
13. Assessment windows and tracking completion
14. Transferring students at end of year
**Example tip:**
*"Did you know you can customize proficiency thresholds for your class? Set what percentage counts as Proficient and Developing to match your program's standards."*
[Take me there] [Learn more in User Guide]
 
**Technical consideration:**
Track which tips have been shown and dismissed per account so teachers don't see the same tip repeatedly. Once all tips have been shown, the system could cycle back or simply stop showing them.
 
Could also be used strategically for feature announcements when new features launch — "New in abcAssess: Timed Assessment Mode is here."
 
### Customizable Dashboard Widgets
Allow teachers to customize their dashboard by adding, removing, and rearranging widgets. Possible widgets could include:
- Class assessment completion progress (current window)
- Students not yet assessed this window
- Recent assessment activity
- Quick-start assessment button
- Upcoming assessment window deadlines
- Class proficiency summary
- Students below threshold (needs attention)
- Recent report downloads
Teachers have different workflows — some want to see everything at a glance, others want a clean minimal view. Customizable widgets let the dashboard work for everyone.
 
---
 
## Assessment Packs
 
### Heggerty Assessment Pack
Create a structured assessment pack specifically for Heggerty Phonemic Awareness curriculum. The pack would mirror Heggerty's structure — multiple skill categories, each with rotating item sets assessed in groups of 5. Teachers could:
- Select which Heggerty unit/week they are assessing
- See growth over time across Heggerty skill areas
- Track automaticity alongside accuracy for fluency goals
This is a high-priority future feature given Heggerty's widespread use in early childhood programs. Danielle currently uses a custom assessment workaround — an official pack would be cleaner and more accurate.
 
### Assessment Pack Framework
A general framework for creating structured assessment packs tied to specific curricula or programs. Beyond Heggerty, potential packs could include:
- DIBELS / DIBELS Next
- AIMSweb
- Other commonly used early childhood literacy screeners
- State-specific required assessments
Assessment packs would be distinct from custom assessments — they come pre-structured with curriculum-aligned item sets, scoring guidelines, and progress tracking designed around the specific tool's framework.
 
---
 
## TS Gold / GOLDfinch Alignment
 
### TS Gold Objective Alignment
Map abcAssess assessment results to Teaching Strategies GOLD objectives so teachers can use abcAssess data to inform their TS Gold documentation. This would not reproduce TS Gold content verbatim but would provide a crosswalk — "students scoring Proficient on Uppercase Letters typically align with TS Gold Objective 16a at level X."
 
This is a significant differentiator if implemented carefully and legally. Many teachers use both tools and having abcAssess data inform TS Gold entries would save substantial time.
 
*Legal note: Do not reproduce TS Gold objective text verbatim. Frame as alignment guidance, not replacement. Teaching Strategies Gold® is a registered trademark of Teaching Strategies, LLC. abcAssess is not affiliated with Teaching Strategies.*
 
---
 
## Mirror Mode
 
### Assessment Mirror Mode
A split-screen or mirrored display mode where the flashcard is shown on the student-facing side of a device (tablet propped up or second screen) while the teacher controls and scores from their side. Would allow:
- Student sees the flashcard clearly without seeing teacher's response buttons
- Teacher scores invisibly on their side
- More natural assessment experience — student faces the card, teacher faces the scoring interface
Particularly useful for tablet-based assessments in a structured setting. Less critical for phone-based opportunistic assessment.
 
---
 
## Account & Administrative Features
 
### Admin Level Account
A school or center director level account that sits above individual teacher accounts. Admin would be able to:
- View all classes across the program
- See program-wide assessment data and trends
- Generate program-level reports for licensing, accreditation, or grant reporting
- Manage teacher accounts (add, remove, reset passwords)
- Set program-wide assessment requirements and windows
- Not have access to individual student data without teacher permission
This opens a school/district pricing tier and makes abcAssess viable for program-wide adoption rather than individual teacher use only.
 
**Beta center discount:**
Centers that participated in the beta period will receive a permanent 20% discount on their center license when this option becomes available — regardless of when center licensing launches. This applies to centers where at least one teacher actively participated in the beta and completed the end-of-beta survey.
 
*Note: Admin accounts would require significant additional legal documentation — data access agreements, admin-specific Terms of Service, and potentially additional FERPA authorization language.*
 
---
 
## Reports & Data
 
### IEP Progress Report Type
A specialized report format designed for special education progress monitoring. Details to be determined following summer consultation with ECSE teacher colleague. Considerations include:
- Goal-based reporting format
- Baseline vs current performance comparison
- Rate of progress documentation
- Automaticity data from timed assessments
- Formatting consistent with IEP documentation requirements
*Status: Deferred until summer 2026 ECSE teacher consultation.*
 
### Data Export Formats
Beyond PDF reports, allow teachers to export data in formats useful for other systems:
- CSV export of assessment data for importing into other tools
- Excel-formatted class reports
- Potentially a TS Gold-compatible export format (see TS Gold Alignment above)
---
 
## Accessibility & Language
 
### Additional Language Support
Translate the app interface and assessment prompts into additional languages. Priority languages based on target markets:
- Spanish (large dual language learner population in US)
- French (Canada — Quebec and French-speaking provinces)
- Welsh (UK)
- Irish/Gaelic (Ireland)
*Note: Assessment content translation would need to be reviewed by early childhood educators fluent in each language to ensure assessment validity.*
 
### Text-to-Speech for Assessment Items
Automatic text-to-speech for assessment flashcard items so teachers don't need to record their own audio prompts for built-in assessments. Would use high-quality TTS rather than recorded audio for consistency.
 
---
 
## Integrations
 
### Google Classroom Integration
Allow teachers to import their class roster from Google Classroom rather than manually entering students. Would pull student first names only — consistent with data minimization principles.
 
### Seesaw Integration
Similar roster import and potentially data sharing with Seesaw portfolios.
 
### Calendar Integration
Sync assessment windows with school calendar apps (Google Calendar, Apple Calendar) so deadline reminders appear in teachers' existing workflow.
 
---
 
## Gamification & Engagement
 
### Teacher Streaks and Milestones
Small recognition moments for teachers who maintain consistent assessment habits:
- Assessment window completion streaks
- "You've assessed 500 students" milestones
- End of year summary ("You completed X assessments this year")
Celebrates teacher effort in a profession that rarely gets celebrated.
 
---
 
## Platform
 
### Web Browser Extension
A lightweight browser extension that lets teachers log a quick assessment from any device without opening the full app. Useful for brief opportunistic assessments.
 
### Apple Watch / Wearable
Extremely lightweight assessment logging from a wearable — tap Known/Unknown on a watch face during circle time or transitions. Very speculative but fits the "phone in your pocket" philosophy of invisible, opportunistic assessment.
 
---
 
*Add new ideas above the relevant section or create a new section.*
*Last updated: June 10, 2026*
 
