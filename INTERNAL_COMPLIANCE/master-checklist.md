# abcAssess Pre-Launch Master Checklist
*Last updated: July 2026*
*Target launch: January 2027*
 
---
 
## 🏢 Business & Legal Structure
 
- [ ] Register abcAssess LLC with North Dakota Secretary of State (~$135, businessreg.nd.gov) — **do this soon, student data is live now**
- [ ] Open business bank account once LLC is registered (Relay or Mercury recommended)
- [ ] Have attorney review all five legal documents before January 2027 launch — focus on FERPA, COPPA, GDPR, PIPEDA, Australian Privacy Principles, NZ Privacy Act
- [ ] Appoint EU GDPR Representative (required for non-EU companies processing EU data) — ~$200-500/year
- [ ] Appoint UK GDPR Representative (separate from EU) — similar cost
- [ ] Sign IP Assignment Agreement on same day LLC is registered — not before
- [ ] Ensure Operating Agreement documenting 100% membership units is in place before signing IP Assignment Agreement
- [ ] Update all legal documents to reflect "abcAssess LLC" once registered
- [ ] Update Effective Date on IP Assignment Agreement to match LLC formation date
---
 
## 📋 Legal Documents
 
All five documents updated and ready for attorney review:
 
- [ ] Privacy Policy v1.2 — attorney review
- [ ] Terms of Service v2.3 — attorney review
- [ ] Data Processing Agreement v2.1 — attorney review
- [ ] Technical & Privacy FAQ v2.1 — publish to support center
- [ ] Accessibility Statement v2.2 — publish to support center
- [ ] IP Assignment Agreement DRAFT — sign on LLC formation day
- [ ] Remove "Hosted on GitHub Pages — Theme by orderedlist" from support center footer
- [ ] Share brother-in-law attorney copy for first pass review
- [ ] Cookie Policy / consent banner — checked June 2026: PostHog currently only fires inside the logged-in app, not on the public landing page, so a standalone Cookie Policy is likely NOT needed right now. Re-confirm once PostHog landing page configuration is finished (was left incomplete) — make sure tracking doesn't end up firing pre-login. If it does end up on the landing page, draft a Cookie Policy/banner at that point.
- [ ] Internal Incident Response / Breach Notification runbook (NOT public-facing) — DPA promises breach notification to customers; write the actual internal step-by-step plan for what happens the moment a breach is suspected (who's notified, what's assessed, notification timeline, who handles comms). Attorney will likely ask for this during review.
---
 
## 🌐 Support Center — What Gets Published Where
 
**Main support center nav/footer (Privacy Policy, ToS, etc. — fully public, linked everywhere):**
- [ ] Privacy Policy
- [ ] Terms of Service
- [ ] Data Processing Agreement
- [ ] Technical & Privacy FAQ
- [ ] Accessibility Statement
- [ ] User Guide (move from draft into GitHub Pages — one long page, TOC + anchor links + back-to-top, same pattern as legal docs; do NOT split into per-section pages)
- [ ] 5-Minute Starter Guide
- [ ] Cookie Policy (if needed — see Legal Documents section above for the check; if a policy is required, it goes here, fully public, since it concerns the marketing site visitors see before ever signing up)
**Published, but NOT in main nav — quiet/direct-link only:**
- [ ] School Authorization — publish to a stable URL (e.g. `abcassess.app/support/school-authorization`) but do not add to footer/main nav. This is for school/center administrators during procurement conversations, sent directly by Danielle when relevant. Add one quiet reference line at the bottom of the Technical & Privacy FAQ: "Are you a school or center considering abcAssess? Contact us for a School Authorization document."
- [ ] Sub-Processor Registry — publish to a stable URL. Referenced by the DPA ("see Sub-Processor Registry") so it needs to actually exist publicly, but doesn't need main nav placement — link to it directly from within the DPA text instead.
- [ ] Beta Participant Terms — publish to `abcassess-legal/beta-participant-terms` (already planned). Remove from public support center after beta ends.
**Never public — internal only, confirmed correct as-is:**
- IP Assignment Agreement, Operating Agreement, Pre-Launch Master Checklist, Emergent task lists, DECISIONS.md, PROMPTS.md, TIMELINE.md, Image Asset Tracker, Insurance Quote Description, internal Pricing/Subscription Model doc, Professional Services Guide, About This Project reference doc, beta survey raw responses (once collected)
- [ ] Move internal compliance documents OUT of the `abcassess-legal` repo (currently sitting in an "internal compliance" folder there) into a brand new, separate **private** repo (e.g. `abcassess-internal` or `abcassess-compliance`). Reasoning: `abcassess-legal` actively powers the public GitHub Pages site — keeping private docs in the same repo as actively-published content creates real risk of an accidental publish (config change, exclude rule slip, etc.). A fully separate repo makes that structurally impossible instead of just policy-dependent.
  - [ ] Create new repo, confirm visibility is set to **Private** in repo Settings (don't just assume — verify)
  - [ ] Move (not copy) all internal compliance files over
  - [ ] Delete the internal-compliance folder from `abcassess-legal` once confirmed moved
  - [ ] No Jekyll/theme/styling needed for the internal repo — skip `_config.yml`, Cayman theme, custom CSS entirely. Plain `.md` files are fine; GitHub renders markdown reasonably by default for single-reader internal use.
  - [ ] No GitHub Pages enabled on the internal repo at all — nothing to publish, so don't even turn the feature on
  - [ ] Optional: add a single root `README.md` listing what's in the repo and why, for future orientation
---
 
## 🔒 Insurance
 
- [ ] Research and get quotes from Embroker, Hiscox, Coalition, Simply Business
- [ ] Purchase General Liability insurance (~$300-600/year)
- [ ] Purchase Errors & Omissions / Professional Liability (~$500-1,500/year)
- [ ] Purchase Cyber Liability insurance (~$500-2,000/year) — **highest priority given student data**
- [ ] Inform insurance provider of international user base (US, Canada, Australia, New Zealand, UK, Ireland)
- [ ] Note: when signing UK/Australia school contracts, confirm local insurance requirements
---
 
## 💳 Payment Processing
 
- [ ] Set up Stripe account
- [ ] Configure Monthly Plan ($5/month) with 14-day free trial
- [ ] Configure Annual Plan ($50/year) with 14-day free trial
- [ ] Configure 14-day free trial — credit card required at end to continue, not upfront
- [ ] Enable Stripe Tax for automatic VAT (UK/Ireland) and GST (Australia/New Zealand) collection
- [ ] Configure 48-hour refund window for new signups and annual renewals
- [ ] Configure auto-renewal with reminder emails
- [ ] Test complete payment flow end to end before launch
- [ ] Note: VAT registration required in UK when revenue exceeds £85,000; Ireland €37,500; AU AUD $75,000; NZ NZD $60,000
---
 
## 🛠️ App — Emergent Task List
 
### Student List / Class Page
- [ ] Edit Class "Save" button → change to sage
- [ ] Transfer Students "Send Request" button → confirm renders honey/yellow when active
- [ ] Add Student preview text → make dynamic or remove until input exists
- [ ] Delete dialog → standardize casing ("Delete Class" vs "Delete class")
- [ ] Delete Class flow → add student handling step before type-to-confirm
- [ ] Transfer icon on Manage Teachers → rename to "Change Role," replace with user-cog icon
- [ ] Manage Teachers → add helper text explaining role permissions
- [ ] Transfer Student (individual) → add two options: move within account or send to another teacher
### Manage Assessments / Student Overrides
- [ ] Individual student override screen → add explicit Save button, no auto-save
- [ ] "Reset to Class Defaults" → stages the change, requires Save to take effect
- [ ] Unsaved changes prompt → "You have unsaved changes. Save or discard?"
### Assessment Picker
- [ ] "Start Assessment" picker → add last assessed date under each assessment name
- [ ] "Same Assessment, Next Student" picker → add last assessed date + "Not yet assessed this window" filter
- [ ] "Another Assessment, Same Student" picker → same last assessed date + filter
- [ ] Empty state when all students assessed for a type → confetti + completion message
- [ ] Empty state when student completes all assessments → confetti + completion message
### Assessment Flow
- [ ] Hide navigation bar during active assessment — X exit button only
- [ ] Implement Fullscreen API triggered on assessment start
- [ ] Accidental exit protection → "Exit assessment? Your progress will be lost."
- [ ] Auto-save responses incrementally during assessment
- [ ] Manual entry → replace scrolling checkbox list with tile grid
- [ ] Assessment history expanded view → replace ✓/✗ with app-wide symbol system
- [ ] Items to Practice on results screen → display alphabetically
- [ ] Backup download confirmation dialog → add FERPA responsibility language + checkbox acknowledgment
- [ ] Backup download → log to database: teacher account ID, timestamp, IP address, acknowledgment version
### Student Profile
- [ ] Delete Student flow → add data handling step before type-to-confirm
- [ ] Progress Over Time chart → replace color band shading with labeled threshold lines
- [ ] Progress Over Time chart → reduce data point label crowding
- [ ] Assessment color dots → document and lock in fixed color per assessment type
### Assessment Settings
- [ ] Save button → move to sticky bar at bottom of panel
- [ ] Sticky save bar → sage Save button + amber "Unsaved changes" indicator
- [ ] Threshold editor → "Save Thresholds" button change to sage
- [ ] Threshold validation → prevent Developing threshold higher than Proficient
### Global / Design System
- [ ] Sticky save bar + discard prompt → apply consistently everywhere data can be changed
- [ ] All dialogs/panels → maximum height 90% of viewport, internal scrolling only
- [ ] Navigation badges → suppress during active assessment session
- [ ] Confetti → add to: all students assessed this window, student completes all assessments
- [ ] "Custom" label in Student Overrides → consider changing from terracotta to purple
### Settings Page
- [ ] Log Out button → change from terracotta to neutral outlined button
- [ ] Confirm Password "Continue" button → change from terracotta to steel blue or honey/yellow
- [ ] Security Questions "Save Questions" button → change to sage
- [ ] Reconcile Assistant permissions — can they view reports or not?
- [ ] Delete Account → move into Password & Security modal
- [ ] Password & Security modal → add Auto Sign-Out and Delete Account
- [ ] Pending Sync tile → show count, last sync attempt, manual Sync Now button
- [ ] Pending Sync / offline storage → confirm IndexedDB or equivalent (not memory)
- [ ] Settings layout restructure → three columns: Profile/Security, Assessment Settings, Connections
- [ ] Teacher Connections tile → expand with role labels, change role, remove options
- [ ] Pending Invitations tile → new, with Incoming and Outgoing sections
### Reports Page
- [ ] Restructure into three columns: Assessment Window + summary, Assessment Explorer, Downloads & Exports
- [ ] Move backup download from Settings to Reports page
- [ ] Center column → assessment picker, class average, Growth Over Time chart, item breakdown
- [ ] Progress bars → add color coding based on configured proficiency thresholds
- [ ] Class ranking table → add score color coding based on thresholds
- [ ] Item breakdown table → add color coding, consider ascending sort order
- [ ] Report options → replace hardcoded threshold percentages with dynamic values
- [ ] Confirm color band shading in PDF reflects teacher's configured thresholds
- [ ] Investigate why color band shading works in PDF but not app chart
- [ ] Report dialog → split into three tabs: Options, Assessments, Preview
- [ ] Download button → visible and accessible from all three tabs
- [ ] Progress report → add class average overlay option
- [ ] Progress report footer → fix copyright year to dynamic current year
- [ ] Parent report item grid → sort alphabetically
- [ ] Parent report → change "Numbers" to "Numerals" throughout
- [ ] Confirm "Confidential — For Educational Use Only" footer on all report versions
### Quality Assurance
- [ ] Audit all modals that appear in multiple locations — confirm identical design, copy, behavior
- [ ] Transfer Student (individual) → add two transfer options matching class-level transfer flow
### Internationalization
- [ ] Audit app for US-only hardcoding — date formats, phone fields, address fields
- [ ] Display dates in user's local format — DD/MM/YYYY for AU, NZ, UK, Ireland; MM/DD/YYYY for US, Canada
- [ ] Confirm no other locale-specific assumptions hardcoded
---
 
## 📊 Analytics & Monitoring
 
- [ ] PostHog setup complete — Product Analytics and Web Analytics enabled
- [ ] Verify PostHog Live Events showing correctly
- [ ] Verify NO student PII appearing in any PostHog events
- [ ] Verify IP anonymization enabled in PostHog
- [ ] Verify person profiles disabled in PostHog
- [ ] Session replay — configure masking before enabling, verify student data fields masked
- [ ] Sentry configured for frontend and backend with student data masking
- [ ] Uptime Robot configured for app, root domain, API health, Railway direct URL
- [ ] Health check endpoint updated to accept both GET and HEAD requests
- [ ] Add PostHog and Sentry to sub-processors in Privacy Policy and DPA ✓ (done)
---
 
## 🔐 Security & Infrastructure
 
- [ ] Run full offline test: turn off connectivity → complete assessments → close app → restart device → restore connectivity → confirm all synced
- [ ] Confirm offline assessments saved to device storage (IndexedDB), NOT memory
- [ ] Pre-launch security and code quality review
- [ ] Staging environment setup
- [ ] Automated database backup verification
- [ ] Plan MongoDB Atlas EU region cluster for UK/Ireland users as those markets grow
---
 
## 📱 Mobile & Tablet
 
- [ ] Complete mobile view review and fixes
- [ ] Complete tablet view review and fixes
- [ ] Test fullscreen API on iOS and Android
- [ ] Test assessment flow on phone — tap targets, speed, responsiveness
- [ ] Stress test: tap through 26 letters as fast as possible, confirm all responses register
- [ ] Test haptics for assessment save confirmation (mobile only)
---
 
## 🌐 Internationalization
 
- [ ] Privacy Policy updated for all six markets ✓ (done)
- [ ] Terms of Service updated for all six markets ✓ (done)
- [ ] DPA updated for all six markets ✓ (done)
- [ ] FAQ updated for all six markets ✓ (done)
- [ ] Accessibility Statement updated for all six markets ✓ (done)
- [ ] Confirm with attorney whether data residency requirements apply for UK/Ireland at current scale
- [ ] EU Representative appointed before actively marketing to EU/Ireland schools
- [ ] UK Representative appointed before actively marketing to UK schools
---
 
## 📚 Documentation & Content
 
- [ ] User Guide — write assessment flow section first (most stable, most needed)
- [ ] User Guide — complete remaining sections after UI revamp is finalized
- [ ] Development log repository created on GitHub (private)
- [ ] DECISIONS.md — populate with key product decisions including backdated entries
- [ ] PROMPTS.md — populate from Emergent conversation history
- [ ] TIMELINE.md — populate with development milestones
- [ ] README.md — add to private dev log repo
- [ ] Image asset tracker — set up and populate as beginning sounds images are sourced
---
 
## 🖼️ Content & Assets
 
- [ ] Source beginning sounds images from Pixabay or Flaticon (verify Pixabay License on each)
- [ ] Log every image in Image Asset Tracker with source URL and license confirmation
- [ ] Do NOT use Google Images, Pinterest, or Canva stock elements for assessment images
- [ ] Consider commissioning original illustration set for consistent branded look (medium term)
- [ ] Remove "Hosted on GitHub Pages — Theme by orderedlist" from support center footer
---
 
## 👩‍🏫 Beta Program
 
- [ ] Define "active" threshold for free year eligibility (minimum usage requirement)
- [ ] Send written confirmation of free year offer to all current beta participants
- [ ] Grow beta teacher base — target outreach to interested centers before September school year start
- [ ] Prepare back-to-school demo for center staff meetings (August)
- [ ] Set November 1 beta teacher count target
- [ ] Beta closes December 2026 — incorporate feedback before January launch
- [ ] Consider Founding Member rate ($35/year for life) for beta teachers who continue after free year
---
 
## 🚀 Launch Preparation
 
- [ ] Finalize landing page copy and design
- [ ] Set up subscription management in app (plan selection, billing, trial, upgrades)
- [ ] Test complete new user flow: signup → trial → assessment → report → billing
- [ ] Set up support email routing (support@, legal@, beta@, feedback@abcassess.app)
- [ ] Prepare launch announcement for beta participants
- [ ] Prepare social media / outreach strategy for January 2027 launch
- [ ] Identify EdTech communities to announce in (Facebook groups, Teachers Pay Teachers, etc.)
---
 
## 🔮 Future (Not Pre-Launch)
 
- [ ] Academic Year Plan — Fall 2027
- [ ] Southern Hemisphere campaign timing — October/November 2027
- [ ] MongoDB Atlas EU region cluster — as UK/Ireland user base grows
- [ ] 2FA / two-factor authentication option
- [ ] School/district admin accounts
- [ ] Custom assessment sharing marketplace
- [ ] Prorated billing for Academic Year Plan
- [ ] Summer Transition Mode
- [ ] Hemisphere-specific email campaigns
---
 
*This checklist should be reviewed weekly as launch approaches.*
*Items marked ✓ are complete. All others are outstanding.*
