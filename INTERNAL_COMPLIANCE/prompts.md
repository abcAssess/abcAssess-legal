# PROMPTS.md
## Significant AI Direction Log
 
*Maintained by: Danielle Andrist, Founder*
*Started: June 2026*
*Purpose: Documents significant moments in the AI-assisted development of abcAssess where Danielle Andrist provided specific creative direction, rejected AI outputs, introduced original ideas, or applied domain expertise to shape the product. Supports establishment of human authorship under applicable copyright and trade secret law per the abcAssess IP Assignment Agreement.*
 
---
 
### What belongs here:
- Moments you gave AI a specific instruction based on your teaching expertise
- Moments you rejected something AI produced and explained why
- Moments you corrected an error or caught something wrong
- Moments you introduced a completely new idea the AI hadn't suggested
- Moments your domain knowledge shaped a feature in a way a developer wouldn't have thought of
- Moments you pushed back on a suggestion that didn't fit real classroom use
### What doesn't belong here:
- Routine implementation requests ("make this button blue")
- Generic feature requests with no domain expertise behind them
- Moments where you accepted AI output without modification
### How to add an entry:
Add new entries at the top of the relevant section. Be specific about what you said, what the AI produced, and what you did with it.
 
```
### [DATE] — [SHORT TITLE]
**Tool:** Emergent AI / Claude / Other
**Context:** [What was being worked on]
**My direction:** [What specific instruction, correction, or creative input you provided]
**AI output:** [Brief description of what the AI produced]
**My response:** [Did you accept, reject, modify, or iterate? What did you change and why?]
**Domain knowledge applied:** [What teaching or product expertise informed your direction]
```
 
---
 
## From Claude — UX Review Sessions (June 2026)
 
*These entries document the comprehensive UX and product strategy review conducted with Claude in June 2026. Go through the conversation history and add the most significant moments.*
 
---
 
### June 2026 — Colorblind Accessibility Symbol System
**Tool:** Claude
**Context:** Reviewing the assessment tracking chart design
**My direction:** Identified that the tracking chart used color alone to communicate proficiency levels, which would be inaccessible to colorblind users. Specified a combined color AND symbol system: ✓ for proficient (sage green), ~ for developing (amber), ! for emerging (terracotta), — for not applicable (grey). Also specified a dot in the corner of cells to indicate manual edits.
**AI output:** Claude confirmed the approach met WCAG 2.1 Success Criterion 1.4.1 and suggested applying the same symbol system consistently to the assessment history expanded view for app-wide consistency.
**My response:** Accepted and extended — applied consistently across tracking chart and assessment history view throughout the app.
**Domain knowledge applied:** Awareness of colorblind accessibility needs in classroom settings; understanding that teachers, administrators, and specialists reviewing reports may have color vision deficiencies.
 
---
 
### June 2026 — Keyboard Shortcuts Pedagogical Insight
**Tool:** Claude
**Context:** Reviewing the live assessment flow screens
**My direction:** Explained that keyboard shortcuts were critical for classroom use specifically because teachers need to record responses without students seeing the outcome. Described using left/right arrow keys rapidly during real assessments with my Pre-K class in May 2026. Students thought they were "playing a game on my phone" and had no awareness they were being assessed or that they got answers wrong. A teacher visibly tapping a large red "Unknown" button repeatedly would signal failure to the child.
**AI output:** Claude identified this as a significant pedagogical insight that no developer would have arrived at independently and suggested it be captured in marketing copy as a key differentiator — "To your students it's a game on your phone. To you, it's data."
**My response:** Accepted — flagged for landing page copy, user guide, and marketing materials. Confirmed as one of the most important product insights from real classroom use.
**Domain knowledge applied:** Direct classroom experience assessing Pre-K students; understanding of child psychology around failure and discouragement in early childhood; knowledge of how young children respond to adult reactions during assessment.
 
---
 
### June 2026 — Phone as Primary Assessment Device
**Tool:** Claude
**Context:** Discussing mobile vs tablet priority for development
**My direction:** Corrected Claude's assumption that tablet was the primary assessment device. Explained that I conducted my entire class assessment in May 2026 on my phone — it was in my pocket on the playground, in the hallway, during snack time. Teachers don't carry tablets everywhere but they always have their phone. Opportunistic assessment during unstructured time is a core use case.
**AI output:** Claude revised its recommendation to prioritize mobile development and reframed the product positioning around phone-based assessment.
**My response:** Accepted — confirmed phone as primary device, tablet as secondary, desktop as tertiary.
**Domain knowledge applied:** Direct classroom experience; understanding of how teachers actually move through their day and when assessment opportunities arise.
 
---
 
### June 2026 — Manual Entry Select All Workflow
**Tool:** Claude
**Context:** Reviewing the manual entry checkbox list
**My direction:** Explained that the scrolling checkbox list was annoying based on real data entry experience. For a student who got 20/26, I would select all and then uncheck the 6 they missed — much faster than checking 20 individual boxes. For a student who got 7/26, I would check individually. Suggested replacing the list with a tile grid matching the assessment history expanded view.
**AI output:** Claude confirmed the tile grid approach and noted it would create visual consistency between manual entry and assessment history views — same layout, just checkboxes instead of display-only symbols.
**My response:** Accepted — added to Emergent task list.
**Domain knowledge applied:** Direct experience entering assessment data for 18 students; understanding of efficient data entry workflows in a classroom context.
 
---
 
### June 2026 — Student Data Minimization Validation
**Tool:** Claude
**Context:** Reviewing the Add Student dialog and privacy approach
**My direction:** Explained the deliberate decision to collect only first name (required), last initial (optional), birth month and year (optional, no day). Clarified that no day field was intentional — month and year is sufficient for age-grouping without being individually identifying. Teachers can also use student ID numbers or other identifiers instead of names entirely.
**AI output:** Claude confirmed this was a strong privacy-first design decision that would resonate with schools concerned about FERPA and reduce barriers to adoption.
**My response:** Accepted — confirmed approach is intentional and documented reasoning for privacy policy and DPA.
**Domain knowledge applied:** Awareness of FERPA/COPPA concerns; understanding of what data is actually needed for educational assessment vs what is collected out of habit.
 
---
 
### June 2026 — Font Selection Validation
**Tool:** Claude
**Context:** Reviewing the assessment flashcard screen
**My direction:** Explained that the font choice for flashcards was critical and had required significant research. Young children are taught specific letterforms — double-story 'a', typed 'g', and uppercase 'I' without serifs would invalidate letter recognition assessments for some students who know their letters but don't recognize the digital version. Confirmed the chosen font had single-story 'a', standard manuscript 'g', and uppercase 'I' with serifs.
**AI output:** Claude noted this was exactly the kind of domain expertise that makes the difference between an assessment tool built by an educator vs a developer, and suggested documenting it as a key product decision.
**My response:** Accepted — added to DECISIONS.md as a primary example of teaching expertise driving product design.
**Domain knowledge applied:** Knowledge of manuscript print standards in early childhood literacy instruction; direct teaching experience with letter recognition assessment.
 
---
 
### June 2026 — "What's Next" Screen Four Exit Paths
**Tool:** Claude
**Context:** Reviewing the assessment results and flow
**My direction:** [Add specific direction you gave about the What's Next screen options]
**AI output:** [Add what Claude suggested]
**My response:** [Add what you accepted/modified]
**Domain knowledge applied:** Understanding of different teacher assessment workflow patterns — some assess all subjects for one student, some assess one subject across the whole class.
 
---
 
### June 2026 — Co-Teacher vs Assistant Permission Levels
**Tool:** Claude
**Context:** Reviewing the Manage Teachers feature
**My direction:** Explained that two distinct permission levels reflect real classroom staffing structures. A co-teacher is a fully qualified educator who shares instructional responsibility and needs full data access. A paraprofessional or aide assists with activities but shouldn't have access to all reports or the ability to modify the class roster.
**AI output:** Claude confirmed the two-level system and suggested adding helper text to the Manage Teachers dialog explaining exactly what each role can and cannot do, so teachers understand what access they're granting before they invite someone.
**My response:** Accepted — added helper text to Emergent task list.
**Domain knowledge applied:** 20 years of classroom experience with different staffing models including co-teachers, paraprofessionals, student teachers, and classroom aides.
 
---
 
### June 2026 — Auto-Save Frustration Discovery
**Tool:** Claude
**Context:** Reviewing the student override settings screen
**My direction:** Discovered during live testing that the student override settings auto-saved without warning. Changed a student's settings and then couldn't remember what they were originally. Identified this as a real problem — teachers make mistakes and need to be able to discard changes.
**AI output:** Claude suggested explicit Save button + discard prompt pattern, consistent with how the class-wide settings already worked. Also suggested applying this pattern globally across the entire app wherever data can be changed.
**My response:** Accepted and expanded — established as a global design system rule: sticky save bar + discard prompt everywhere data can be modified.
**Domain knowledge applied:** Direct product testing; understanding of teacher workflows where interruptions (students, colleagues) can cause accidental changes.
 
---
 
### June 2026 — Delete Class Student Handling Step
**Tool:** Claude
**Context:** Reviewing the Delete Class dialog
**My direction:** Suggested adding a step before the type-to-confirm screen asking what to do with the students — transfer to another class or delete with the class. Reasoning: a teacher who wants to delete a class might not want to lose all the student data, and giving them an out before the irreversible action is more humane.
**AI output:** Claude confirmed and noted this was consistent with the Archive Class flow which already had this step, suggesting both flows should mirror each other for consistency.
**My response:** Accepted — added to Emergent task list, confirmed both flows should be consistent.
**Domain knowledge applied:** Understanding of how teachers manage class transitions and that student data often needs to persist beyond a single class configuration.
 
---
 
### June 2026 — Summer Transition Mode Reframing
**Tool:** Claude
**Context:** Discussing the Academic Year Plan summer access period
**My direction:** Explained the core real-world workflow: at end of year, Pre-K teacher transfers all students to the kindergarten teacher who receives complete assessment histories before the year starts. The kindergarten teacher reviews data all summer, plans instruction, builds the new roster as class lists arrive in August. This is the most important thing summer access enables — not just "read-only" but active preparation for the incoming year.
**AI output:** Claude reframed the feature from "limited summer access" to "Summer Transition Mode" with the positioning "data follows the child, not the classroom" and suggested this framing for marketing copy.
**My response:** Accepted — "Summer Transition Mode" adopted as the official name, "data follows the child" captured as core marketing language.
**Domain knowledge applied:** Direct understanding of how student transitions work between Pre-K and Kindergarten; knowledge of when teachers receive class lists and begin planning.
 
---
 
### June 2026 — Academic Year Plan Complexity Decision
**Tool:** Claude
**Context:** Deep dive into Academic Year Plan pricing and billing
**My direction:** After working through multiple edge cases (mid-year signups, Annual subscribers wanting to switch, hemisphere timing differences, prorated pricing), recognized the complexity was getting out of hand for a pre-revenue product. Made the decision to defer the Academic Year Plan to Fall 2027 and launch with Monthly and Annual only.
**AI output:** Claude confirmed this was the right strategic decision — "get real user data before building complex billing infrastructure for hypothetical demand."
**My response:** Accepted — deliberately deferred. Documented all the Academic Year Plan thinking in the pricing document for future reference.
**Domain knowledge applied:** Founder judgment; ADHD-aware decision making about scope and complexity.
 
---
 
### June 2026 — International Market Selection
**Tool:** Claude
**Context:** Discussing geographic expansion beyond US
**My direction:** Pushed to include Canada, Australia, New Zealand, UK, and Ireland at launch. Reasoning: all English-speaking, similar educational frameworks, underserved in early childhood assessment tools specifically, manageable legal frameworks.
**AI output:** Claude confirmed all six markets were achievable with relatively minor additions to legal documents and Stripe Tax configuration. Identified that the existing GDPR coverage already handled UK and Ireland, and that PIPEDA (Canada), Australian Privacy Principles, and NZ Privacy Act 2020 were compatible with the existing privacy architecture.
**My response:** Accepted — six market launch confirmed. Legal documents updated for all six jurisdictions.
**Domain knowledge applied:** Understanding of English-speaking early childhood education markets; awareness that these markets share similar assessment frameworks and teacher needs.
 
---
 
## From Emergent AI — Development Sessions
 
*Go through your Emergent conversation history and add entries here. Focus on moments where you gave specific direction, rejected something, or applied teaching expertise.*
 
---
 
### [DATE] — [TITLE]
**Tool:** Emergent AI
**Context:** [What were you building]
**My direction:** [What did you tell Emergent specifically]
**AI output:** [What did Emergent produce]
**My response:** [What did you accept, reject, or modify and why]
**Domain knowledge applied:** [What expertise informed your direction]
 
---
 
### [DATE] — [TITLE]
**Tool:** Emergent AI
**Context:**
**My direction:**
**AI output:**
**My response:**
**Domain knowledge applied:**
 
---
 
### [DATE] — [TITLE]
**Tool:** Emergent AI
**Context:**
**My direction:**
**AI output:**
**My response:**
**Domain knowledge applied:**
 
---
 
### [DATE] — [TITLE]
**Tool:** Emergent AI
**Context:**
**My direction:**
**AI output:**
**My response:**
**Domain knowledge applied:**
 
---
 
### [DATE] — [TITLE]
**Tool:** Emergent AI
**Context:**
**My direction:**
**AI output:**
**My response:**
**Domain knowledge applied:**
 
---
 
### [DATE] — [TITLE]
**Tool:** Emergent AI
**Context:**
**My direction:**
**AI output:**
**My response:**
**Domain knowledge applied:**
 
---
 
### [DATE] — [TITLE]
**Tool:** Emergent AI
**Context:**
**My direction:**
**AI output:**
**My response:**
**Domain knowledge applied:**
 
---
 
### [DATE] — [TITLE]
**Tool:** Emergent AI
**Context:**
**My direction:**
**AI output:**
**My response:**
**Domain knowledge applied:**
 
---
 
### [DATE] — [TITLE]
**Tool:** Emergent AI
**Context:**
**My direction:**
**AI output:**
**My response:**
**Domain knowledge applied:**
 
---
 
### [DATE] — [TITLE]
**Tool:** Emergent AI
**Context:**
**My direction:**
**AI output:**
**My response:**
**Domain knowledge applied:**
 
---
 
*Add new entries above this line as you review your Emergent conversation history.*
*Last updated: June 2026*
 
