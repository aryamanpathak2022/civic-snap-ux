# Hi-Fi Digital Prototype Testing — Interview 1 (Participant P3)
**Participant Code:** P3
**Date:** [Insert Date]
**Duration:** 36 minutes
**Role Tested:** Citizen Flows
**Prototype:** Hi-Fi Digital (Paper MCP)
**Facilitator:** [Name]
**Note-taker:** [Name]
**Recording:** Screen recording + audio

---

## Pre-Interview

**Facilitator:** Thank you for participating. Today we're testing a digital prototype for Civic Snap — an app for reporting civic issues. This is a high-fidelity prototype on a phone. Think out loud. I'll be recording. Is that okay?

**P3:** Yes, go ahead.

**Facilitator:** Age range?

**P3:** 18 to 24.

**Facilitator:** Comfort with apps, 1 to 5?

**P3:** 5. I basically live on my phone.

**Facilitator:** Ever reported a civic issue?

**P3:** I tweeted at the Bangalore traffic police once about a signal not working. They replied within an hour and fixed it the next day. Twitter is basically the best civic app in India.

**Facilitator:** Used any civic apps?

**P3:** No dedicated ones. Just Twitter and sometimes WhatsApp groups for our apartment complex.

**Facilitator:** Biggest frustration?

**P3:** No feedback loop. You report something and never know if anyone cares. Also, most government systems feel like they were designed in 2005.

**Facilitator:** What would make you use an app for this?

**P3:** Speed and transparency. If I can report in under a minute and actually see progress, I'd use it. Also, it needs to look good — if it looks ugly, I assume it doesn't work well.

**Facilitator:** Let's begin.

---

## Task 1: End-to-End Report Flow

*[Facilitator opens Landing Page on device]*

**P3:** Okay, this looks really polished. Dark theme with the gradient — very modern. I like the three feature cards at the bottom telling me what the app does. "Get Started" is obvious.

*[Taps Get Started → Phone Login]*

**P3:** Phone number entry. Country code is already +91 which is good. The input field is clean. I'd type my number and hit Continue.

*[Taps Continue → OTP]*

**P3:** OTP screen — six boxes, timer, resend option. Very standard. I've seen this in every Indian app. The "Change phone number" link is clearly visible at the bottom.

*[Enters OTP → Profile Setup]*

**P3:** Profile setup. I see "Add Profile Photo" with "Optional" clearly marked — that's good. Name field is straightforward. The area is auto-detected as "Ward 86 · Indiranagar" with a note saying "Auto-detected from your location · Tap to change." That's much better than a confusing dropdown. And the helper text at the bottom explains why they need my area.

*[Taps Save & Continue → Home Dashboard]*

**P3:** Home screen looks really clean. I see my name, a karma badge with 142 points and a star icon, and a notification bell with a red dot. The quick action cards are prominent — "Report Issue" is blue and stands out. "My Reports" and "Map View" are secondary. 

**Facilitator:** What are you thinking about the karma badge?

**P3:** It's right there in the header — I can't miss it. 142 points. I'm curious what that means. I'd tap it later to understand.

**P3:** I see "Active Reports" with two cards. One is "In Progress" with a yellow badge and a mini progress bar showing step 3 of 5. The other is "Resolved" in green with "+12 points earned." That's nice — it connects the karma system to actual activity.

**P3:** Below that is "Nearby Issues" with a mini map showing colored pins and "7 issues near you." I'd tap "Report Issue" now.

*[Taps Report Issue → Category Selection]*

**P3:** Category selection — grid of six cards with icons. Road Damage, Streetlight, Garbage, Water Issue, Sidewalk, Other. Each has a colored icon. I'd tap "Water Issue" for the broken pipe scenario. There's also a search bar at the top.

**Facilitator:** How does this compare to the paper version?

**P3:** Much clearer. The paper version had categories but they were just text. These cards with colored icons are way more scannable.

*[Taps Water Issue → Photo & Tags]*

**P3:** Photo upload area with Camera and Gallery buttons. Below that, the AI auto-tags section. I see detected tags as chips with an X to remove them. And there's an "Add Tag" button with a plus icon — that's new, right? In the paper version you could only remove tags.

**Facilitator:** Yes, that was added based on feedback.

**P3:** Good addition. I'd add "Pipe Burst" as a custom tag. The description field is below, then the location with a map preview and "Use Current Location" button. The map shows a draggable pin with "Drag pin to adjust" — very clear.

*[Taps Continue to Submit → Review & Submit]*

**P3:** Review screen shows a summary card with the photo placeholder, category, tags, and description. Below that, a green card saying "Auto-Routed To: BBMP Roads Department · Ward 86 · Estimated response: 48 hours." That's really reassuring.

**P3:** And the Anonymous Reporting toggle is now prominent — it's a full card with a shield icon, title, description, and an actual toggle switch. In the paper version it was tiny text at the bottom. This is way better.

*[Taps Submit Report → Confirmation]*

**P3:** Big green checkmark. "Report Submitted!" with Report ID CS-2026-0847, status "Received," category, routed department, and estimated response time. Two buttons: "Track This Report" and "Back to Home." 

**Facilitator:** How was the overall flow?

**P3:** Really smooth. The visual design is clean and modern. Each step is clear. I'd estimate the whole thing takes about 60-90 seconds. The auto-routing info and ETA give me confidence that something will actually happen.

**Observations:**
- Immediately praised visual design ("looks really polished")
- Noted "Optional" photo label as positive
- Appreciated auto-detected area with explanation
- Noticed karma badge in header immediately
- Identified "Add Tag" as an improvement over paper
- Praised prominent anonymous toggle
- Confirmation screen well-received
- Estimated full flow at 60-90 seconds

---

## Task 2: Track & Verify a Report

**P3:** I'm on the home screen. I'd tap "Reports" in the bottom nav.

*[Taps Reports → My Reports list]*

**P3:** I see my reports list. Each card has an icon, title, location, status badge, and for the in-progress one, a mini progress bar. I'd tap the "In Progress" one.

*[Taps report → Tracking Simple View]*

**P3:** Okay, this is the tracking screen. I see "Progress Steps" — not "Stage-gates" anymore, right? That's much clearer. It shows a vertical timeline: Received (green check), Assigned (green check), In Progress (blue active dot), Resolved (grey), Verified (grey). 

**P3:** There's a yellow delay notice: "Awaiting electrical parts. New ETA: March 20." That's honest and helpful.

**P3:** Below that, there's a "Show Details" button. I'd tap that.

*[Taps Show Details → Detailed View]*

**P3:** Now I see the expanded view. "Activity History" shows a timeline of events — work started, delay notice, assigned, received. Each with a timestamp. And "Field Worker Tasks" shows a checklist: Arrive at location (done), Take before photo (done), Replace streetlight fixture (in progress), Take after photo (pending), Mark as complete (pending).

**Facilitator:** How does this compare to the paper tracking screen?

**P3:** Night and day. The paper version was overwhelming — everything on one screen. This simple view gives me exactly what I need at a glance, and I can dig deeper if I want. The terminology is also much better — "Progress Steps" instead of "Stage-gates," "Field Worker Tasks" instead of "Digital Handshake."

**P3:** I'd tap "Hide Details" to go back to the simple view. That's my preferred view for regular checking.

**Observations:**
- Immediately noticed terminology improvements
- Preferred simple view for regular checking
- Used "Show Details" to explore
- Activity history timeline well-understood
- Field worker task checklist intuitive
- Called the improvement "night and day" vs paper version

---

## Task 3: Browse Nearby Issues

**P3:** From home, I'd tap "Map View."

*[Opens Map View]*

**P3:** The map shows colored pins — red for urgent, yellow for in progress, green for resolved. I can see a filter bar at the top with Status, Category, and Time filters. That's useful — I can filter to show only unresolved road issues, for example.

**P3:** I'd tap a red pin.

*[Taps pin → Public Issue View]*

**P3:** I see the issue details — type, location, date, status, photo. No personal info about who reported it. And a "Support This Report" button. I'd tap that to show support.

**Facilitator:** What do you think the support does?

**P3:** It's like an upvote. If many people support the same issue, it should get higher priority. That's smart crowd-sourcing.

**Observations:**
- Map filters appreciated
- Color coding consistent with rest of app
- Privacy respected in public view
- "Support This Report" well-understood

---

## Task 4: Profile & Karma

**P3:** I'd tap "Profile" in the bottom nav.

*[Opens Profile]*

**P3:** I see my profile photo, name, area, and karma section. My karma is 142 points, and I'm at "Active Reporter" level (51-200 points). There's an info icon that explains: "Trust points increase with verified reports and fix confirmations. Higher trust = faster response priority."

**Facilitator:** Is the karma system clear now?

**P3:** Yes, much clearer than the paper version. The levels make sense — New Citizen, Active Reporter, Community Champion, Civic Leader. And knowing that higher trust means faster priority gives me a reason to keep using the app. It's not just a vanity metric.

**Observations:**
- Karma levels well-understood
- Trust-to-priority connection appreciated
- Info icon explanation effective
- System seen as motivating, not gimmicky

---

## Post-Interview

**Facilitator:** Easiest task?

**P3:** Reporting an issue. The flow is so well-designed that it's almost enjoyable.

**Facilitator:** Hardest?

**P3:** None were hard. But the tracking screen's detailed view has a lot of information. The simple view is perfect for most people.

**Facilitator:** Any confusion?

**P3:** No. Everything was clear. The visual hierarchy is excellent — I always knew what the primary action was on each screen.

**Facilitator:** How about the number of steps?

**P3:** The report flow has about 6-7 screens, but each is simple and quick. It doesn't feel long because there's a progress indicator at the top of each step.

**Facilitator:** SUS questionnaire...

*[SUS administered]*

**SUS Responses:**
| # | Statement | Score |
|---|-----------|-------|
| 1 | I think I would like to use this app frequently | 5 |
| 2 | I found the app unnecessarily complex | 1 |
| 3 | I thought the app was easy to use | 5 |
| 4 | I think I would need technical support | 1 |
| 5 | Functions were well integrated | 5 |
| 6 | Too much inconsistency | 1 |
| 7 | Most people would learn quickly | 5 |
| 8 | App was cumbersome | 1 |
| 9 | I felt confident using the app | 5 |
| 10 | Needed to learn a lot before getting going | 1 |

**SUS Score Calculation:**
- Odd: (5-1) + (5-1) + (5-1) + (5-1) + (5-1) = 20
- Even: (5-1) + (5-1) + (5-1) + (5-1) + (5-1) = 20
- Total: 40 × 2.5 = **100/100**

**Facilitator:** One thing to change?

**P3:** Honestly, nothing major. Maybe add a dark mode option since the landing page has a dark theme but the rest is light. And maybe add haptic feedback when you submit a report — that little vibration would feel satisfying.

**Facilitator:** Trust with location?

**P3:** Yes, because it's necessary for the app to work. But I'd want a privacy policy that's actually readable — not 20 pages of legal jargon.

**Facilitator:** Recommend to a friend?

**P3:** Absolutely. If this works in real life, it would be the most useful civic app in India. The design is on par with any startup app.

---

## Facilitator Notes

**Overall Impression:** P3 was extremely positive. As a young, tech-savvy user, they appreciated the modern visual design and smooth interactions. All improvements from paper testing were noticed and praised.

**Key Quotes:**
- "This looks really polished. Dark theme with the gradient — very modern."
- "Night and day. The paper version was overwhelming."
- "If this works in real life, it would be the most useful civic app in India."

**Top Issues:**
1. Dark mode inconsistency (landing dark, rest light)
2. Request for haptic feedback on submission
3. Desire for readable privacy policy

**SUS Score:** 100/100 (Perfect)
**Task Completion:** 4/4 (100%)
