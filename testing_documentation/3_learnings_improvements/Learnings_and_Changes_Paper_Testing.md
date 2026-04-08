# Learnings from Paper Prototype Testing & Summary of Changes
**Project:** Civic Snap (Civic Sense)
**Testing Round:** Paper Prototype (Low-Fidelity)
**Participants:** P1 (25-34, tech-savvy), P2 (35-44, moderate tech comfort)
**Testing Date:** [Insert Date]
**Average SUS Score:** 87.5/100 (P1: 95, P2: 80)

---

## 1. Executive Summary

Both participants responded positively to the Civic Snap paper prototype. The core concept — report, track, verify — resonated strongly. The most praised features were the progress tracking bar, report ID system, before/after verification, and karma gamification. The most consistent criticism was information density on the tracking screen and ambiguous terminology. Both participants said they would use and recommend the app, contingent on actual government responsiveness.

**Key Finding:** The information architecture and task flows are fundamentally sound. Changes needed are primarily about clarity, labeling, progressive disclosure, and visual hierarchy — not structural redesign.

---

## 2. Findings by Task

### Task 1: Account Creation & Login
| Finding | P1 | P2 | Severity |
|---------|----|----|----------|
| Phone-only login appreciated | ✅ | ✅ | — |
| No Continue button after entering phone number | ⚠️ | ⚠️ | Critical |
| OTP flow clear and well-understood | ✅ | ✅ | — |
| Area input method unclear (dropdown vs type) | ⚠️ | ⚠️ | Medium |
| Profile photo requirement unclear | ⚠️ | ⚠️ | Medium |
| Wanted auto-detect for area/ward | — | ⚠️ | Low |
| Asked about changing phone number later | — | ⚠️ | Low |

**Insight:** The login flow works well. The profile setup screen needs clearer labels and optional indicators.

---

### Task 2: Report a Pothole
| Finding | P1 | P2 | Severity |
|---------|----|----|----------|
| "Report Issue" button found immediately | ✅ | ✅ | — |
| Category selection with icons intuitive | ✅ | ✅ | — |
| AI auto-tagging concept understood | ✅ | ✅ | — |
| AI auto-detected tags have NO X/cross button to remove them | ⚠️ | ⚠️ | High |
| GPS location step clear | ✅ | ✅ | — |
| GPS location step clear | ✅ | ✅ | — |
| Map pin adjustment appreciated | ✅ | ✅ | — |
| Anonymous reporting toggle too small | ⚠️ | ⚠️ | High |
| Report ID and ETA built confidence | ✅ | ✅ | — |
| Flow felt slightly long but acceptable | ⚠️ | ✅ | Low |

**Insight:** The reporting flow is the strongest part of the prototype. However, AI auto-detected tags have no X/cross button, so users cannot remove incorrect tags — this is a critical issue that could lead to reports being routed to the wrong department. The anonymous reporting toggle also needs to be more prominent.

---

### Task 3: Check Report Status
| Finding | P1 | P2 | Severity |
|---------|----|----|----------|
| Progress bar was clearest element | ✅ | ✅ | — |
| Color-coded status badges understood | ✅ | ✅ | — |
| Delay notice appreciated for transparency | ✅ | ✅ | — |
| Screen too information-dense | ⚠️ | ⚠️ | High |
| "Stage-gates" terminology confusing | ⚠️ | ⚠️ | High |
| "Digital Handshake" terminology confusing | ⚠️ | ⚠️ | High |
| Activity log and agency tasks below fold | ⚠️ | ⚠️ | Medium |
| Suggested simple vs detailed view | ⚠️ | ⚠️ | High |

**Insight:** This is the most critical finding. The tracking screen has the right information but presents it all at once. Progressive disclosure is needed.

---

### Task 4: Verify a Fix
| Finding | P1 | P2 | Severity |
|---------|----|----|----------|
| Before/after comparison intuitive | ✅ | ✅ | — |
| GPS + timestamp built trust | ✅ | ✅ | — |
| Wanted confirmation dialog before disputing | ⚠️ | ⚠️ | Medium |
| Suggested specific dispute reasons | — | ⚠️ | Medium |
| Karma/trust points well-received | ✅ | ✅ | — |
| Karma system needs explanation | ⚠️ | ⚠️ | Medium |

**Insight:** The verification flow is strong, but there is no dispute flow. No confirmation dialog exists before disputing a fix, and no way to specify dispute reasons. This could lead to accidental disputes. Karma needs a brief explainer.

---

### Task 5: Browse Nearby Issues
| Finding | P1 | P2 | Severity |
|---------|----|----|----------|
| Map view intuitive | ✅ | ✅ | — |
| Color-coded pins understood | ✅ | ✅ | — |
| "Support This Report" feature well-received | ✅ | ✅ | — |
| Map clutter with many pins | — | ⚠️ | Medium |
| Wanted filters (by status, category) | — | ⚠️ | Medium |
| Suggested category-based pin shapes | — | ⚠️ | Low |

**Insight:** Map view works but needs filtering for scalability.

---

## 3. Cross-Participant Themes

### 3.1 What Worked Well (Keep As-Is)
1. **Phone + OTP Login** — Both participants found it quick and familiar
2. **Category Selection with Icons** — Visual + text combination was effective
3. **Progress Bar on Tracking** — The single most praised element
4. **Report ID System** — Made the process feel official and trackable
5. **Before/After Verification** — Intuitive and trust-building
6. **Karma/Trust Points** — Gamification was motivating, not childish
7. **Color-Coded Status Badges** — Traffic light metaphor universally understood
8. **Estimated Response Time** — Set clear expectations

### 3.2 What Needs Improvement (Changes Made)
1. **No Continue Button on Login Page** — After entering phone number, no visible Continue button. Users were stuck and thought the app was broken. (P1 & P2)
2. **Tracking Screen Too Dense** — Overwhelmed both participants. All information shown at once. Needed progressive disclosure (simple view + detailed view). (P1 & P2)
3. **Anonymous Reporting Toggle** — Too small and subtle. Easily missed. Needed to be more prominent — a full card with shield icon and clear label. (P2)
4. **Profile Photo Requirement Unclear** — Not marked as optional. Participants unsure whether photo was mandatory. (P2)
5. **Tag Editing — No Way to Remove** — AI auto-detected tags appeared as chips with no X/cross button. If AI misidentified an issue, users could not remove incorrect tags before submission. (P1)
6. **No Dispute Flow — No Confirmation, No Reason Selector** — No confirmation dialog before disputing a fix. No way to specify dispute reason (e.g., "Wrong location," "Temporary fix only"). (P1)
7. **Karma Explanation — Points Had No Context** — Users saw karma points but had no idea what they meant or what benefits they provided. Needed info icon and explanation linking trust to priority. (P2)
8. **Map Filters — No Way to Filter by Status/Category** — Map became cluttered with pins. No way to filter by status (open, in progress, resolved) or category (roads, streetlights, etc.). (P2)

---

## 4. Detailed Changes Made for Hi-Fi Prototype

### Change 1: Tracking Screen — Progressive Disclosure
**Problem:** Tracking screen showed all information at once (progress bar, delay notice, activity log, agency tasks, digital handshake). Both participants found it dense.

**Change:** Implemented a two-tier view:
- **Summary View (default):** Progress bar, current status, estimated completion date, delay notice (if any)
- **Detailed View (expandable):** Activity log, agency tasks, digital handshake steps, full audit trail
- Added a "Show Details" / "Hide Details" toggle

**Impact:** Reduces cognitive load for casual users while preserving depth for engaged users.

---

### Change 2: Replace Technical Jargon with Plain Language
**Problem:** "Stage-gates" and "Digital Handshake" were confusing to both participants.

**Change:**
- "Stage-gates" → "Progress Steps"
- "Digital Handshake" → "Field Worker Tasks"
- "Auto-sequenced" → "In Order"
- "Cross-Agency Hub" → "Department Coordination"
- "Verified Audit Trail" → "Activity History"

**Impact:** Makes the app accessible to non-technical users across all education levels.

---

### Change 3: Anonymous Reporting — Prominent Toggle
**Problem:** Anonymous reporting was a small text note at the bottom, easily missed.

**Change:**
- Moved to a visible toggle switch near the submit button
- Added icon (shield/mask) for visual recognition
- Added brief explanation: "Your name won't be visible to agencies"
- Default state: OFF (identified reporting)

**Impact:** Users who need anonymity will find it. Users who don't need it won't be confused.

---

### Change 4: Profile Setup — Clearer Labels
**Problem:** Photo requirement unclear, area input method ambiguous.

**Change:**
- Profile photo: Added "(Optional)" label and a skip link
- Area field: Changed to auto-detect from GPS with manual override dropdown
- Added helper text: "We'll use this to show you nearby issues"
- Added "Change phone number" link visibility

**Impact:** Reduces friction during onboarding. Users won't feel forced to upload a photo.

---

### Change 5: Tag Editing — Remove & Add Tags
**Problem:** Users could not remove AI-auto-detected tags because there was no X/cross button on tag chips. If the AI misidentified an issue, users had no way to remove incorrect tags, which could lead to reports being routed to the wrong department. Users also wanted the ability to add custom tags.

**Change:**
- Added X/cross button on each auto-detected tag chip so users can remove incorrect ones
- Added "+ Add Tag" button next to detected tags
- Opens a text input for custom tag entry
- Shows suggested tags based on category
- Custom tags appear as same-style chips with X buttons

**Impact:** Gives users full control over issue classification. Improves accuracy.

---

### Change 6: Dispute Flow — Confirmation + Reasons
**Problem:** No confirmation before disputing; no way to specify dispute reason.

**Change:**
- Added confirmation dialog: "Are you sure you want to dispute this repair?"
- Added dispute reason selector:
  - "Repair not completed"
  - "Wrong location"
  - "Temporary fix only"
  - "Other (please specify)"
- Added text field for additional details
- Reiterated: "A supervisor will review within 24 hours"

**Impact:** Reduces accidental disputes. Provides actionable feedback to supervisors.

---

### Change 7: Karma System — Explanation
**Problem:** Users liked karma points but didn't understand what they meant.

**Change:**
- Added info icon (ℹ️) next to karma/trust points
- Tooltip explains: "Trust points increase with verified reports and fix confirmations. Higher trust = faster response priority."
- Added a "Karma Levels" section in Profile:
  - 🌱 New Citizen (0-50 points)
  - 🏘️ Active Reporter (51-200 points)
  - 🏙️ Community Champion (201-500 points)
  - 🌟 Civic Leader (500+ points)

**Impact:** Makes the gamification system transparent and motivating.

---

### Change 8: Map View — Filters
**Problem:** Map becomes cluttered with many pins; no way to filter.

**Change:**
- Added filter bar at top of map:
  - Status filter: All / Open / In Progress / Resolved
  - Category filter: All / Roads / Streetlights / Garbage / Water / Other
  - Time filter: Today / This Week / This Month
- Added pin count badge: "23 issues near you"
- Different pin shapes for categories (circle = roads, triangle = streetlights, square = garbage)

**Impact:** Makes the map usable at scale. Users can focus on relevant issues.

---

## 5. Additional Improvements (Not from Testing but Identified)

### Change 9: Bottom Navigation — Clearer Labels
**Problem:** P2 used "Reports" tab naturally, but the prototype said "My Reports."

**Change:**
- Home → Home
- My Reports → Reports
- Map → Map
- Notifications → Alerts
- Profile → Profile

**Impact:** Shorter, cleaner labels fit better in bottom nav.

---

### Change 10: Phone Login — Continue Button
**Problem:** Both participants noted the absence of a visible Continue button after entering their phone number. Users were stuck and unsure how to proceed, thinking the app was broken.

**Change:**
- Added a prominent "Continue" button below the phone number input field
- Button activates only after a valid phone number is entered
- Clear visual affordance (blue, full-width, disabled state when empty)

**Impact:** Resolves a critical blocking issue. Users can now proceed through login without confusion.

---

### Change 11: Tag Editing — X/Close Button on AI Tags
**Problem:** Auto-detected AI tags appeared as chips with no X/cross button. Users could not remove incorrect tags, meaning reports could be routed to the wrong department.

**Change:**
- Added X/close button on each auto-detected tag chip
- Tapping X removes the tag and triggers re-routing confirmation
- Tags are now clearly editable (removable) before submission

**Impact:** Gives users control over AI-generated tags. Prevents misclassification of reports.

---

### Change 12: Profile — Edit Visibility
**Problem:** No visible "Edit Profile" button on the profile screen. Users didn't know how to modify their information.

**Change:**
- Added a prominent "Edit Profile" button near the top of the profile screen
- Added pencil icon next to editable fields (name, area, photo)
- Photo area now shows camera icon overlay on tap

**Impact:** Makes profile editing discoverable. Users can now update their information without confusion.

---

### Change 13: Notifications — Action Differentiation
**Problem:** All notifications looked similar. Users couldn't quickly distinguish between informational updates and action-required items (like verification requests).

**Change:**
- Added colored left-border to notification cards: blue for informational, orange for action-required
- Added small action icon (exclamation mark) for items needing user response
- Added "Action Needed" filter tab at top of Notifications screen
- Added swipe-to-dismiss gesture for individual notifications

**Impact:** Users can quickly identify which notifications need their attention. Reduces likelihood of missed verification requests.

---

### Change 10: Empty States
**Problem:** No empty state screens were shown in paper prototype.

**Change:** Added empty state designs for:
- No active reports: "No reports yet. Tap 'Report Issue' to get started!"
- No notifications: "You're all caught up! We'll notify you when your reports update."
- No nearby issues: "No issues reported nearby. You're in a great area!"

**Impact:** Prevents confusion when sections are empty. Encourages action.

---

## 6. SUS Score Comparison

| Participant | Score | Rating |
|-------------|-------|--------|
| P1 | 95 | Excellent |
| P2 | 80 | Good |
| **Average** | **87.5** | **Excellent** |

**Interpretation:** An average SUS of 87.5 places Civic Snap in the "Excellent" usability range (above 80.3 is considered A-grade). The gap between P1 (95) and P2 (80) suggests the app is more intuitive for tech-savvy users, which is expected for a paper prototype. The hi-fi version should narrow this gap with clearer visual hierarchy.

---

## 7. Priority Matrix for Changes

| Priority | Change | Effort | Impact |
|----------|--------|--------|--------|
| 🔴 Critical | Phone login Continue button | Low | Critical |
| 🔴 Critical | Tracking screen progressive disclosure | Medium | High |
| 🔴 Critical | Tag editing — X/cross button on AI tags | Low | High |
| 🔴 Critical | Dispute flow — confirmation + reason selector | Medium | High |
| 🟡 High | Anonymous reporting toggle — make prominent | Low | High |
| 🟡 High | Profile photo — mark as optional | Low | Medium |
| 🟡 High | Karma explanation — info icon + levels | Low | Medium |
| 🟡 High | Map filters — status and category filters | Medium | Medium |

---

## 8. Hi-Fi Testing — New Issues Found

All 8 issues from paper testing were resolved in the hi-fi prototype. P3 and P4 both confirmed the improvements. The following new issues emerged during hi-fi testing:

| # | Issue | Found By | Severity |
|---|-------|----------|----------|
| 1 | **Delete Profile and Data** — No option to delete account or remove personal data. Users expected GDPR-compliant data removal. | P3 | High |
| 2 | **Text too small for visibility** — Several areas (activity history timestamps, heatmap labels, notification detail text) had small text that was hard to read, especially for older users. | P4 | High |
| 3 | **Voice input option needed** — Users who can't type well (older users, those with motor impairments) need a voice/mic input option for descriptions. | P4 | Medium |
| 4 | **Privacy policy and legal aspects not accessible** — No link to privacy policy, terms of service, or data usage information anywhere in the app. Users wanted to know how their data is used. | P3 | Medium |

---

## 9. Next Steps

1. ✅ Implement all changes in hi-fi digital prototype
2. ✅ Test hi-fi prototype with 2+ new participants
3. ✅ Compare SUS scores between paper and hi-fi rounds
4. ✅ Validate that changes resolved identified issues
5. ✅ Document new issues found in hi-fi testing
6. ⏳ Implement hi-fi fixes (delete account, text scaling, voice input, privacy policy)
7. ⏳ Finalize prototype for submission

---

**Document Prepared By:** [Your Name]
**Date:** [Date]
**Version:** 1.0
