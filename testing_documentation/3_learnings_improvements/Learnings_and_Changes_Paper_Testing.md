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
| Wanted ability to ADD custom tags | ⚠️ | ⚠️ | Medium |
| GPS location step clear | ✅ | ✅ | — |
| Map pin adjustment appreciated | ✅ | ✅ | — |
| Anonymous reporting toggle too small | ⚠️ | ⚠️ | High |
| Report ID and ETA built confidence | ✅ | ✅ | — |
| Flow felt slightly long but acceptable | ⚠️ | ✅ | Low |

**Insight:** The reporting flow is the strongest part of the prototype. The anonymous reporting toggle needs to be more prominent. Tag editing needs an "add" option.

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

**Insight:** The verification flow is strong. Adding a confirmation dialog and dispute reason selector would improve it. Karma needs a brief explainer.

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
1. **Tracking Screen Density** — Both participants found it overwhelming
2. **Technical Jargon** — "Stage-gates," "Digital Handshake" confused both
3. **Anonymous Reporting Visibility** — Too small, easily missed
4. **Profile Setup Clarity** — Photo requirement and area input ambiguous
5. **Tag Editing** — Could remove but not add custom tags
6. **Dispute Flow** — Needed confirmation dialog and reason selector
7. **Karma Explanation** — Points system needed context
8. **Map Filters** — Needed for scalability

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

### Change 5: Tag Editing — Add Custom Tags
**Problem:** Users could remove AI-detected tags but not add their own.

**Change:**
- Added "+ Add Tag" button next to detected tags
- Opens a text input for custom tag entry
- Shows suggested tags based on category
- Custom tags appear as same-style chips

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
| 🔴 Critical | Tracking screen progressive disclosure | Medium | High |
| 🔴 Critical | Replace technical jargon | Low | High |
| 🟡 High | Anonymous reporting toggle | Low | High |
| 🟡 High | Profile setup clarity | Low | Medium |
| 🟡 High | Dispute confirmation + reasons | Medium | Medium |
| 🟢 Medium | Add custom tags | Medium | Medium |
| 🟢 Medium | Karma explanation | Low | Medium |
| 🟢 Medium | Map filters | Medium | Medium |
| 🔵 Low | Pin shape differentiation | Low | Low |
| 🔵 Low | Empty states | Low | Medium |

---

## 8. Next Steps

1. ✅ Implement all changes in hi-fi digital prototype
2. ✅ Test hi-fi prototype with 2+ new participants
3. ⏳ Compare SUS scores between paper and hi-fi rounds
4. ⏳ Validate that changes resolved identified issues
5. ⏳ Document any new issues found in hi-fi testing
6. ⏳ Finalize prototype for submission

---

**Document Prepared By:** [Your Name]
**Date:** [Date]
**Version:** 1.0
