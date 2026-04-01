# Study Protocol — Civic Snap (Civic Sense)
**Group Number:** [Insert Group Number]
**Course:** User Experience Design
**Date of Testing:** [Insert Date]
**Version:** 1.0 — Paper + Digital Prototype Testing

---

## 1. Introduction

### 1.1 Project Overview
**Civic Snap** is a civic issue reporting and management platform that connects citizens, field workers, and government officials. Citizens report infrastructure problems (potholes, broken streetlights, garbage overflow, etc.) through a mobile app. The system auto-routes reports to the correct agency, assigns field workers, tracks resolution, and requires citizen verification before closing a ticket.

### 1.2 Purpose of This Study
This study evaluates the usability, clarity, and task-completion effectiveness of the Civic Snap prototype at two stages:

1. **Paper Prototype Testing** (Low-fidelity) — Validate core flow logic, information architecture, and task understandability.
2. **Digital Hi-Fi Prototype Testing** — Validate visual design, interaction patterns, navigation clarity, and overall user experience after incorporating learnings from paper testing.

### 1.3 Research Questions
- Can users successfully complete core tasks without guidance?
- Do users understand the purpose of each screen and the overall flow?
- Are labels, icons, and navigation elements intuitive?
- Where do users hesitate, mis-click, or express confusion?
- Does the multi-role design (Citizen / Field Worker / Govt Official) feel coherent?

---

## 2. Participant Criteria

### 2.1 Inclusion Criteria
- Age 18+
- Owns and regularly uses a smartphone
- Has experienced at least one civic infrastructure issue in their city (pothole, broken light, garbage, etc.)
- Comfortable using at least 2 mobile apps regularly

### 2.2 Target Participants Per Round
| Round | Minimum | Ideal | Roles Tested |
|-------|---------|-------|-------------|
| Paper Prototype | 2 | 3-5 | Citizen flows |
| Digital Hi-Fi | 2 | 3-5 | Citizen + Field Worker + Govt Official |

### 2.3 Recruitment Method
- Convenience sampling (classmates, friends, family)
- Brief screening questionnaire before scheduling

---

## 3. Testing Environment & Materials

### 3.1 Paper Prototype Testing
- **Materials:** Printed paper screens, pen for annotations, sticky notes
- **Setting:** Quiet room, table, phone camera or laptop for screen recording
- **Recording:** Video recording of participant's hands + verbal think-aloud
- **Facilitator Role:** One person acts as the "computer" — swapping paper screens based on participant actions

### 3.2 Digital Hi-Fi Prototype Testing
- **Materials:** Digital prototype link opened on participant's phone or a shared tablet
- **Setting:** Quiet room, screen recording enabled
- **Recording:** Screen recording + audio recording of think-aloud
- **Facilitator Role:** Observe, prompt, take notes — do NOT guide or explain

---

## 4. Testing Structure (Both Rounds)

Each session follows this structure:

| Phase | Duration | Description |
|-------|----------|-------------|
| Welcome & Consent | 3 min | Explain study purpose, get verbal consent, explain recording |
| Pre-Interview | 5 min | Background questions about civic issue experience |
| Task Execution | 15-20 min | Participant completes 4-5 tasks with think-aloud |
| Post-Interview | 10 min | Follow-up questions, SUS (System Usability Scale) |
| Wrap-Up | 2 min | Thank participant, stop recording |

**Total Session Duration:** ~35-40 minutes

---

## 5. Tasks — Paper Prototype Testing (Citizen Flows)

### Task 1: Account Creation & Login
**Scenario:** "You just downloaded the Civic Snap app. You want to create an account using your phone number so you can start reporting issues."

**Expected Path:** Landing Page → Enter Phone Number → OTP Verification → Profile Setup → Home Dashboard

**Success Criteria:**
- Participant understands they need to enter a phone number
- Participant understands the OTP step
- Participant completes profile setup without confusion
- Participant lands on the Home Dashboard

**Observe:**
- Does the participant hesitate at any step?
- Do they understand what "OTP" means?
- Is the profile setup form clear?

---

### Task 2: Report a Pothole
**Scenario:** "You're walking home and notice a large pothole on your street. You want to report it through the app."

**Expected Path:** Home Dashboard → Tap "Report Issue" → Select Category (Road/Pothole) → Take/Upload Photo → Add Description → Confirm Location → Submit → Confirmation Screen

**Success Criteria:**
- Participant finds the report button easily
- Participant understands category selection
- Participant knows how to add a photo
- Participant understands location confirmation
- Participant sees and understands the submission confirmation

**Observe:**
- Can they find the primary action button?
- Do they understand the AI auto-tagging concept?
- Is the location step clear?
- Do they notice the anonymous reporting option?

---

### Task 3: Check Report Status
**Scenario:** "You reported a broken streetlight last week. You want to check if it's been fixed."

**Expected Path:** Home Dashboard → Tap "My Reports" → Find the streetlight report → View Status/Tracking Screen

**Success Criteria:**
- Participant navigates to My Reports from home
- Participant can identify their past report
- Participant understands the status indicator (e.g., "In Progress", "Resolved")
- Participant understands the tracking timeline

**Observe:**
- Is the navigation to My Reports intuitive?
- Can they read and understand status labels?
- Do they understand the stage-gate progress bar?

---

### Task 4: Verify a Fix
**Scenario:** "You received a notification that the pothole you reported has been repaired. The app asks you to verify the fix."

**Expected Path:** Notification → Tap Notification → View Before/After Photos → Confirm Fix or Dispute → Confirmation + Karma Points

**Success Criteria:**
- Participant understands they need to verify
- Participant can compare before/after photos
- Participant knows how to confirm or dispute
- Participant understands the outcome (karma points or dispute process)

**Observe:**
- Is the before/after comparison clear?
- Do they understand what happens if they dispute?
- Is the karma/trust points concept clear?

---

### Task 5: Browse Nearby Issues (Optional — time permitting)
**Scenario:** "You're curious about what other issues people in your area have reported. Browse the public reports near you."

**Expected Path:** Home Dashboard → Tap "Nearby Issues" or "Map View" → Browse public reports → Tap one to view details

**Success Criteria:**
- Participant finds the public/nearby issues section
- Participant can view details of a public report
- Participant understands what information is public vs private

**Observe:**
- Is the map/list view intuitive?
- Do they understand which reports are public?

---

## 6. Tasks — Digital Hi-Fi Prototype Testing

### Task 1: Complete End-to-End Report Flow
**Scenario:** "You notice water leaking from a broken pipe on your street. Report it from start to finish."

**Expected Path:** Login → Home → Report Issue → Category → Photo → Description → Location → Submit → Confirmation

**Success Criteria:** Same as paper Task 2, plus evaluate visual clarity and interaction smoothness.

---

### Task 2: Track & Verify a Report
**Scenario:** "Check the status of your most recent report. If it shows as resolved, verify the fix."

**Expected Path:** Home → My Reports → Select Report → View Tracking → Verify/Dispute

**Success Criteria:** Same as paper Tasks 3 + 4 combined.

---

### Task 3: Field Worker — View & Complete Task (if testing FW flow)
**Scenario:** "You are a field worker. Log in, check your assigned tasks, and mark one as complete."

**Expected Path:** FW Login → Task Queue → Select Task → View Details → Upload After Photo → Mark Complete → GPS Confirmation

**Success Criteria:**
- FW can identify assigned vs pending tasks
- FW understands task details and location
- FW knows how to upload completion proof
- FW understands GPS verification step

---

### Task 4: Govt Official — Review & Assign (if testing GO flow)
**Scenario:** "You are a government office staff member. Review incoming reports and assign a ticket to a field worker."

**Expected Path:** GO Login → Dashboard/Heatmap → Review Report → Create/Assign Ticket → Assign to FW

**Success Criteria:**
- GO can see incoming report volume and priority
- GO understands the assignment interface
- GO can select appropriate field worker

---

## 7. Pre-Interview Questions

Ask these before starting tasks. Record answers.

1. What is your age range? (18-24 / 25-34 / 35-44 / 45-54 / 55+)
2. How would you rate your comfort level with smartphone apps? (1-5 scale)
3. Have you ever reported a civic issue (pothole, garbage, streetlight, etc.) to authorities? If yes, how?
4. Have you used any civic/government apps before? Which ones?
5. What frustrates you most about the current process of reporting civic issues?
6. What would make you more likely to report an issue if you had an app for it?

---

## 8. Post-Interview Questions

Ask these after task completion. Record answers.

### 8.1 Task-Specific Questions
1. Which task was the easiest? Which was the hardest? Why?
2. Was there any screen where you weren't sure what to do next?
3. Did any label, icon, or button confuse you?
4. How did you feel about the number of steps required to report an issue?
5. Did you understand what happens after you submit a report?

### 8.2 System Usability Scale (SUS)
Rate each statement from 1 (Strongly Disagree) to 5 (Strongly Agree):

| # | Statement | Score (1-5) |
|---|-----------|-------------|
| 1 | I think I would like to use this app frequently | |
| 2 | I found the app unnecessarily complex | |
| 3 | I thought the app was easy to use | |
| 4 | I think I would need the support of a technical person to use this app | |
| 5 | I found the various functions were well integrated | |
| 6 | I thought there was too much inconsistency in the app | |
| 7 | I would imagine most people would learn to use this app very quickly | |
| 8 | I found the app very cumbersome/difficult to use | |
| 9 | I felt very confident using the app | |
| 10 | I needed to learn a lot of things before I could get going with this app | |

**SUS Score Calculation:**
- Odd items: Score - 1
- Even items: 5 - Score
- Sum all × 2.5 = SUS Score (out of 100)

### 8.3 Open-Ended Questions
1. If you could change one thing about this app, what would it be?
2. Would you trust this app with your location data? Why or why not?
3. Would you recommend this app to a friend? Why or why not?
4. Any additional comments or suggestions?

---

## 9. Data Collection & Analysis Plan

### 9.1 Metrics to Track
| Metric | Description |
|--------|-------------|
| Task Completion Rate | % of tasks completed successfully without help |
| Time on Task | Time taken to complete each task |
| Error Rate | Number of wrong taps, backtracks, or confusions |
| SUS Score | System Usability Scale score |
| Verbal Cues | Positive/negative comments during think-aloud |
| Hesitation Points | Screens where participant paused >5 seconds |

### 9.2 Analysis Method
1. Transcribe each session within 24 hours
2. Code transcript for: confusion points, positive moments, suggestions
3. Aggregate findings across all participants
4. Identify top 5 usability issues by frequency and severity
5. Map each issue to a specific design change
6. Create a "Changes Made" summary linking feedback → action

---

## 10. Ethical Considerations

1. **Informed Consent:** Participants will be informed about the study purpose, recording, and their right to withdraw at any time. Verbal consent will be recorded.
2. **Anonymity:** Participant names will be replaced with codes (P1, P2, etc.) in all documentation.
3. **Data Storage:** Recordings will be stored securely and deleted after the course ends.
4. **No Deception:** Participants will be told this is a prototype, not a real app.
5. **Minimal Risk:** The study involves no physical or psychological risk.
6. **Voluntary Participation:** Participants can stop at any time without penalty.

---

## 11. Facilitator Checklist

### Before Session
- [ ] Print/prepare prototype screens
- [ ] Set up recording device
- [ ] Prepare consent script
- [ ] Prepare task cards
- [ ] Prepare note-taking template
- [ ] Test prototype (paper or digital)

### During Session
- [ ] Record session (with consent)
- [ ] Take timestamped notes
- [ ] Do NOT guide or explain (let them struggle productively)
- [ ] Prompt think-aloud: "What are you thinking right now?"
- [ ] Note exact words of confusion or praise

### After Session
- [ ] Stop recording
- [ ] Thank participant
- [ ] Transcribe within 24 hours
- [ ] Log key findings in tracking sheet

---

**Document Prepared By:** [Your Name]
**Date:** [Date]
**Version:** 1.0
