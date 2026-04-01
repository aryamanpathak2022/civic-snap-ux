# Civic Snap — Stage 4: Test + Hi-Fi Prototype
## Presentation Content (Slide-by-Slide)

**Instructions for PPT Agent:**
- This is a 16-slide presentation
- Each slide has: Title, Slide Content (bullet points/text), Image Placement instructions, and Speaker Notes
- All images should be screenshots from the Paper MCP prototype (artboard IDs provided)
- Use a clean, modern design with the Civic Snap brand colors: Primary Blue (#3B82F6), Green (#10B981), Dark (#0F172A), Light Gray (#F8FAFC)
- Font: Inter or similar sans-serif
- Keep slides visually clean — don't overcrowd with text

---

## SLIDE 1 — Title Slide

**Title:** Civic Snap
**Subtitle:** Stage 4 — Test + Hi-Fi Prototype
**Bottom text:** User Experience Design | Group [Insert Number] | [Date]

**Image Placement:** None — use a full-bleed dark background (#0F172A) with the Civic Snap logo/icon centered (the blue-green gradient pin icon from the landing page).

**Speaker Notes:**
Good [morning/afternoon]. Today we're presenting Stage 4 of our Civic Snap project — the testing and high-fidelity prototyping phase. Civic Snap is a civic issue reporting and management platform connecting citizens, field workers, and government officials.

---

## SLIDE 2 — Project Overview

**Title:** What is Civic Snap?

**Slide Content:**
- A mobile platform for reporting, tracking, and resolving civic infrastructure issues
- Three user roles: Citizens, Field Workers, Government Officials
- Core flow: Report → Auto-Route → Track → Verify → Earn Trust
- Key features: AI auto-tagging, real-time tracking, anonymous reporting, karma gamification, multi-channel support (app, WhatsApp, SMS)

**Image Placement:** Right side — Screenshot of Home Dashboard (Artboard: 3FZ-0 — Hi-Fi Home Dashboard). Show the quick action cards and active reports section.

**Speaker Notes:**
Civic Snap solves a fundamental problem: citizens report civic issues but never know what happens next. Our platform closes that loop. A citizen reports an issue — like a pothole or broken streetlight — the system auto-routes it to the correct department, assigns a field worker, tracks progress in real-time, and requires citizen verification before closing the ticket. It serves three roles: citizens who report, field workers who fix, and government officials who manage.

---

## SLIDE 3 — Our Paper Prototypes

**Title:** Paper Prototype Overview

**Slide Content:**
- 36 screens covering all user flows
- Citizen flows: Login, Report, Track, Verify, Browse, Profile
- Field Worker flows: Task queue, GPS closeout, Digital handshake
- Government flows: Heatmap dashboard, Triage & assignment, Analytics
- Edge cases: Offline mode, Error states, Duplicate clusters, Escalation

**Image Placement:** Create a 2x2 grid of paper prototype screenshots showing variety:
- Top-left: Landing Page (Artboard: 1N4-0)
- Top-right: Home Dashboard (Artboard: 1C9-0)
- Bottom-left: Report Hazard (Artboard: DS-0)
- Bottom-right: Field Worker Task Queue (Artboard: 1VI-0)

**Speaker Notes:**
We started with 36 paper prototype screens covering the complete ecosystem. Citizen flows include onboarding, reporting, tracking, and verification. Field worker flows cover task management and GPS-verified closeouts. Government flows include heatmaps, ticket assignment, and analytics. We also designed for edge cases like offline mode, error states, and duplicate report clustering.

---

## SLIDE 4 — Study Protocol

**Title:** Testing Methodology

**Slide Content:**
- Two rounds: Paper prototype (low-fi) → Hi-fi digital prototype
- Participants: 2 per round (4 total), diverse age ranges
- Method: Think-aloud protocol with task-based evaluation
- Metrics tracked: Task completion rate, time-on-task, error rate, SUS score
- 5 core tasks: Account creation, Report issue, Track status, Verify fix, Browse nearby
- Session structure: Pre-interview (5 min) → Tasks (20 min) → Post-interview + SUS (15 min)

**Image Placement:** Left side — A simple flowchart graphic showing: Paper Testing → Learnings → Design Changes → Hi-Fi Testing → Final Prototype. Use icons for each step.

**Speaker Notes:**
Our testing followed a rigorous two-round methodology. First, we tested paper prototypes with two participants using a think-aloud protocol. We captured every hesitation, confusion, and insight. Then we incorporated all findings into a hi-fi digital prototype and tested again with two new participants. We tracked task completion rates, time-on-task, error rates, and System Usability Scale scores throughout.

---

## SLIDE 5 — Paper Testing: Key Findings

**Title:** Paper Prototype Testing Results

**Slide Content:**
- P1 (25-34, tech-savvy): SUS = 95/100
- P2 (35-44, moderate): SUS = 80/100
- Average SUS: 87.5/100 (Excellent range)
- What worked: Progress bar, report ID, before/after verification, karma system
- What needed fixing: Tracking screen too dense, technical jargon, anonymous toggle hidden, profile setup unclear

**Image Placement:** Right side — Screenshot of the paper prototype Live Tracking screen (Artboard: DT-0) with a red callout box highlighting the information density issue.

**Speaker Notes:**
Paper testing revealed strong fundamentals but clear improvement areas. Both participants loved the progress tracking bar, report ID system, and karma gamification. But the tracking screen was overwhelming — too much information at once. Terms like Stage-gates and Digital Handshake confused both users. The anonymous reporting toggle was nearly invisible. And the profile setup form had ambiguous fields. Average SUS of 87.5 is excellent, but there was clear room for improvement.

---

## SLIDE 6 — Changes Made (Paper → Hi-Fi)

**Title:** Design Improvements Based on Testing

**Slide Content:**

Tracking screen: All info at once → Simple view + expandable details
Terminology: "Stage-gates" → "Progress Steps"
Terminology: "Digital Handshake" → "Field Worker Tasks"
Anonymous toggle: Small text note → Prominent toggle card with icon
Profile photo: Unclear requirement → Clearly marked "Optional"
Area input: Ambiguous → Auto-detected + tap to change
Tag editing: Remove only → Remove + Add custom tags
Dispute flow: Direct action → Confirmation dialog + reason selector
Karma system: No explanation → Levels + info tooltip
Map view: No filters → Status, category, time filters

**Image Placement:** None needed — this is a comparison table slide. Use alternating row colors for readability.

**Speaker Notes:**
We made 10 specific changes based on paper testing feedback. The biggest was the tracking screen — we split it into a simple summary view and an expandable detailed view. We replaced all technical jargon with plain language. The anonymous reporting toggle went from invisible text to a prominent card with a shield icon. We added the ability to add custom tags, not just remove them. And we added a confirmation dialog before disputing a repair.

---

## SLIDE 7 — Hi-Fi Prototype: Onboarding

**Title:** Hi-Fi Prototype — Onboarding Flow

**Slide Content:**
- Landing Page: Clean dark theme, feature highlights, clear CTA
- Phone Login: +91 pre-filled, simple input
- OTP Verification: 6-box input, timer, resend option
- Profile Setup: Optional photo, auto-detected area, clear helper text

**Image Placement:** Horizontal strip of 4 screenshots across the slide (left to right):
1. Landing Page (Artboard: 3F0-0)
2. Phone Login (Artboard: 3FW-0)
3. OTP Verification (Artboard: 3FX-0)
4. Profile Setup (Artboard: 3FY-0)

**Speaker Notes:**
The hi-fi onboarding flow is four screens: a polished landing page with feature highlights, phone number entry with pre-filled country code, OTP verification with a timer, and profile setup with auto-detected location and optional photo. Each screen has clear visual hierarchy and progress indicators. The entire flow takes about 30 seconds.

---

## SLIDE 8 — Hi-Fi Prototype: Report Issue

**Title:** Hi-Fi Prototype — Report Issue Flow

**Slide Content:**
- Step 1: Category selection with icon grid + search
- Step 2: Photo upload, AI auto-tags with add/remove, description, GPS location
- Step 3: Review summary, auto-routing info, prominent anonymous toggle
- Confirmation: Report ID, status, department, ETA, track button

**Image Placement:** 2x2 grid of screenshots:
- Top-left: Category Selection (Artboard: 3N0-0)
- Top-right: Photo & Tags with "Add Tag" button (Artboard: 3N1-0)
- Bottom-left: Review & Submit with anonymous toggle (Artboard: 3N2-0)
- Bottom-right: Submission Confirmation (Artboard: 3XO-0)

**Speaker Notes:**
The report flow is three steps plus confirmation. Step one: choose a category from an icon grid — much more scannable than text-only. Step two: take a photo, review AI-detected tags, add custom tags, write details, and confirm location. Step three: review everything, see which department it's routed to, and choose anonymous or identified reporting. The confirmation screen gives you a report ID, status, and estimated response time.

---

## SLIDE 9 — Hi-Fi Prototype: Tracking

**Title:** Hi-Fi Prototype — Report Tracking

**Slide Content:**
- Simple View: Progress steps, status, delay notice, estimated completion
- Detailed View: Activity history timeline, field worker task checklist
- Plain language: "Progress Steps" not "Stage-gates"
- Progressive disclosure: Users choose their level of detail

**Image Placement:** Side-by-side comparison:
- Left: Simple View (Artboard: 3T0-0)
- Right: Detailed View (Artboard: 3T1-0)
Add an arrow between them labeled "Show Details →"

**Speaker Notes:**
This was our biggest improvement. The simple view shows exactly what most users need: a progress timeline, current status, any delay notices, and estimated completion. Tap Show Details to expand into activity history and field worker tasks. This progressive design serves both casual users who want a quick check and engaged users who want full transparency.

---

## SLIDE 10 — Hi-Fi Prototype: Verify Fix

**Title:** Hi-Fi Prototype — Verify & Dispute

**Slide Content:**
- Before/After comparison: Side-by-side photos with GPS verification
- Confirm Fix: One-tap confirmation, karma points awarded
- Dispute Flow: Confirmation dialog → Select reason → Add details → Supervisor review within 24 hours
- Dispute reasons: "Repair not completed", "Wrong location", "Temporary fix", "Other"

**Image Placement:** Left side — Verify Fix screen (Artboard: 3XN-0). Right side — A callout box showing the dispute reason selector as a mini mockup (can be drawn as a simple list with radio buttons).

**Speaker Notes:**
The verification flow lets citizens confirm or dispute a repair. Before and after photos are shown side-by-side with GPS and timestamp verification for trust. If you confirm, you earn karma points. If you dispute, you get a confirmation dialog and can select a reason — wrong location, incomplete repair, temporary fix, or other. This triggers a supervisor review within 24 hours.

---

## SLIDE 11 — Hi-Fi Testing Results

**Title:** Hi-Fi Digital Prototype Testing Results

**Slide Content:**
- P3 (18-24, very tech-savvy): SUS = 100/100
- P4 (45-54, moderate): SUS = 87.5/100
- Average SUS: 93.75/100 (Excellent — improved from 87.5)
- Task completion: 100% (8/8 tasks across both participants)
- Key feedback: "Night and day improvement", "Best-designed government app", "Text is readable"

**Image Placement:** Right side — A bar chart comparing SUS scores:
- Paper P1: 95, Paper P2: 80 → Avg 87.5
- Hi-Fi P3: 100, Hi-Fi P4: 87.5 → Avg 93.75
Use blue bars for paper, green bars for hi-fi.

**Speaker Notes:**
Hi-fi testing showed clear improvement. SUS scores went from 87.5 average to 93.75. The improvement was especially significant for the less tech-savvy user — P4 scored 87.5 compared to P2's 80 in paper testing. Both participants completed all tasks without help. P3 called it night and day compared to paper. P4, our oldest participant, said it was the best-designed government-related app they'd seen.

---

## SLIDE 12 — SUS Score Comparison

**Title:** Usability Improvement: Paper → Hi-Fi

**Slide Content:**

Metric | Paper Testing | Hi-Fi Testing | Change
Average SUS | 87.5 | 93.75 | +6.25
Tech-savvy user | 95 | 100 | +5
Moderate user | 80 | 87.5 | +7.5
Task completion | 100% | 100% | Maintained
Key issue | Tracking density | Minor polish needs | Resolved

Key Insight: Visual design improvements benefited less tech-savvy users more (+7.5 vs +5), confirming that clarity and hierarchy matter most for accessibility.

**Image Placement:** None — this is a data slide. Use a clean table with the key insight highlighted in a colored callout box at the bottom.

**Speaker Notes:**
The data tells a clear story. While both rounds scored in the Excellent range, the hi-fi prototype improved across the board. Most importantly, the improvement was larger for the less tech-savvy user — a 7.5 point gain versus 5 points for the tech-savvy user. This confirms that our visual design improvements — clearer hierarchy, larger text, better labels — particularly benefit users who need more guidance.

---

## SLIDE 13 — What Users Said

**Title:** Participant Feedback

**Slide Content:**
- "This is exactly what I wanted — transparency." — P1, Paper Testing
- "If this app actually works and the government responds, it would be a game-changer." — P1, Paper Testing
- "Night and day. The paper version was overwhelming." — P3, Hi-Fi Testing
- "The text is a good size — I don't need my reading glasses for this." — P4, Hi-Fi Testing
- "This is the best-designed government-related app I've seen." — P4, Hi-Fi Testing

**Image Placement:** None — quote-focused slide. Use large quotation marks and attribute each quote clearly. Alternate quote colors (blue and green).

**Speaker Notes:**
Direct quotes from our participants capture the impact of our design decisions. P1 praised the transparency of the tracking system. P3 noticed the dramatic improvement from paper to hi-fi. P4, our oldest participant, specifically appreciated the readability — something we prioritized based on paper testing feedback. The consistent theme: if the government actually responds, this would transform civic engagement.

---

## SLIDE 14 — Ethical Considerations

**Title:** Ethical Design Principles

**Slide Content:**
- Privacy by Design: Minimal data collection, anonymous reporting, encrypted storage
- Transparency: Clear progress tracking, unalterable audit trails, open aggregate data
- Equity: Multi-channel reporting (app + WhatsApp + SMS), accessibility features, multi-language support
- Accountability: SLA tracking, escalation mechanisms, fraud detection
- User Autonomy: Opt-out options, data deletion, consent withdrawal
- Safety: Face blurring in photos, rate limiting, appropriate-use guidelines

**Image Placement:** Right side — A simple icon grid (6 icons in 2x3 layout) representing each principle: Shield (Privacy), Eye (Transparency), Scale (Equity), Checkmark (Accountability), User (Autonomy), Lock (Safety).

**Speaker Notes:**
Ethical considerations are central to our design. We built in privacy by design with minimal data collection and prominent anonymous reporting. Transparency through clear progress tracking and unalterable audit trails. Equity through multi-channel support so non-smartphone users aren't excluded. Accountability through SLA tracking and escalation. And safety through features like automatic face blurring in photos and rate limiting to prevent abuse.

---

## SLIDE 15 — Key Learnings

**Title:** What We Learned

**Slide Content:**
1. Progressive disclosure beats information density — Users want control over how much detail they see
2. Plain language matters — Technical jargon creates barriers even for tech-savvy users
3. Visual design is accessibility — Good hierarchy, large text, and clear labels help everyone
4. Trust is built through transparency — Report IDs, ETAs, and activity logs create confidence
5. Gamification works when meaningful — Karma points tied to real benefits (faster priority) motivate engagement
6. Testing with diverse ages reveals different needs — Younger users want speed; older users want clarity

**Image Placement:** Left side — A small screenshot collage showing the three most impactful changes: the simple tracking view, the prominent anonymous toggle, and the Add Tag button.

**Speaker Notes:**
Six key learnings from this process. First, progressive disclosure is powerful — give users a simple view and let them choose to go deeper. Second, plain language isn't optional — technical terms create real barriers. Third, good visual design IS accessibility — clear hierarchy helps everyone. Fourth, trust comes from transparency — report IDs and ETAs make the system feel real. Fifth, gamification works when it's meaningful, not just decorative. And sixth, testing with diverse ages reveals needs you'd never predict.

---

## SLIDE 16 — Next Steps & Thank You

**Title:** What's Next

**Slide Content:**
- Multi-language support — Kannada, Hindi, and other regional languages
- Voice input — For users who can't type easily
- Dark mode — Consistent across all screens
- WhatsApp/SMS integration — Alternative reporting channels
- Government backend — Full dashboard for officials and field workers
- Pilot deployment — Partner with one ward for real-world testing

**Image Placement:** Center — The Civic Snap logo/icon with "Thank You" below it. Add "Questions?" at the bottom.

**Speaker Notes:**
Our next steps include multi-language support, voice input for accessibility, consistent dark mode, WhatsApp and SMS integration for non-app users, a full government backend, and ultimately a pilot deployment with one ward. Thank you — we're happy to take questions.

---

## Image Placement Quick Reference

| Slide | Image Needed | Paper MCP Artboard ID | Notes |
|-------|-------------|----------------------|-------|
| 2 | Home Dashboard | 3FZ-0 | Hi-Fi version |
| 3 | 4 paper screens | 1N4-0, 1C9-0, DS-0, 1VI-0 | 2x2 grid |
| 5 | Paper Tracking | DT-0 | Add red callout |
| 7 | 4 onboarding screens | 3F0-0, 3FW-0, 3FX-0, 3FY-0 | Horizontal strip |
| 8 | 4 report screens | 3N0-0, 3N1-0, 3N2-0, 3XO-0 | 2x2 grid |
| 9 | Tracking comparison | 3T0-0 (left), 3T1-0 (right) | Side by side with arrow |
| 10 | Verify Fix | 3XN-0 | Left side of slide |
| 11 | Hi-Fi Home or Tracking | 3FZ-0 or 3T0-0 | Next to bar chart |
| 15 | 3 key changes | 3T0-0, 3N2-0, 3N1-0 | Small collage |

**How to capture screenshots from Paper MCP:**
1. Open Paper MCP in your editor
2. Select each artboard by name
3. Use the screenshot/export feature to capture each screen
4. Save as PNG files and insert into the PPT at the indicated positions
