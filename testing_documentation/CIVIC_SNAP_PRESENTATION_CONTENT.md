# Civic Snap — Full Presentation Content Guide

**Version:** Complete Stage 4 Documentation
**Purpose:** Presentation script and slide content for UX design course submission
**Structure:** 5 sections as requested — Problem → Features → Taskflows → Paper Testing → Digital Testing

---

# SECTION 1 — PROBLEM STATEMENTS
## (~1 slide)

### The Problem

**Title:** Why Civic Snap Exists

**Content:**

**Problem 1 — Prioritization: "Urgency is defined by political pressure or social media noise, not actual safety risk"**

- Currently, which civic issues get fixed fastest depends on who complains loudest or who has political connections
- Real hazards affecting vulnerable communities get ignored because no one tweets about them
- The system rewards noise, not need

**Problem 2 — Credibility: "Administrative closure takes precedence over high-quality, durable repairs"**

- Issues are marked "resolved" without actual citizen verification
- Field workers close tickets without proof of durable repair
- No accountability for whether the fix actually lasted

**Problem 3 — Departmental Disconnect: "Tickets bounce indefinitely during jurisdictional disputes"**

- BBMP vs. BWSSB finger-pointing leaves citizens stuck in the middle
- No clear ownership when an issue spans multiple agencies
- Reports get passed around for weeks without action

**Problem 4 — Follow-up Fatigue: "Citizens are forced to repeatedly chase officials, hearing only 'Work in progress'"**

- Zero transparency — citizens have no idea if their report is being acted on
- No feedback loop, no ETA, no progress visibility
- Most citizens give up after one or two attempts

---

# SECTION 2 — FEATURES & FUNCTIONS DECIDED
## (~1-2 slides, concise)

### The Solution: Civic Snap Platform

The platform has three connected interfaces — one for each user type.

**Citizen App (Empowerment)**

- No-Guess UI: AI handles complex departmental routing automatically from a single photo
- Live Tracking: Real-time stage-gate alerts replace the need for constant follow-up calls
- Honest Delays: Transparent, automated explanations sent when service deadlines are missed
- Anonymous Reporting: Toggle to report without revealing identity
- Karma Gamification: Trust points earned through verified participation

**AI Backend (The Brain)**

- Master Tickets: Splits a single complex incident into synchronized sub-tasks for multiple agencies
- Smart Clustering: Merges duplicate reports from the same 50m radius to prevent redundant crew dispatch
- Risk Engine: Scores hazard urgency using objective city traffic and transit data, ignoring social media "noise"

**Government Portal (Accountability)**

- Hazard Heatmaps: Dashboards visualize true community exposure for intelligent resource planning
- Smooth Handoffs: Cross-agency communication tools eliminate multi-department "bounce"
- Verified Audits: Mandatory digital GPS stamps and citizen sign-offs ensure high-quality, durable repairs

---

# SECTION 3 — TASKFLOWS
## (~2-3 slides, concise)

### Citizen Flows (tested in both rounds)

| Flow | Steps |
|------|-------|
| **Account Creation** | Landing → Phone Number → OTP → Profile Setup → Home |
| **Report Issue** | Report Issue → Category → Photo → Tags → Description → Location → Review → Submit → Confirmation |
| **Track Status** | Home → Reports → Select Report → Tracking View (Simple/Detailed) |
| **Verify Fix** | Notification → Before/After Photos → Confirm or Dispute → Karma Awarded |
| **Browse Nearby** | Map View → Filter Pins → View Public Report → Support |

### Field Worker Flows (documented in prototype)

| Flow | Steps |
|------|-------|
| **Task Handling** | Task Queue → Select Task → View Details → Upload Before Photo → Perform Work → Upload After Photo → Mark Complete → GPS Confirmation |

### Government Office Flows (documented in prototype)

| Flow | Steps |
|------|-------|
| **Manual Ticket Creation** | Dashboard → Create Ticket → Fill Details → Submit |
| **Assign Ticket** | Incoming Reports → Review → Assign to Field Worker |
| **Report View** | All Reports → Filter/Search → View Details → Status Update |

---

# SECTION 4 — PAPER PROTOTYPE TESTING FINDINGS & CHANGES
## (~4-5 slides, detailed with image placeholders)

---

## Slide 4A — Paper Prototype Overview

**Title:** Our Paper Prototype — 36 Screens, 3 User Ecosystems

**Content:**

**Paper Prototype Scope:**

- 36 screens covering complete user ecosystem
- Citizen flows: Login, Report, Track, Verify, Browse, Profile
- Field Worker flows: Task queue, GPS closeout, Digital handshake
- Government flows: Heatmap dashboard, Triage & assignment, Analytics
- Edge cases: Offline mode, Error states, Duplicate clusters, Escalation

**Image Placeholder — 2×2 Grid of Paper Screens:**

- **Top-Left:** Landing Page — "[INSERT IMAGE: Paper prototype landing page screen]"
- **Top-Right:** Home Dashboard — "[INSERT IMAGE: Paper prototype home dashboard screen]"
- **Bottom-Left:** Report Hazard — "[INSERT IMAGE: Paper prototype report hazard screen]"
- **Bottom-Right:** Field Worker Task Queue — "[INSERT IMAGE: Paper prototype field worker task queue screen]"

---

## Slide 4B — Paper Testing Methodology

**Title:** How We Tested — Paper Prototype Round

**Content:**

**Study Design:**

- 2 participants (P1: 25-34, tech-savvy | P2: 35-44, moderate tech comfort)
- Think-aloud protocol with task-based evaluation
- 5 core tasks tested: Account creation, Report issue, Track status, Verify fix, Browse nearby
- Metrics: Task completion rate, Time-on-task, Error rate
- Session structure: Pre-interview (5 min) → Tasks (20 min) → Post-interview (15 min)

**Image Placeholder — Methodology Flowchart:**
"[INSERT IMAGE: Simple flowchart — Paper Testing → Learnings → Design Changes → Hi-Fi Testing → Final Prototype]"

---

## Slide 4C — Paper Testing: Key Findings

**Title:** Paper Prototype Results — What Worked and What Didn't

**Content:**

**What Worked (Keep As-Is):**

- ✅ Phone + OTP login — both participants found it quick and familiar
- ✅ Category selection with icons — visual + text combination was effective
- ✅ Progress bar on tracking — single most praised element across both participants
- ✅ Report ID system — made the process feel official and trackable
- ✅ Before/after verification — intuitive and trust-building
- ✅ Karma/trust points — gamification was motivating, not childish
- ✅ Color-coded status badges — traffic light metaphor universally understood

**What Needed Fixing:**

- ❌ Tracking screen too dense — all info shown at once overwhelmed both participants
- ❌ Technical jargon — "Stage-gates" and "Digital Handshake" confused both
- ❌ Anonymous reporting toggle — nearly invisible, small text note at bottom
- ❌ Profile setup — photo requirement unclear, area input ambiguous
- ❌ Tag editing — could remove AI tags but not add custom ones
- ❌ Dispute flow — no confirmation before disputing, no reason selector
- ❌ Karma explanation — points system had no context
- ❌ Map filters — no way to filter by status or category

**Image Placeholder — Paper Tracking Screen with Callout:**
"[INSERT IMAGE: Paper prototype tracking screen (Artboard DT-0) with RED CALLOUT ARROW pointing to the dense information area labeled: "Too much information at once — both participants felt overwhelmed"]"

---

## Slide 4D — Changes Made: Paper → Hi-Fi

**Title:** 10 Design Changes Based on Paper Testing Feedback

**Content:**

| Issue (Paper) | Change Made (Hi-Fi) |
|--------------|---------------------|
| Tracking screen: all info at once | → Simple view + expandable "Show Details" toggle |
| "Stage-gates" terminology | → "Progress Steps" |
| "Digital Handshake" terminology | → "Field Worker Tasks" |
| Anonymous toggle: small text note | → Prominent toggle card with shield icon |
| Profile photo: unclear if required | → Clearly marked "(Optional)" + skip link |
| Area input: ambiguous method | → Auto-detected from GPS + tap to change |
| Tag editing: remove only | → Remove + Add custom tags with "+" button |
| Dispute: direct action | → Confirmation dialog + reason selector |
| Karma: no explanation | → Levels explained + info tooltip |
| Map: no filters | → Status, Category, Time filters added |

**Image Placeholder — Before/After Comparison (select one):**
"[INSERT IMAGE: Side-by-side of paper tracking screen (left) vs hi-fi simple tracking view (right) showing the progressive disclosure improvement]"

OR show the terminology changes:
"[INSERT IMAGE: Close-up of hi-fi tracking screen showing "Progress Steps" label replacing "Stage-gates"]"

---

## Slide 4E — Paper Testing: Selected Participant Quotes

**Title:** What Participants Said (Paper Testing)

**Content:**

**On Transparency:**
> "This is exactly what I wanted — transparency. I can see exactly where my report is." — P1

**On the Karma System:**
> "It's like a credit score for being a good citizen." — P2
> "The karma system is clever. And the transparency in tracking is exactly what's missing from current systems." — P1

**On the Tracking Screen:**
> "Not overwhelming, but dense. I'm someone who likes to see everything, so I'd scroll through it all. But my wife, who's less tech-savvy, might find it confusing." — P2

**On the Biggest Concern:**
> "The app design is good, but the real test is whether it leads to action." — P2

---

# SECTION 5 — DIGITAL (HI-FI) PROTOTYPE TESTING FINDINGS & CHANGES
## (~5-6 slides, most detailed section)

---

## Slide 5A — Hi-Fi Prototype Overview

**Title:** Hi-Fi Digital Prototype — After Changes

**Content:**

**What Changed in Hi-Fi:**

All 10 paper testing issues were addressed in the hi-fi digital prototype:

1. Progressive disclosure on tracking (simple view / detailed view)
2. Plain language terminology throughout
3. Prominent anonymous reporting toggle card
4. Optional profile photo with clear labeling
5. Auto-detected area with GPS
6. Add custom tags functionality
7. Dispute confirmation with reason selector
8. Karma system with level explanations
9. Map filters (status, category, time)
10. Cleaner bottom navigation labels

**Image Placeholder — Hi-Fi Screens Strip (4 across):**
"[INSERT IMAGE: Hi-Fi Landing Page (Artboard 3F0-0)]"
"[INSERT IMAGE: Hi-Fi Phone Login (Artboard 3FW-0)]"
"[INSERT IMAGE: Hi-Fi OTP (Artboard 3FX-0)]"
"[INSERT IMAGE: Hi-Fi Profile Setup (Artboard 3FY-0)]"

---

## Slide 5B — Hi-Fi Testing Methodology

**Title:** How We Tested — Digital Hi-Fi Round

**Content:**

**Study Design:**

- 2 participants (P3: 18-24, very tech-savvy | P4: 45-54, moderate tech comfort)
- Same think-aloud protocol, same task set as paper round
- Same metrics tracked for direct comparison
- Same session structure (Pre → Tasks → Post)

**Key Difference from Paper Round:**
The same tasks were repeated with the improved hi-fi prototype to measure whether design changes resolved the identified issues.

**Image Placeholder — Methodology Comparison:**
"[INSERT IMAGE: Simple comparison graphic — Paper Round: P1+P2 → Hi-Fi Round: P3+P4, showing same methodology used for both rounds]"

---

## Slide 5C — Hi-Fi Testing: Key Findings

**Title:** Hi-Fi Prototype Results — All Issues Resolved

**Content:**

**Every Paper Issue Was Resolved:**

| Paper Issue | Hi-Fi Result |
|------------|-------------|
| Tracking screen dense | ✅ P3: "Night and day. The paper version was overwhelming." |
| "Stage-gates" confusing | ✅ Both participants used "Progress Steps" without confusion |
| "Digital Handshake" confusing | ✅ P4 called it "Field Worker Tasks" — no confusion |
| Anonymous toggle hidden | ✅ P3: "In the paper version it was tiny text at the bottom. This is way better." |
| Profile photo unclear | ✅ P4: "Optional" clearly marked |
| Can't add custom tags | ✅ P3 noticed and praised the "+ Add Tag" button |
| Karma no explanation | ✅ P4: "Higher trust means faster priority. So it's not just a game — it actually helps me." |
| Map no filters | ✅ Both participants used filters on map |

**Task Completion: 100%** (All participants completed all 8 tasks without help)

**Image Placeholder — Before/After Comparison:**
"[INSERT IMAGE: Comparison showing improvements from paper to hi-fi — can use side-by-side screenshots of tracking screen, anonymous toggle, or category selection]"

---

## Slide 5D — Hi-Fi: Progressive Disclosure (Key Change)

**Title:** Biggest Improvement: Progressive Disclosure on Tracking

**Content:**

**The Paper Problem:**
Both P1 and P2 found the paper tracking screen overwhelming — all information shown at once (progress bar, delay notice, activity log, agency tasks, digital handshake steps).

**The Hi-Fi Solution:**
Two-tier view:

- **Simple View (default):** Progress steps + current status + delay notice + estimated completion
- **Detailed View (tap "Show Details"):** Activity history timeline + field worker task checklist

**Participant Reactions:**

> "Night and day. The paper version was overwhelming." — P3

> "Having both options is good — some people want details, some don't." — P4

> "If I just wanted a quick check, I could stay on the simple view. Having both options is good." — P4

> "The simple view is what I'd use most often." — P4

**Image Placeholder — Side-by-Side Tracking Comparison:**
"[INSERT IMAGE LEFT: Hi-Fi Simple Tracking View (Artboard 3T0-0) — showing progress steps, delay notice, and "Show Details" button]"
"[INSERT IMAGE RIGHT: Hi-Fi Detailed Tracking View (Artboard 3T1-0) — showing expanded activity history and field worker tasks]"
"[ANNOTATION: Arrow between them labeled "Tap Show Details →"]"

---

## Slide 5E — Hi-Fi: Terminology & Clarity Improvements

**Title:** Plain Language Changes — Before and After

**Content:**

**Terminology Changes:**

| Paper Prototype (Confusing) | Hi-Fi Prototype (Clear) |
|----------------------------|------------------------|
| Stage-gates | Progress Steps |
| Digital Handshake | Field Worker Tasks |
| Auto-sequenced | In Order |
| Cross-Agency Hub | Department Coordination |
| Verified Audit Trail | Activity History |

**Participant Confirmation:**

> "'Progress Steps' — not 'Stage-gates' anymore, right? That's much clearer." — P3

> "The terminology is also much better — 'Progress Steps' instead of 'Stage-gates,' 'Field Worker Tasks' instead of 'Digital Handshake.'" — P3

> "I see 'Progress Steps' at the top — what does that mean? I had to read the context to understand." — P2 (Paper)

**Image Placeholder — Terminology Close-up:**
"[INSERT IMAGE: Hi-Fi tracking screen close-up showing "Progress Steps" label and "Field Worker Tasks" section]"

---

## Slide 5F — Hi-Fi: Anonymous Toggle Improvement

**Title:** Anonymous Reporting — From Hidden to Prominent

**Content:**

**Paper Problem:**
P1: "I almost missed that — it's quite small."
P2: "Maybe a toggle switch instead of small text."

**Hi-Fi Solution:**
- Full card with shield icon
- Title: "Report Anonymously"
- Description: "Your name won't be visible to agencies"
- Actual toggle switch (not small text)
- Positioned prominently near the Submit button

**Participant Reaction:**
> "Anonymous Reporting toggle is now prominent — it's a full card with a shield icon, title, description, and an actual toggle switch. In the paper version it was tiny text at the bottom. This is way better." — P3

**Image Placeholder — Anonymous Toggle:**
"[INSERT IMAGE LEFT: Paper prototype — tiny text note at bottom of report form]"
"[INSERT IMAGE RIGHT: Hi-Fi prototype — prominent anonymous reporting card with shield icon and toggle switch]"
"[ANNOTATION: "Before → After" comparison]"

---

## Slide 5G — Hi-Fi: Karma System Explained

**Title:** Karma Gamification — Now With Context

**Content:**

**Paper Problem:**
Both participants liked karma points but didn't understand what they meant or what benefits they provided.

> "I'd want to know what the points mean. Can I redeem them? Do they give me any status? Or is it just for show?" — P2

**Hi-Fi Solution:**

- Karma badge visible in header (142 points, star icon)
- Info icon (ℹ️) next to karma with tooltip explanation
- Four levels with descriptions:
  - 🌱 New Citizen (0-50 points)
  - 🏘️ Active Reporter (51-200 points)
  - 🏙️ Community Champion (201-500 points)
  - 🌟 Civic Leader (500+ points)
- Explanation: "Trust points increase with verified reports and fix confirmations. Higher trust = faster response priority."

**Participant Reactions:**

> "142 points. I'm curious what that means. I'd tap it later to understand." — P3

> "It explains that points increase when I report issues and verify fixes. Higher trust means faster response priority. So it's not just a game — it actually helps me get better service." — P4

> "It's a small thing but it makes civic participation feel rewarding." — P2

**Image Placeholder — Karma Profile Section:**
"[INSERT IMAGE: Hi-Fi Profile screen showing karma section with 142 points, "Active Reporter" level, and info icon tooltip visible or partially shown]"
"[ANNOTATION: Highlight the info icon and level badges]"

---

## Slide 5H — Hi-Fi: Accessibility Wins

**Title:** Visual Design is Accessibility — What We Learned

**Content:**

**Key Finding:**
P4 (age 45-54, less tech-savvy) found the hi-fi version significantly easier to use than the paper version, confirming that visual design improvements particularly benefit users who need more clarity.

**Specific Accessibility Improvements Valued by P4:**

> "The text is a good size — I don't need my reading glasses for this." — P4

> "Much better than most apps. I don't need my reading glasses for this." — P4

> "The pictures make it much easier. I don't have to read every word." — P4 (on category icons)

**Design Choices That Helped:**

- Large, readable text (16px minimum body text)
- Category cards with colored icons (not just text)
- Color-coded status badges (green/yellow/red = traffic light metaphor)
- Big, clearly labeled buttons
- Progress indicator at top of each step in report flow

**Image Placeholder — Category Selection Comparison:**
"[INSERT IMAGE LEFT: Paper prototype category screen — text labels only]"
"[INSERT IMAGE RIGHT: Hi-Fi prototype category grid — icon cards with colored icons]"
"[ANNOTATION: "Icons help users who can't or won't read every word" — P4]"

---

## Slide 5I — Hi-Fi: Participant Quotes

**Title:** What Participants Said (Hi-Fi Testing)

**Content:**

**On Overall Impression:**
> "This looks really polished. Dark theme with the gradient — very modern." — P3

> "If this works in real life, it would be the most useful civic app in India. The design is on par with any startup app." — P3

> "This is the best-designed government-related app I've seen." — P4

> "I'd especially recommend it to other older people because the text is readable and the buttons are big. Most government apps are not designed for people my age." — P4

**On the Tracking Improvement:**
> "Night and day. The paper version was overwhelming." — P3

> "Having both options is good — some people want details, some don't." — P4

**On Transparency:**
> "That's honest. I appreciate that they tell me instead of just going silent." — P4 (on delay notice)

---

# SECTION 6 — SUMMARY & KEY LEARNINGS
## (~1-2 slides)

---

## Slide 6A — The Complete Improvement Story

**Title:** From Paper to Hi-Fi — The Full Picture

**Content:**

**What Improved Between Rounds:**

- Both participants completed all tasks in the hi-fi round without any guidance
- Every issue identified in paper testing was resolved in hi-fi
- P4 (older, less tech-savvy) particularly benefited from the design improvements
- The gap between tech-savvy and moderate users narrowed significantly

**Key Insight:**
Good design isn't just about aesthetics — it's about access. Every improvement we made (larger text, clearer labels, progressive disclosure, plain language) disproportionately helped the user who needed more support.

**What This Means:**
Testing across diverse age groups revealed that clarity and visual hierarchy are accessibility features, not just preferences.

---

## Slide 6B — 6 Design Principles We Learned

**Title:** Key Learnings

**Content:**

**1. Progressive Disclosure Beats Information Density**
Users want control over how much detail they see. A simple default view + optional detailed view serves everyone.

**2. Plain Language Matters**
Technical jargon creates barriers even for tech-savvy users. "Progress Steps" beats "Stage-gates" every time.

**3. Visual Design IS Accessibility**
Large text, clear hierarchy, and icon-based navigation help everyone — especially users who are older, less literate, or less tech-savvy.

**4. Trust is Built Through Transparency**
Report IDs, ETAs, delay notices, and activity logs create confidence that the system is real and accountable.

**5. Gamification Works When Meaningful**
Karma points tied to real benefits (faster priority) motivate engagement. Decorative points feel hollow.

**6. Test with Diverse Ages**
Younger users want speed; older users want clarity. Testing across age ranges reveals needs you'd never predict.

---

# IMAGE PLACEHOLDER REFERENCE

## Where to Insert Screenshots

| Slide | Image Description | File to Use |
|-------|------------------|-------------|
| 4A | Paper 2×2 grid — Landing, Home, Report, FW Queue | Paper MCP screenshots |
| 4B | Methodology flowchart | [Create in presentation tool] |
| 4C | Paper tracking screen with dense info callout | Paper DT-0 |
| 4D | Before/after tracking comparison | Paper DT-0 vs Hi-Fi 3T0-0 |
| 4E | Quote slide — no images needed | — |
| 5A | Hi-Fi 4-screen strip — Landing, Login, OTP, Profile | Hi-Fi 3F0-0, 3FW-0, 3FX-0, 3FY-0 |
| 5B | Methodology comparison | [Create in presentation tool] |
| 5C | Before/after comparison | Any paper vs hi-fi screenshot pair |
| 5D | Simple vs Detailed tracking side-by-side | Hi-Fi 3T0-0 and 3T1-0 |
| 5E | Progress Steps label close-up | Hi-Fi 3T0-0 |
| 5F | Anonymous toggle — before vs after | Paper report form vs Hi-Fi 3N2-0 |
| 5G | Karma profile section | Hi-Fi Profile screen |
| 5H | Category icons — paper vs hi-fi | Paper category screen vs Hi-Fi 3N0-0 |
| 5I | Quote slide — no images needed | — |

---

# PRESENTATION SLIDE COUNT RECOMMENDATION

| Section | Slides | Time |
|---------|--------|------|
| 1. Problem Statements | 1 | ~1 min |
| 2. Features & Functions | 1-2 | ~1 min |
| 3. Taskflows | 1-2 | ~1 min |
| 4. Paper Testing Findings | 4-5 | ~5-6 min |
| 5. Hi-Fi Testing Findings | 8-9 | ~8-10 min |
| 6. Summary & Learnings | 2 | ~2 min |
| **Total** | **17-21 slides** | **~18-22 minutes** |

**Time Allocation:**
- Sections 1-3 (Problem → Features → Taskflows): ~3 minutes (concise, background)
- Section 4 (Paper Testing): ~5-6 minutes (builds narrative to why changes were made)
- Section 5 (Hi-Fi Testing): ~8-10 minutes (the main event — where changes are validated)
- Section 6 (Summary): ~2 minutes (wrap up)

---

*Document prepared for UX Design course presentation. All participant quotes are from recorded think-aloud sessions. Images to be inserted manually at indicated placeholder positions.*
