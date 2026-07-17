# abcAssess Pricing & Subscription Model
*Working document — not final. Last updated July 2026.*
 
---
 
## Launch Plans (January 2027)
 
*Keeping it simple for launch. Academic Year Plan planned for Fall 2027 after gathering real user feedback.*
 
### Monthly Plan
- **Price:** $5/month
- **Access:** Full access to all features
- **Billing:** Month-to-month, cancel anytime
- **Best for:** Teachers who want to try before committing, or who only need the tool short-term
- **Natural fit for:** New teachers exploring the tool, part-time or substitute educators, teachers who only need it for a specific assessment window
### Annual Plan
- **Price:** $50/year (saves $10 vs monthly)
- **Access:** Full access to all features, all 12 months
- **Billing:** Renews annually on signup anniversary
- **Best for:** Year-round educators who want simplicity and full access without thinking about dates
- **Natural fit for:** Year-round childcare centers and daycares, Head Start programs, private preschools with year-round enrollment, teachers who run summer school, teachers who want maximum simplicity
---
 
## Launch Pricing Comparison (January 2027)
 
| Plan | Price | Access | Best For |
|---|---|---|---|
| Monthly | $5/mo ($60/yr) | Full, all 12 months | Flexibility / trying it out |
| Annual | $50/yr | Full, all 12 months | Year-round centers, simplicity |
 
---
 
## Who Each Launch Plan Is For
 
### Monthly — $5/month
The try-before-you-commit plan. No long-term obligation.
- New teachers exploring the tool
- Part-time or substitute educators
- Teachers who only need it for a specific assessment window
- Anyone who wants to test it before choosing an annual plan
### Annual — $50/year
The simplicity plan. Full access, no seasonal restrictions, no thinking about dates.
- **Year-round childcare centers and daycares**
- **Head Start programs** (often year-round)
- **Private preschools with year-round enrollment**
- Teachers who run summer school or year-round assessment programs
- Teachers who just want maximum simplicity
- Most traditional school-year teachers who don't want to think about summer access
---
 
## Refund Policy
 
- Monthly plans: cancel anytime, no refund for current month
- Annual plans: non-refundable after charge date, access retained through end of paid period
- Academic Year Plan renewals confirmed but not yet charged: can be cancelled before charge date with no penalty
- Clearly stated in Terms of Service and at point of purchase
---
 
## Beta & Founding Member Pricing
 
### Beta Participants
- Free during beta period
- One full year free after official launch
- Must have been an active beta participant (definition TBD — minimum usage threshold to be determined)
- Communicated in writing to all beta participants
### Founding Member Rate (proposed)
- Teachers who complete their free beta year and continue subscribing
- Suggested rate: 20% off the current rate for life as a "Founding Member"
- Rewards loyalty, prevents churn at the end of the free year
- Creates a tier of highly engaged long-term users who become word-of-mouth advocates
---
 
## School & District Contracts
 
*To be developed based on market feedback. Initial thoughts:*
 
### Per-Teacher Licensing (proposed)
| Teachers | Price Per Teacher/Year |
|---|---|
| 1–9 | $40 (Academic Year rate) |
| 10–24 | $35 |
| 25–49 | $30 |
| 50+ | Negotiated |
 
### Site License (proposed)
- Flat fee for unlimited teachers at one school
- Estimated range: $300–$800/year depending on school size
- Includes all teacher accounts, admin reporting features TBD
### District License (proposed)
- Covers all schools in a district
- Negotiated individually based on number of schools and teachers
- Estimated starting range: $2,000–$5,000/year for small districts
### Notes on School/District Contracts
- Districts will likely require proof of insurance and minimum coverage amounts
- A Data Processing Agreement (DPA) will be required for most district contracts
- Pricing TBD based on real conversations with interested schools/centers
- Lead with "contact us for school pricing" until model is validated
---
 
## Future Plans (Fall 2027 — Planned)
 
*To be built after gathering real user feedback from January 2027 launch. Spring 2027 — announce and collect intent. Fall 2027 — launch.*
 
### Academic Year Plan Overview
- **Planned Price:** $40/year flat for 8–10 month active periods, prorated at $5/month for shorter periods
- **Active period:** 6–10 months, teacher-defined start and end dates
- **Maximum active period:** 10 months — enforced at date picker in UI
- **Minimum Summer Transition Mode:** 2 months required — prevents gaming into a de facto Annual Plan
- **Summer Transition Mode:** Included free with every Academic Year Plan, no renewal required to access
- **Best for:** Traditional school-year educators whose assessment work follows the academic calendar
- **Natural fit for:** Public school Pre-K and kindergarten teachers, teachers whose year runs September–May or August–May
- *"This is the plan I would choose as a Pre-K teacher."* — Danielle Andrist, founder
### Active Period Rules
- Teacher selects start date and end date at signup
- Date picker enforces maximum 10-month active period
- UI note: "Academic Year Plans support up to 10 active months. Need year-round access? Our Annual Plan may be a better fit."
- Any active period of 8–10 months = $40 flat
- Active periods under 8 months = prorated at $5/month
### Prorated First Year Pricing
Teacher picks their start month, active period runs through their chosen end date (maximum 10 months), pays based on length of active period. Renews at flat $40 from year two onward regardless of original prorated amount.
 
| Active Period Length | First Year Price | Summer Transition Included |
|---|---|---|
| 10 months | $40 (flat) | ✓ |
| 9 months | $40 (flat) | ✓ |
| 8 months | $40 (flat) | ✓ |
| 7 months | $35 | ✓ |
| 6 months | $30 | ✓ |
| Under 6 months | Monthly only recommended | — |
 
### Renewal Billing Model
- Teacher confirms renewal anytime during Summer Transition Mode — no charge until chosen start date
- Charge processes automatically on their chosen start date (e.g. September 1)
- If teacher cancels before charge date — no charge, no refund needed, access ends at start date
- If teacher does not confirm renewal by start date — remains in Summer Transition Mode read-only until they subscribe again
- No automatic charge without explicit renewal confirmation
- Summer Transition Mode is included free with the previous year's plan — no renewal required to access it
### Switching from Annual to Academic Year Plan (mid-year)
For existing Annual subscribers who want to switch:
- Teacher registers intent in spring (e.g. May), selects their Academic Year dates
- App calculates remaining Annual Plan credit as of their chosen Academic Year start date
- App confirms: "Starting September 1 your Academic Year Plan begins. Your remaining Annual Plan credit of $X will be applied — you'll be charged $40 minus $X on September 1."
- No charge until September 1 — teacher can change their mind before then
- From year two onward: flat $40 renewal every September (or chosen start date)
- Renewal date snaps to Academic Year start date, not upgrade date — teachers think in school years, not calendar months
### Upgrading from Academic Year to Annual Plan (mid-year)
For Academic Year subscribers who need year-round access:
- Prorated credit from remaining Academic Year Plan applied toward Annual Plan cost
- Charged the difference immediately (Stripe handles proration automatically)
- Example: Paid $40 in September, upgrades in November after 2 months ($8.89 used) → charged ~$18.89 to upgrade to Annual
- Renewal date snaps back to original Academic Year start date (e.g. September) — not the upgrade date
- This keeps renewal aligned with the school year even for Annual subscribers who started on Academic Year Plan
### Upgrade Prompt in App
When a teacher in Summer Transition Mode tries to start an assessment:
"Assessment tools are paused during Summer Transition Mode. Upgrade to Annual for full year-round access — your remaining Academic Year credit will be applied."
 
### Academic Year Plan Rollout — Hemisphere Timing
 
The Academic Year Plan launch campaign runs twice a year, timed to each hemisphere's school calendar. Content is essentially identical — just different timing and start date references.
 
**Northern Hemisphere Campaign (US, Canada, UK, Ireland)**
- **Announcement:** May 2027 — as school year wraps up
- **Active period start:** August or September
- **Campaign framing:** "Setting up for next school year? Register your Academic Year dates now."
- **Charge date:** September 1 (or chosen start date)
**Southern Hemisphere Campaign (Australia, New Zealand)**
- **Announcement:** October/November 2027 — as their school year wraps up
- **Active period start:** January or February
- **Campaign framing:** "Setting up for next year? The Academic Year Plan is now available — choose your January start date and lock in your rate."
- **Charge date:** January 1 or February 1 (or chosen start date)
Note: The flexible date picker means AU/NZ teachers can set their own dates regardless of campaign timing — the campaigns just provide a natural, well-timed prompt aligned with how teachers in each hemisphere think about their year.
 
### Northern Hemisphere Announcement Email (May 2027)
"Big news for next school year — introducing the abcAssess Academic Year Plan. Designed for teachers who follow the school calendar, the Academic Year Plan gives you full access during your active months and Summer Transition Mode to transfer students, build your fall roster, and review incoming data — all for $40/year.
 
Want to switch when it launches this fall? Tell us your academic year dates and we'll handle the rest. You'll continue on your current plan until your chosen start date, then automatically switch to Academic Year at $40.
 
[Register my academic year dates]"
 
### Southern Hemisphere Announcement Email (October/November 2027)
"Big news for next year — introducing the abcAssess Academic Year Plan. Designed for teachers who follow the school calendar, the Academic Year Plan gives you full access during your active months and a transition period to transfer students, build your new roster, and review incoming data — all for $40/year.
 
Setting up for your January start? Tell us your academic year dates and we'll handle the rest. You'll continue on your current plan until your chosen start date, then automatically switch to Academic Year at $40.
 
[Register my academic year dates]"
 
### Renewal Email Sequence
- **Late May:** "Summer Transition Mode begins June 1 — start transferring your students."
- **Late June:** "Confirm your renewal for next year — no charge until September 1."
- **Late July:** "Reminder: your Academic Year Plan renews September 1. Update payment details if needed."
- **September 1 (or chosen date):** Charge processes, full access unlocks
### Summer Transition Mode
Summer Transition Mode is not a limitation — it's the season when the most important handoffs happen. Pre-K teachers transfer their graduating students to incoming kindergarten teachers, who receive a complete assessment history before the year even starts. New rosters are built as class lists arrive in August. Incoming teachers can review historical data for their new students and plan instruction before the first day of school.
 
**The core workflow Summer Transition Mode enables:**
A Pre-K teacher transfers all of their students to the kindergarten teacher at the end of the year. The kindergarten teacher receives complete assessment histories for every incoming student — which letters they know, which sounds they're working on, where they need support — and can review and plan all summer. When their new class list arrives in August, they add their incoming students and the year starts with everyone already prepared.
 
**This is the data following the child, not the classroom.**
 
**Allowed in Summer Transition Mode:**
- Create new classes for the upcoming year
- Add new students (as class lists arrive)
- Transfer students from/to other teachers
- Archive or delete old classes and students
- Edit student and class information
- View all historical reports and data for incoming students
- Download/export reports and backups
- Generate and print PDFs
**Not allowed in Summer Transition Mode:**
- Starting new assessments
- Manual entry of assessment data
- Modifying existing assessment records
**Summer Transition Mode UI banner:**
"Academic Year Plan — Summer Transition Mode. Assessment tools resume [start date]. Manage your roster, transfer students, and access all your reports."
 
**Marketing framing:**
"Academic Year Plan includes Summer Transition Mode — transfer your students to next year's teachers, receive incoming rosters, and review historical data so everyone starts September prepared."
 
### Extensions
**Add a Month — $5**
- Extends the active window by 30 days
- Available at any time
- Good for teachers whose year runs longer than expected or who need summer school access
- When second extension month is purchased, prompt to upgrade to Annual:
  "You've added 2 extra months. Upgrading to our Annual Plan gives you full year-round access — just $10 more than your Academic Year Plan."
---
 
## Terms of Service Notes (for Academic Year Plan launch)
 
The following should be added/updated in Terms of Service when Academic Year Plan launches in Fall 2027:
 
- Summer Transition Mode is included at no additional charge as part of the previous year's Academic Year Plan and does not require renewal confirmation to access
- Annual and Academic Year Plan subscriptions are non-refundable after the charge date
- Mid-year cancellations retain access through end of paid period — no partial refunds
- Academic Year Plan renewals confirmed but not yet charged can be cancelled before the charge date with no penalty
- No automatic renewal charge is processed without explicit renewal confirmation from the teacher
- Active period maximum is 10 months — minimum 2 months Summer Transition Mode required
- Plan switches and upgrades use Stripe prorated credits — teacher is shown exact charge before confirming
- Renewal date on Annual Plan upgrade snaps to original Academic Year start date, not upgrade date
---
 
## Subscription Infrastructure Notes (for Emergent — Fall 2027)
 
The subscription system needs to track per teacher account:
- Plan type (monthly, annual, academic year)
- Active window start and end dates (academic year plan only)
- Active period length in months
- Current mode (active or summer transition mode)
- Renewal confirmed but not yet charged status
- Pending plan switch (e.g. Annual → Academic Year scheduled for future date)
- Extension months purchased
- Upgrade history
- Renewal date (always snaps to Academic Year start date for plan switchers)
- Beta/founding member status
- Free year expiry date (beta participants)
### Academic Year Plan Settings UI
Display in Account Settings:
"Your active period: [start date] — [end date]
Summer Transition Mode begins: [day after end date]
Next charge: $40 on [start date, following year] — confirmed / not yet confirmed"
 
Options visible in settings:
- Confirm renewal for next year (no charge until start date)
- Add a month ($5)
- Upgrade to Annual (prorated difference charged, renewal date preserved)
- Cancel renewal confirmation
- Cancel subscription
### Date Picker Rules
- Maximum active period: 10 months
- Minimum active period: 6 months (under 6 months → recommend Monthly)
- Minimum Summer Transition Mode: 2 months
- UI enforces these limits at date selection
---
 
## Pre-Launch Checklist (Business & Legal)
 
**Business Structure:**
- [ ] Register abcAssess LLC in North Dakota (~$135 filing fee, businessreg.nd.gov) — prioritize before scaling beta
- [ ] Open business bank account (Relay or Mercury recommended for SaaS)
- [ ] Update all legal documents to reflect LLC name once registered
**Legal:**
- [ ] Attorney review of Privacy Policy, Terms of Service, and DPA before fall launch — focus on FERPA, COPPA, GDPR, PIPEDA, Australian Privacy Principles, NZ Privacy Act
- [ ] Appoint EU Representative for GDPR compliance (required for non-EU companies processing EU data) — services available for ~$200–$500/year
- [ ] Appoint UK Representative for UK GDPR compliance (separate from EU representative) — similar cost
- [ ] Confirm with attorney whether data residency requirements apply for UK/Ireland users at current scale
**Insurance:**
- [ ] Research and purchase insurance:
  - [ ] General Liability (~$300–$600/year)
  - [ ] Errors & Omissions / Professional Liability (~$500–$1,500/year)
  - [ ] Cyber Liability (~$500–$2,000/year) — priority given student data handling
  - [ ] Recommended providers: Embroker, Hiscox, Coalition, Simply Business
- [ ] Inform insurance provider of international user base (US, Canada, Australia, New Zealand, UK, Ireland)
- [ ] When signing UK/Australia school contracts, confirm local insurance requirements are met
**Payment & Billing:**
- [ ] Set up Stripe for payment processing
- [ ] Enable Stripe Tax for automatic VAT (UK/Ireland) and GST (Australia/New Zealand) collection
- [ ] Decide on currency display — USD globally to start, local currency display future consideration
- [ ] Note: VAT registration required in UK when revenue exceeds £85,000; Ireland €37,500; Australia AUD $75,000; New Zealand NZD $60,000 — not immediate concerns
**Infrastructure:**
- [ ] Plan MongoDB Atlas EU region cluster for UK/Ireland user data as those markets grow — not urgent at launch but plan ahead
- [ ] Audit app for US-only hardcoding — date formats, phone fields, address fields (see Emergent list)
- [ ] Enable date localization in app — DD/MM/YYYY for AU, NZ, UK, Ireland; MM/DD/YYYY for US, Canada
**Beta & Launch:**
- [ ] Finalize beta participant list and define "active" threshold for free year eligibility
- [ ] Send written confirmation of free year offer to all beta participants
- [ ] Build subscription management into app (plan selection, billing, free trial, upgrades)
- [ ] Set up 14-day free trial in Stripe — credit card required at end to continue, not upfront
---
 
## Beta Growth Goals
 
- **Current:** 4 active beta teachers
- **Target by October 1:** TBD
- **Key opportunity:** August back-to-school meetings and PD days at interested centers
- **Strategy:** Personal outreach to center contacts, demo at staff meetings, word-of-mouth from existing beta teachers
---
 
*This document should be updated as pricing is validated through real market conversations.*
*Do not publish externally — internal planning document only.*
