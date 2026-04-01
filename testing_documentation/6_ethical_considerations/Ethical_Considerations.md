# Ethical Considerations — Civic Snap (Civic Sense)
**Project:** Civic Snap — Civic Issue Reporting & Management Platform
**Group Number:** [Insert Group Number]
**Course:** User Experience Design
**Version:** 1.0

---

## 1. Introduction

Civic Snap is a platform that connects citizens, field workers, and government officials for reporting, tracking, and resolving civic infrastructure issues. As a system that handles personal data, location information, public reporting, and government accountability, it raises several ethical considerations that must be addressed in its design and implementation.

---

## 2. Data Privacy & Collection

### 2.1 Location Data
**Concern:** The app requires access to the user's GPS location to accurately report issues and route them to the correct department.

**Ethical Implications:**
- Location data is sensitive personal information that can reveal a user's home, workplace, and daily routines
- Continuous or background location tracking could enable surveillance
- Location data could be misused if shared with third parties or accessed by unauthorized personnel

**Mitigation Strategies:**
- Request location permission only when actively reporting an issue (foreground-only access)
- Provide a manual location pin-drop option for users who deny location permission
- Store only the coordinates needed for the report — not continuous location history
- Clearly explain in plain language why location is needed and how it will be used
- Allow users to delete their location data from individual reports
- Publish a clear, readable privacy policy (not legal jargon)

### 2.2 Personal Information
**Concern:** The app collects phone numbers, names, profile photos, and area/ward information during registration.

**Ethical Implications:**
- Phone numbers can be used to identify and contact users outside the app
- Profile photos and names make reporters identifiable to government officials
- Data breaches could expose personal information of civic activists

**Mitigation Strategies:**
- Implement anonymous reporting option (prominent toggle — tested and validated)
- Minimize data collection — only collect what is necessary for the service
- Use phone number hashing for internal identification rather than storing raw numbers
- Allow users to delete their account and all associated data
- Encrypt personal data at rest and in transit
- Implement role-based access control — field workers should not see reporter identities unless necessary

---

## 3. Informed Consent

### 3.1 User Consent
**Concern:** Users must understand what data is collected, how it is used, and what rights they have.

**Ethical Implications:**
- Most users do not read privacy policies or terms of service
- Consent obtained through confusing interfaces is not truly informed
- Users may not understand the implications of anonymous vs. identified reporting

**Mitigation Strategies:**
- Use layered consent — brief summary at key moments, detailed policy available on demand
- Present consent in plain language at the point of data collection (e.g., "We need your location to place the pin accurately. Your location is only stored with this report.")
- Make the anonymous reporting toggle prominent and explain its implications clearly
- Allow users to withdraw consent and delete their data at any time
- Use just-in-time explanations rather than a single upfront consent wall

### 3.2 Testing Consent
**Concern:** User testing sessions involve recording participants' interactions and verbal responses.

**Ethical Implications:**
- Participants may not fully understand how their recordings will be used
- Recordings could capture sensitive information inadvertently shared during testing

**Mitigation Strategies:**
- Obtain explicit verbal consent before each recording session
- Explain the purpose, duration, and storage of recordings
- Allow participants to withdraw at any time without penalty
- Anonymize all participant data in documentation (use codes: P1, P2, etc.)
- Delete recordings after the course ends

---

## 4. Equity & Accessibility

### 4.1 Digital Divide
**Concern:** A smartphone-based reporting system excludes citizens who do not own smartphones or lack digital literacy.

**Ethical Implications:**
- The most marginalized communities (low-income, elderly, rural) may be the ones most affected by civic issues but least able to use the app
- This could create a two-tier system where affluent neighborhoods get faster responses

**Mitigation Strategies:**
- Provide alternative reporting channels: WhatsApp bot, SMS-based reporting, phone helpline
- Design the app with accessibility in mind: large text, high contrast, simple navigation (validated with P4, age 45-54)
- Support multiple languages relevant to the local population
- Partner with community organizations to help non-digital citizens report issues
- Ensure the government backend treats all reports equally regardless of submission channel

### 4.2 Language & Literacy
**Concern:** The app currently uses English, which may not be accessible to all citizens.

**Ethical Implications:**
- Non-English speakers may be unable to report issues or understand status updates
- Technical jargon (even simplified) may be inaccessible to users with lower education levels

**Mitigation Strategies:**
- Support local languages (Kannada, Hindi, etc. for Bangalore context)
- Use icon-based navigation alongside text (validated in hi-fi testing — P4 found icons helpful)
- Avoid technical terminology in citizen-facing interfaces
- Use simple, short sentences in all user-facing text
- Provide voice input option for users who cannot type (suggested by P4)

---

## 5. Accountability & Transparency

### 5.1 Government Accountability
**Concern:** The app creates a public record of government responsiveness, which could be politically sensitive.

**Ethical Implications:**
- Government officials may resist transparency or manipulate data
- Unresolved reports could reflect poorly on specific departments or individuals
- There is a risk of retaliation against citizens who report issues in certain contexts

**Mitigation Strategies:**
- Make aggregate data public (number of reports, resolution rates by ward) without exposing individual reporters
- Implement an audit trail that cannot be altered (verified audit trail feature)
- Protect reporter identities in public-facing data
- Design the system so that data flows automatically — manual intervention should be logged
- Include escalation mechanisms for reports that are not addressed within SLA

### 5.2 Algorithmic Fairness
**Concern:** The app uses AI auto-tagging to classify issues from photos, which could introduce bias.

**Ethical Implications:**
- AI misclassification could route reports to the wrong department, causing delays
- Training data bias could result in better accuracy for certain types of issues or locations
- Users may over-trust AI decisions without understanding their limitations

**Mitigation Strategies:**
- Always allow users to review and edit AI-detected tags (validated in hi-fi testing — "Add Tag" and "Remove Tag" features)
- Display AI confidence levels or uncertainty indicators
- Provide a manual category override option
- Regularly audit AI accuracy across different issue types and locations
- Be transparent about AI use — label auto-tagged content clearly

---

## 6. Gamification Ethics

### 6.1 Karma & Trust Points
**Concern:** The app uses a gamification system (karma points, trust levels) to incentivize civic participation.

**Ethical Implications:**
- Gamification could encourage frivolous or false reporting to earn points
- Trust points that affect response priority could create inequality — wealthy or active users get faster service
- The system could be gamed by coordinated groups

**Mitigation Strategies:**
- Award points only for verified actions (confirmed fixes, not just reports)
- Implement fraud detection for suspicious reporting patterns
- Ensure that trust points affect priority within a reasonable range — not to the extent that low-trust users are ignored
- Make the karma algorithm transparent so users understand how points are earned
- Allow users to opt out of the gamification system if they find it manipulative

---

## 7. Surveillance & Misuse

### 7.1 Citizen Surveillance
**Concern:** The app's reporting features could be misused to surveil or harass individuals or communities.

**Ethical Implications:**
- Reports could be filed against specific individuals (e.g., street vendors, homeless people) rather than infrastructure issues
- Photo evidence could capture identifiable individuals without consent
- Coordinated reporting campaigns could target specific neighborhoods or communities

**Mitigation Strategies:**
- Focus the app on infrastructure issues, not people — category selection should guide users toward appropriate reports
- Blur faces and license plates in uploaded photos automatically
- Implement rate limiting to prevent spam reporting
- Review and moderate reports that appear to target individuals rather than infrastructure
- Provide clear guidelines on appropriate use during onboarding

### 7.2 Field Worker Surveillance
**Concern:** Field workers are tracked via GPS and their work is documented with before/after photos.

**Ethical Implications:**
- GPS tracking of workers raises privacy concerns
- Photo documentation could be used to unfairly penalize workers
- Workers may feel constantly monitored, leading to stress

**Mitigation Strategies:**
- Limit GPS tracking to work hours and assigned task locations only
- Use GPS data for verification, not continuous monitoring
- Provide workers with visibility into their own performance data
- Implement a fair dispute process for workers who disagree with citizen verification
- Ensure worker data is not used for punitive action without due process

---

## 8. Data Retention & Deletion

### 8.1 Report Data
**Concern:** How long should report data be retained?

**Ethical Implications:**
- Indefinite retention increases breach risk and privacy exposure
- Premature deletion could destroy accountability records
- Users may want to delete their report history

**Mitigation Strategies:**
- Define clear retention periods: active reports retained until resolution + 1 year; anonymized aggregate data retained for analytics
- Allow users to delete their personal data while preserving anonymized report records
- Implement automatic data purging after retention periods expire
- Provide users with a data export option (right to data portability)

---

## 9. Summary of Key Ethical Principles

| Principle | Application in Civic Snap |
|-----------|--------------------------|
| **Privacy by Design** | Minimal data collection, anonymous reporting, encrypted storage |
| **Transparency** | Clear progress tracking, audit trails, open aggregate data |
| **Equity** | Multi-channel reporting, accessibility features, multi-language support |
| **Accountability** | Unalterable audit logs, SLA tracking, escalation mechanisms |
| **User Autonomy** | Opt-out options, data deletion, consent withdrawal |
| **Fairness** | AI review and edit, fraud detection, equal treatment across channels |
| **Safety** | Face blurring, rate limiting, appropriate-use guidelines |

---

## 10. Ethical Review Checklist

- [x] Informed consent process defined for user testing
- [x] Data collection minimized to necessary information only
- [x] Anonymous reporting option prominently available
- [x] Location access limited to foreground use only
- [x] Plain-language privacy explanations at point of collection
- [x] Accessibility validated with diverse age groups (18-24, 45-54)
- [x] AI auto-tagging includes user review and edit capability
- [x] Gamification system includes fraud prevention
- [x] Alternative reporting channels planned (WhatsApp, SMS)
- [x] Data retention and deletion policies defined
- [x] Worker privacy protections included
- [x] Face/license plate blurring planned for photos
- [ ] Multi-language support (planned for future iteration)
- [ ] Voice input option (suggested by testing — planned for future)
- [ ] Formal privacy policy document (to be drafted)

---

**Document Prepared By:** [Your Name]
**Date:** [Date]
**Version:** 1.0
