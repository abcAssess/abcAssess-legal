---
layout: default
title: Accessibility Statement
description: Version 2.2 · Updated June 16, 2026
---

<style>
  .btn { display: none !important; }
  header .project-tagline { margin-bottom: 2rem; }
</style>

[Return to Support Center](index.md)

---

## Our Commitment

#### At abcAssess, we believe every teacher deserves access to high-quality classroom assessment tools — regardless of ability. We are committed to ensuring that our web platform and native iOS and Android applications are accessible to educators and administrators with diverse abilities.

#### We continually audit, test, and improve our interfaces to provide a seamless and supportive experience for all users. Accessibility is not an afterthought — it is built into our design and development process from the start.

#### abcAssess is committed to compliance with the Web Content Accessibility Guidelines (WCAG) 2.1 Level AA, Section 508 of the Rehabilitation Act of 1973, and the Americans with Disabilities Act (ADA) Title III as applied to web-based services, as well as equivalent accessibility standards in the United Kingdom, Australia, New Zealand, Canada, and Ireland. Where our platform falls short of full conformance, we are actively working to close those gaps and welcome feedback from any user who encounters a barrier.

---

## Conformance Status

#### The Web Content Accessibility Guidelines (WCAG) define technical requirements for making digital content accessible to people with disabilities. abcAssess is designed to meet WCAG 2.1 Level AA across both our web platform and native mobile applications.

**Current Status:** Partially Conformant with WCAG 2.1 Level AA. This means that some parts of our platform do not yet fully meet all guidelines. We are actively working toward full conformance and provide the known limitations and our remediation roadmap below. Users who encounter a specific barrier may request an accessible alternative by contacting us at support@abcassess.app.

---

## Accessibility Features

#### abcAssess implements the following accessibility features across our web and mobile platforms: 

- **Screen Reader Support**  
  Our web platform uses semantic HTML landmarks and structured heading elements (H1, H2, etc.) to support screen reader navigation. Our native iOS and Android applications include explicit accessibility labels on all interactive elements to ensure compatibility with VoiceOver (iOS) and TalkBack (Android).

- **Keyboard and Switch Access**  
  Our web platform is fully navigable using a standard keyboard, with visible focus indicators on all interactive elements. Our mobile applications are optimized for use with iOS Switch Control, Android Switch Access, and standard assistive gesture navigation.

- **Color Contrast**  
  Our core color palette enforces a minimum contrast ratio of 4.5:1 between text and background elements, meeting WCAG 2.1 Level AA requirements. This supports readability in a range of lighting conditions, including brightly lit classroom environments.

- **Colorblind-Accessible Assessment Tracking**  
  abcAssess uses a combined color and symbol system throughout the platform to communicate student proficiency levels, ensuring that information is never conveyed by color alone. Each proficiency level is represented by both a color and a distinct symbol:
  - ✓ Proficient (sage green)
  - ~ Developing (amber)
  - ! Emerging (terracotta)
  - — Not Applicable (grey)
  This system appears in the in-app tracking chart, individual student profiles (Current Mastery and Assessment History), and throughout all printed and PDF reports. In reports, proficiency zones are additionally represented by pattern fills (diagonal lines, horizontal lines, and dots) alongside colors, ensuring full accessibility in black-and-white print output. This system was designed specifically to support educators with color vision deficiencies and meets WCAG 2.1 Success Criterion 1.4.1 (Use of Color).

- **Accessibility Settings**  
  abcAssess provides a dedicated Accessibility section in Settings, organized into the following groups:
  - *Visual Accessibility*  
    Show proficiency symbols — teachers can show or hide the ✓ ~ ! — symbol system alongside colors throughout the app. Default on. Recommended for colorblind users.
  - *Motion & Sensitivity*  
    Reduced motion — teachers can disable confetti animations and dialog slide-up animations for users sensitive to motion or flashing content. Default off.
  - *Sensory Feedback*  
    Assessment sounds — teachers can enable or disable audio feedback including the timed assessment alert sound and assessment completion chime. Default on.
    Haptics — teachers can enable or disable vibration feedback when an assessment is completed. Available on mobile devices only. Default on.


- **Audio Assessment Support**  
  abcAssess supports optional audio prompts during assessments, including teacher-recorded audio for custom assessment items. This feature supports educators working with diverse learners and allows teachers to provide consistent, accessible verbal prompts without relying solely on visual content. Teachers can enable or disable audio prompts per assessment type in their assessment settings.

- **Touch Target Sizing**  
  All interactive elements on our native mobile applications — including buttons, toggles, and list items — maintain a minimum tap target size of 48x48 pixels, consistent with WCAG 2.1 Success Criterion 2.5.5 and platform guidelines from Apple and Google.

- **Text Alternatives for Images**  
  Non-decorative system images include descriptive text alternatives. For teacher-uploaded instructional content — such as custom assessment images or audio prompts — our assessment builder provides fields for educators to assign their own descriptive labels within their content library. abcAssess cannot guarantee the accessibility of user-generated content, but we provide the tools to support it.

---

## Known Limitations

#### We are transparent about the areas of our platform that do not yet meet full WCAG 2.1 Level AA conformance. We are actively working to address each of the following:

  - *Complex Data Visualizations:* Class-wide analytics dashboards, historical progress charts, and report snapshots do not yet include comprehensive text or audio equivalents for all visual data. We are working to add accessible data table alternatives and descriptive summaries for these views.
  - *Accessible Data Exports:* We are developing accessible, high-contrast CSV data exports for all roster summaries and student progress records. This feature is currently in development. Users who need immediate access to data in an alternative format may contact us at support@abcassess.app and we will work to accommodate the request manually.
  - *User-Generated Content:* abcAssess cannot guarantee the accessibility of assessment content, images, or templates created or shared by other teachers using the platform. We encourage all educators to use the descriptive labeling tools available in the assessment builder when creating or sharing content.

---

## Legal Framework

#### abcAssess is committed to compliance with the following legal frameworks as they apply to our platform and user base:

- **United States**  
  - *WCAG 2.1 Level AA* — Our primary technical accessibility standard for web and mobile interfaces.
  - *Section 508* — Applicable to federally funded programs and institutions using our platform. We design to Section 508 technical standards, which align closely with WCAG 2.1 AA.
  - *ADA Title III* — Increasingly applied to web-based services and applications. We design our platform to meet ADA Title III standards for accessibility of public-facing digital services.
  - *IDEA* — We recognize that many of our users serve students with disabilities under the Individuals with Disabilities Education Act, and we design our tools to support educators working in those environments.

- **United Kingdom**  
  - *Equality Act 2010* — We design our platform to meet the accessibility requirements of the Equality Act 2010 as applied to digital services.
  - *Public Sector Bodies Accessibility Regulations 2018* — Where applicable to institutions using abcAssess, we design to these standards which align with WCAG 2.1 AA.

- **Australia**  
  - *Disability Discrimination Act 1992 (Cth)* — We design our platform to avoid discrimination on the basis of disability consistent with the DDA and the Web Accessibility National Transition Strategy.

- **New Zealand**  
  - *Human Rights Act 1993* — We design our platform to meet accessibility obligations consistent with New Zealand's human rights framework for digital services.

- **Canada**  
  - *Accessible Canada Act (ACA)* — We design our platform consistent with the principles of the Accessible Canada Act and applicable provincial accessibility legislation.

- **Ireland**
  - *Equal Status Acts 2000–2018* — We design our platform to meet the accessibility requirements of Irish equality legislation as applied to digital services.

---

## Feedback and Accessibility Requests

#### We welcome feedback from teachers, administrators, specialists, and assistive technology users. If you encounter an accessibility barrier — a missing label, an inaccessible feature, or any element that prevents you from using abcAssess effectively — please let us know.

When you contact us with an accessibility concern, we commit to the following:  
  - Acknowledge your report within 2 business days.
  - Provide an initial response with a resolution plan or workaround within 10 business days.
  - Where an immediate fix is not possible, offer a reasonable alternative means of accessing the relevant feature or content upon request.

We treat accessibility reports as high-priority feedback and use them to inform our ongoing development roadmap.

| | |
|---|---|
| **Email** | [support@abcassess.app](mailto:support@abcassess.app) |
| **Subject Line** | Please include "Accessibility" in your subject line |
| **Response Time** | Acknowledgment within 2 business days; resolution plan within 10 |

---

## Updates to This Statement

#### We review and update this Accessibility Statement as our platform evolves and as we make progress toward full WCAG 2.1 Level AA conformance. The Effective Date and Version number at the top of this document reflect the most recent revision. Material updates will be communicated to active account holders in accordance with our standard notification policy.

--- 

[Data Processing Agreement](dpa.md) &nbsp;-&nbsp; [Privacy Policy](privacy-policy.md) &nbsp;-&nbsp; [Technical FAQs](technical-and-privacy-faqs.md) &nbsp;-&nbsp; [Terms of Service](terms-of-service.md) &nbsp;-&nbsp; [User Guide](User-guide.md) 

[Return to Support Center](index.md)
