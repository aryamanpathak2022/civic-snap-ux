# Paper Prototype Testing — Interview 2 (Participant P2)
**Participant Code:** P2
**Date:** [Insert Date]
**Duration:** 42 minutes
**Role Tested:** Citizen Flows
**Facilitator:** [Name]
**Note-taker:** [Name]
**Recording:** Yes (video + audio)

---

## Pre-Interview

**Facilitator:** Thank you for participating. Today we're testing a prototype for an app called Civic Snap — it helps citizens report civic issues like potholes, broken lights, and garbage problems. This is a paper prototype, so I'll show you printed screens and swap them based on your actions. There are no wrong answers — we're testing the design, not you. Please think out loud. I'll be recording. Is that okay?

**P2:** Yes, that's fine.

**Facilitator:** What's your age range?

**P2:** 35 to 44.

**Facilitator:** How would you rate your comfort with smartphone apps, 1 to 5?

**P2:** I'd say 4. I use WhatsApp, UPI apps, Google Maps regularly. But I'm not someone who downloads new apps every week.

**Facilitator:** Have you ever reported a civic issue?

**P2:** Many times. I've called the municipal corporation about garbage collection issues at least ten times. Once I wrote a letter to the ward office about a water logging problem. The letter actually got a response but took three weeks.

**Facilitator:** Have you used any civic or government apps?

**P2:** I tried the MyGov app once. It felt more like a news portal than a problem-solving tool. I also used a pothole reporting app in Pune a few years ago — it was okay but I never knew if anything happened with my reports.

**Facilitator:** What frustrates you most about the current process?

**P2:** The biggest frustration is the lack of follow-up. You report something and then nothing. You don't know if anyone saw it, if it's being worked on, or if it was just ignored. Also, the phone numbers change, the offices are hard to reach, and you often get transferred between departments.

**Facilitator:** What would make you more likely to report an issue with an app?

**P2:** If I knew someone was actually going to act on it. And if I could see progress — like, "your report has been received, assigned to X department, work will start by Y date." That would give me confidence. Also, it should be simple. I don't want to fill out ten fields for one pothole.

**Facilitator:** Perfect. Let's begin.

---

## Task 1: Account Creation & Login

**Facilitator:** Imagine you just downloaded Civic Snap. You want to create an account using your phone number. Go ahead.

*[Facilitator places Landing Page]*

**P2:** Okay, I see "Civic Snap" with a logo that says [CS] and the tagline "Report city issues in seconds. Track resolution in real time." Three steps shown: ① Snap photos, ② Auto Route, ③ Track & Verify. Two buttons: "Get Started" and "Sign In." I'll tap "Get Started."

*[Facilitator swaps to Phone Login screen]*

**P2:** It says "Civic Snap — Report city issues in seconds" at the top. Phone field with +91 and a number 78350 57890. Below that, "— OR —" and then buttons: [Google] [Email]. Footer: "By continuing, you agree to our Terms & Conditions." I'll type my number...

*[P2 types number, then pauses]*

**P2:** I've entered my number, but... where's the Continue button? I don't see any button to proceed. I'd expect a "Continue" or "Next" or "Verify" button right below the phone field, but there's nothing there.

**Facilitator:** What would you do?

**P2:** I'd probably tap somewhere else on the screen to see if the button appears, or I might think something is broken. It's confusing — the most important button on this screen is missing. I'd eventually figure there should be a button and ask someone or try scrolling down.

*[Facilitator notes the missing Continue button as a design issue]*

**P2:** Assuming the button was there, I'd tap Continue. The flow is simple conceptually — just phone number, no email, no password. But that missing button is a real problem. People would think the app is broken or that they did something wrong.

**Facilitator:** Good question. Let's continue.

*[Facilitator swaps to OTP screen]*

**P2:** Now it says "Civic Snap" at the top with "Verify phone" subtitle. "6 digit code sent to +91XXX-90." Six boxes [1][2][3][_][_][_]. "Didn't receive code? Resend in 0:50." Button: [Verify & Continue]. Link: "← Change Number." I'd enter the code. The countdown timer is useful.

**P2:** The "Change Number" link at the bottom is good — I can go back if I entered the wrong number.

*[Facilitator swaps to Create Profile screen]*

**P2:** "Create Profile" at the top. Fields: Name [XXX XXX], Age [XX] ▼ (dropdown), Location 📍 "Choose on map," Email ID [XX@X.X]. Button: [Continue].

**P2:** Wait — this screen has a "Continue" button! But the phone login screen didn't! That's inconsistent. Anyway, I'd fill in my name, use the age dropdown, tap "Choose on map" for my area, and enter my email.

**P2:** The "Choose on map" for location is interesting — I'd expect it to open a map where I can pin my area. But what if the map doesn't load? Is there a text fallback? And there's no photo field at all — just name, age, location, email. That's simpler, but some people might want to add a photo.

*[Facilitator swaps to Home Dashboard]*

**P2:** Now I'm on the home screen. I see my name, some quick actions, and a section called "Active Reports." It's empty right now since I haven't reported anything. The layout is clean.

**Facilitator:** How did you feel about the onboarding?

**P2:** It was straightforward. Four steps is reasonable. My only concern is the profile photo — it should clearly say "optional." And the area field needs to be clearer about how to input it.

**Observations:**
- Confusion at phone login — no Continue button visible after entering number
- Noticed inconsistency: Profile has Continue button but phone login doesn't
- "Choose on map" for location is interesting but needs fallback
- No photo field in wireframe — some users may want to add one

---

## Task 2: Report a Pothole

**Facilitator:** You're walking home and notice a large pothole. Report it through the app.

**P2:** On the home screen, I see "Welcome back Rahul……" at the top, a [Public] badge, person and bell icons, stats row: My Reports 12, Karma Points 247, Verified 11. Below that, "Quick Report — Report any city issue in seconds" with an "AI Auto Tag" label. And a big [+ New Report] button. I'd tap that.

*[Facilitator swaps to Report Hazard screen]*

**P2:** It says "Civic Snap — Report Hazard" at the top. There's a "+ Click Image" button to take a photo. Below that, "AI Auto Tags™" with three buttons: [Auto Detect] [Routes List] [+ Add Tag]. Then a "Context / Add details: ………" text field and a [Submit Report] button.

**P2:** So the app automatically tags the issue when I take a photo? [Auto Detect] detects what's in the image, and [Routes List] shows which department it gets sent to?

*[Facilitator confirms]*

**P2:** That's impressive if it works well. But I notice the tag chips [Auto Detect] and [Routes List] don't have X buttons on them. If the AI tags my issue as "Streetlight" when it's clearly a pothole, how do I remove that? There's no way to remove wrong tags. This is a significant problem.

**Facilitator:** What would you expect?

**P2:** Each tag should have an X button so I can remove ones that are incorrect. I'd also want to add my own tags using the [+ Add Tag] button, but fixing wrong AI tags is the priority.

**P2:** I'd write "Large pothole, about 2 feet wide, near the bus stop on 80 Feet Road" in the Context field and tap [Submit Report].

*[Facilitator swaps to Confirmation screen]*

**P2:** Green checkmark. "Report Submitted — Your hazard report has been received & logged in the system." Ticket ID: #CS-2029-0857. And two buttons: [Track this Report] and [Report Another Issue].

**Facilitator:** How do you feel?

**P2:** Satisfied. The report ID makes it feel official. The 48-hour estimate sets expectations. I like that I can track it right away. The whole process felt like it took about 2 minutes, which is acceptable.

**Observations:**
- Found [+ New Report] button immediately
- AI Auto Tags™ section with [Auto Detect] [Routes List] [+ Add Tag] understood
- AI auto-detected tags have no X/cross button — can't remove incorrect tags (critical issue)
- [+ Add Tag] button noticed as a way to add custom tags
- No category selection screen — goes straight to photo/tags
- Report ID #CS-2029-0857 and submission confirmation appreciated

---

## Task 3: Check Report Status

**Facilitator:** You reported a broken streetlight last week. Check if it's been fixed.

**P2:** On the home screen, I see "Active Reports" but I'm not sure if the streetlight would show there since it was last week. Let me check the bottom navigation. I see "My Reports" — actually I see "View All" next to Active Reports. I'd tap that.

*[Facilitator swaps to My Reports screen]*

**P2:** "← My Reports" at the top with a search bar: "🔍 Search your Reports." Two cards below: [In Progress] #CS-057 — Pothole on MG Road with an image placeholder and [Track →] link, and [Resolved] #CS-058 — Broken Streetlight with ✅ Verified by You.

**P2:** The status badges are clear — yellow for in progress, green for resolved. Like traffic lights. Easy to understand.

*[Facilitator swaps to Live Tracking screen]*

**P2:** This is the tracking screen. Header says CS-[ID]. Progress bar shows: Reported → BWSSB → On Site → Done. The "On Site" stage is active. Below that, "ETA: 28/March 2025." Then "Agency: BWSSB" with a stop icon, and "BWSSB" with a field report icon. There's a "View Activity Logs" link and a [Verify Repair] button.

**Facilitator:** What do you think?

**P2:** The progress bar is very clear — I can see exactly where things stand: Reported → BWSSB → On Site → Done. The agency information shows which department is handling it. But there's a lot of information here. The "View Activity Logs" and field report sections are below the fold.

**P2:** Maybe there should be a simple view and a detailed view. Just the progress bar, status, and ETA for a quick check. Then an expandable section for the activity logs and field reports.

**Observations:**
- Found My Reports via View All link easily
- Status color coding (yellow=in progress, green=resolved) immediately understood
- Progress bar was the standout feature
- Progress stages (Reported → BWSSB → On Site → Done) were clear
- Delay notice appreciated
- Screen too information-dense for average users
- Agency information on tracking screen was useful
- Suggested simple vs. detailed view toggle for tracking

---

## Task 4: Verify a Fix

**Facilitator:** You get a notification that the pothole has been repaired. The app asks you to verify. What do you do?

**P2:** I'd tap the notification.

*[Facilitator swaps to Verify Repair screen]*

**P2:** The header says CS-[ID] and the title says "VERIFY REPAIR — Citizen Sign Off Required." That's very clear — it's telling me I need to sign off on this. Two image placeholders side by side: Before and After. Below that, "GPS Locked: 2026-03-28 | Crew ID: 535 ER." That's reassuring — it tells me the repair was verified at the right location.

**Facilitator:** What would you do next?

**P2:** I'd compare the before and after photos. If the after photo looks good, I'd tap the [VERIFY] button. If not, there's a link that says "Not happy? Details."

**Facilitator:** What do you think about the dispute option?

**P2:** "Not happy? Details" is a text link — it's a bit vague. I'd want to know what happens when I click it. And I'd want specific options to choose from — like "Repair not completed" or "Wrong location" or "Temporary fix only." Just a blank text field isn't enough.

**P2:** But the GPS lock and Crew ID information adds trust. I can see that a real crew member was at the right location at the right time.

**Facilitator:** That's a great insight.

*[Facilitator swaps to confirmation after Confirm]*

**P2:** Now it says "Karma badge earned · +18 trust points." That's a nice touch. It makes me feel like I contributed something.

**Facilitator:** Would the karma system motivate you?

**P2:** Honestly, yes. It's a small thing but it makes civic participation feel rewarding. I'd probably check my karma score occasionally. It's like a credit score for being a good citizen.

**Facilitator:** Is the karma concept clear?

**P2:** Mostly. But I'd want to know what the points mean. Can I redeem them? Do they give me any status? Or is it just for show? A small info icon explaining the karma system would help.

**Observations:**
- "VERIFY REPAIR — Citizen Sign Off Required" title was very clear
- Before/After comparison intuitive
- GPS Locked + Crew ID added trust
- "Not happy? Details" link too vague — wanted specific dispute reasons
- Wanted confirmation dialog before disputing
- Karma system well-received but needed explanation
- Compared karma to "credit score for being a good citizen"

---

## Task 5: Browse Nearby Issues

**Facilitator:** You're curious about issues others have reported nearby. Browse them.

**P2:** On the home screen, I see "Nearby Issues" in the Quick Report section. I'd look for a map view.

*[Facilitator swaps to Public Reports Map screen]*

**P2:** I see a search bar "🔍 Search area or Issue" and a map with pins. Below the map, colored dots: ● Reported ● Pending ● Resolved — those are filters. And a "Nearby Issues" section showing "Pothole MG Road" and "Broken Streetlight" with images.

*[Facilitator swaps to Public Issue Detail screen]*

**P2:** "← Public Issue" at the top with an image placeholder. Title: "Pothole MG Road | ● In Progress." Reported by: Priya S. | 2 hrs ago. Location: 📍 Church Street, MG Road, Ward 65, Bengaluru. Description: "Large pothole near MG Road entrance…" No personal information beyond a first name.

**P2:** I notice there's no "Support This Report" button like P1 mentioned. It's just the issue details — type, location, who reported it, and the description.

**Facilitator:** What does that do?

**P2:** I'm guessing it's like an upvote — if many people support the same issue, it gets higher priority. That's smart. It helps the government understand which issues affect the most people.

**Facilitator:** Anything confusing?

**P2:** The map is a bit cluttered when there are many pins. I'd want a filter — like show only unresolved issues, or filter by category. Also, I can't tell from the pin what type of issue it is without tapping. Maybe different shapes for different categories?

**Observations:**
- Map had ● Reported ● Pending ● Resolved filter dots
- Privacy respected — only first name visible
- Map clutter concern with many pins
- Suggested category-based pin shapes or filters

---

## Task 6: View Notifications

**Facilitator:** You want to check if there are any updates on your submitted reports. Show me how you'd look at your notifications.

**P2:** On the home screen, I see a bell icon 🔔 with a red dot in the top right. That usually means I have notifications. I'd tap that.

*[Facilitator swaps to Notifications screen]*

**P2:** "← Notifications" at the top with a "Mark All Read" link on the right. The notifications are grouped by date. Under "Today": "Report CS-2024-0849 was updated · 2 hrs ago." Under "24/01/2026": "Report CS-2025-0689 was marked resolved · 29/01/24 4:30" and "Report CS-2025-0689 awaiting your feedback."

**Facilitator:** Can you read through them?

**P2:** Under "Today," it says "Report CS-2024-0849 was updated · 2 hrs ago." And under an older date, "Report CS-2025-0689 was marked resolved" and "Report CS-2025-0689 awaiting your feedback." The one about feedback sounds like it needs me to do something — probably verify a fix, like we did earlier.

**Facilitator:** Would you act on that?

**P2:** Yes, I'd tap on the "awaiting your feedback" one. That should take me to the verification screen.

**Facilitator:** What do you think of this screen?

**P2:** It's organized well. Grouping by date is helpful. But I'm looking at this as someone who checks it carefully — someone less patient might just want to see what needs their attention. It would be nice to have a filter or a separate section for "Action Required" notifications versus just "Updates." The "awaiting your feedback" one is different from "was updated" — one needs me to do something, the other is just information.

**P2:** Also, I notice there's no way to delete individual notifications. I'd want to clear old ones that I've already handled.

**Observations:**
- Found notifications via bell icon with red dot
- Understood date grouping immediately
- Distinguished between informational and action-required notifications
- Suggested "Action Required" filter or separate section
- Wanted ability to delete individual notifications
- "Mark All Read" was clear

---

## Task 7: View & Edit Profile

**Facilitator:** You want to check your profile and see your reporting stats. Show me how you'd access your profile and what you see.

**P2:** On the home screen, I see a person icon 👤 in the top right. I'd tap that.

*[Facilitator swaps to Profile screen]*

**P2:** "← [A] Ayush Patel | Indiranagar" at the top. ⭐ 1250 Karma Points. Stats: 23 Reports | 18 Resolved. Menu items: [My Reports] [Notification & Billing]. And a [Sign Out] button at the bottom.

**Facilitator:** How would you edit your information?

**P2:** Hmm, I'm looking for an "Edit" button... I don't see one. There's no pencil icon, no "Edit Profile" link. I'd expect it near my name. Maybe I'm supposed to tap on the [A] avatar to change it? That's not very obvious.

**Facilitator:** What would you expect?

**P2:** I'd expect a clear "Edit Profile" button near the top. And for specific fields, I'd expect to tap on each one. But none of that is indicated here. Just [My Reports], [Notification & Billing], and [Sign Out].

**Facilitator:** What about the karma points?

**P2:** 1250 points with a star. But what does it mean? Is it just a score? Can I redeem it? Does it give me priority? There should be a small info icon explaining what karma points do. I'd want to know if being a high-point user means my reports get handled faster.

**Observations:**
- Found profile via person icon
- Stats display (Reports, Resolved) was clear and appreciated
- No visible "Edit Profile" button — major usability concern
- Karma points visible but purpose unclear
- Wanted explanation of karma system benefits
- Sign Out was clear and accessible
- Suggested field-level editing (tap name, tap area)

---

## Task 8: Field Worker — View & Complete Task

**Facilitator:** Now switch roles. You're a field worker named Ramesh. You've been assigned a task — a broken manhole cover on 12th Main, Indiranagar. Show me how you would start and complete this task.

*[Facilitator places Field Worker Login screen]*

**P2:** This is a different login — "Civic Sende — Field Worker Portal." It wants Employee ID [X X X X] and Department [Select Department ▼]. I'd type my employee ID and select my department.

*[Facilitator swaps to Field Worker Dashboard]*

**P2:** "Hi Ramesh! | My Work" at the top. Stats: 2 High Priority | 2 Medium | 1 Completed. Task cards below. First: "[High Priority] SLA-2hr — Broken Manhole Cover, Indiranagar, 12th Main | #TK-4521 | [Start]." Second: "[High Priority] SLA-6hr — Water Pipe Burst | [Start]."

**Facilitator:** What do you notice about the task cards?

**P2:** The priority badges are clear — red for high. The SLA timers help me understand urgency. I can see the task title and location at a glance.

*[Facilitator swaps to Task Details screen]*

**P2:** "← Task Details | #TK-4521 | [High Priority]" at the top. Title: "Broken Manhole Cover." Two image placeholders. Description: "Large Manhole Cover Missing." Location: 📍 Indiranagar with a map pin. Button: [Complete].

*[Facilitator swaps to GPS Checkout screen]*

**P2:** "← GPS Checkout | #TK-4521" at the top. "GPS → Verified: Indiranagar, 12th Main." Before Photo: [↑ Upload Photo]. After Photo: [↑ Upload Photo]. Notes (Optional): [text field]. Button: [Submit Checkout].

**P2:** GPS Checkout. It says "GPS Verified: Indiranagar, 12th Main." So it checks I'm at the right location. Below that, "Before Photo" upload, "After Photo" upload, "Notes (Optional)" field, and "Submit Checkout" button.

**P2:** The GPS verification is important — it means I can't complete the task without actually being there. Good for accountability. And the notes being optional is fine — sometimes there's nothing extra to add.

**Facilitator:** Is there anything missing from this flow?

**P2:** I'd want to flag a problem if I arrive and the issue doesn't match the report. Like if the description says "broken manhole" but it's actually a water leak, I need a way to report that. Also, what if the task takes longer than the SLA? Can I request more time?

**P2:** And the text on this screen is a reasonable size, which I appreciate. I'd be using this outdoors on-site, so readability matters.

**Observations:**
- Understood field worker login (Employee ID + Department)
- Dashboard stats and SLA timers were immediately clear
- Before/after photo flow intuitive
- GPS verification seen as accountability measure
- Wanted ability to flag discrepancies between report and reality
- Wanted ability to request SLA extension
- Text readability appreciated for outdoor use
- Flow described as clear and task-oriented

---

## Task 9: Government Official — Review Reports & Assign Tickets

**Facilitator:** One last role. You're a government official at the BWSSB office. You need to review incoming reports and assign a ticket to a field worker.

*[Facilitator places Government Official Login screen]*

**P2:** "Civic Snap — Official Portal." Office Email ID [text field], Department [Select ▼], and Password [● ● ●]. Three fields instead of one. I'd fill these in and tap [Login].

*[Facilitator swaps to Government Dashboard]*

**P2:** "Hello BWSSB Office" with stats: 12 Critical | 28 Pending | 156 Resolved. Below that, a heatmap grid with shaded cells. And "Reported Queue [See All]" with "[High Priority] SLA-2hr — Manhole Opened #TK-4521."

**P2:** The heatmap — I'm not sure I understand it right away. What do the darker areas mean?

**Facilitator:** What would you guess?

**P2:** I'd guess darker means more issues. But a legend would help — like "darker = more reports" somewhere visible. Without one, I'm guessing.

*[Facilitator swaps to Reports Queue]*

**P2:** "Reports ——— [+ Create Manual]" at the top. Three cards: "[High Priority] — Manhole Open 📍 Indiranagar" with [Assign] [Details], "[Medium Priority] — Garbage 📍 MG Road" with [Assign] [Details], and "[Medium Priority]" with just [Assign].

**P2:** But with many reports, this list will get long. I'd want filters — by priority, by area, by date. Scrolling through everything isn't efficient.

*[Facilitator swaps to Assign Ticket screen]*

**P2:** "← Assign Tickets | #TK-0591." Employee Name field with [🔍 Search Name] and a Note text area. Button: [Assign].

**P2:** The search just gives me names. I need to see their current workload, how many tasks they already have. Just a name search isn't enough for smart decisions.

*[Facilitator swaps to Ticket Details screen]*

**P2:** "← Ticket Details | #TK-0591 | [User Details]." Two image placeholders. Title: "Manhole Opened." Location: 📍 Indiranagar. Description text area. Progress: "● Reported → ● BWSSB Assigned."

*[Facilitator swaps to User Details screen]*

**P2:** "User Details | #TK-059." Name: Rajesh, Phone Number: XXX-XXX, Email: X@.com, Location: Whitefield, Karma Points: 1250. Buttons: [Message] [Call]. Link: "Report User !"

**P2:** Karma points 1250 — that's a trusted, active reporter. It helps me prioritize.

*[Facilitator swaps to Create Manual Ticket screen]*

**P2:** "← Create Manual Ticket" at the top. Location: [🔍 Search Location], Images: [↑ Upload Img], Priority buttons: [High] [Medium] [Low], Description: [text area], Button: [Create]. Clean and straightforward for phone-in reports.

**P2:** The priority buttons are clear — I can see all three options without opening a dropdown. For an older person like me, that's helpful.

**Observations:**
- Understood secure three-field login for official portal
- Dashboard stats clear but heatmap needed a legend
- Wanted filtering in reports queue (priority, area, date)
- Wanted worker workload/availability context in assignment screen
- User Details with karma points seen as useful for trust assessment
- Manual ticket creation straightforward
- Priority buttons (not dropdown) appreciated for accessibility
- Suggested ability to contact citizens for more details

---

## Post-Interview

**Facilitator:** Which task was easiest?

**P2:** Reporting the pothole. It was very guided and logical.

**Facilitator:** Which was hardest?

**P2:** The tracking screen. Not because it was difficult, but because there was so much information. I had to scroll a lot and process everything.

**Facilitator:** Any screen where you weren't sure what to do?

**P2:** The profile setup — the "Choose on map" for location and no photo field. And the tracking screen had a lot of information to process at once.

**Facilitator:** Any labels or icons that confused you?

**P2:** The anonymous reporting toggle was too small. I almost missed it entirely. And the karma system — I understood the concept but wanted to know what the points actually do.

**Facilitator:** How did you feel about the number of steps to report?

**P2:** It was fine. About 5 steps, each quick. I'd estimate 90 seconds total. Acceptable.

**Facilitator:** Did you understand what happens after submitting?

**P2:** Yes. The confirmation screen was clear — report ID, status, ETA. And I could track it immediately.

**Facilitator:** Now the SUS questionnaire...

*[SUS administered]*

**SUS Responses:**
| # | Statement | Score |
|---|-----------|-------|
| 1 | I think I would like to use this app frequently | 4 |
| 2 | I found the app unnecessarily complex | 2 |
| 3 | I thought the app was easy to use | 4 |
| 4 | I think I would need technical support | 1 |
| 5 | Functions were well integrated | 4 |
| 6 | Too much inconsistency | 2 |
| 7 | Most people would learn quickly | 4 |
| 8 | App was cumbersome | 2 |
| 9 | I felt confident using the app | 4 |
| 10 | Needed to learn a lot before getting going | 1 |

**SUS Score Calculation:**
- Odd: (4-1) + (4-1) + (4-1) + (4-1) + (4-1) = 3+3+3+3+3 = 15
- Even: (5-2) + (5-1) + (5-2) + (5-2) + (5-1) = 3+4+3+3+4 = 17
- Total: 32 × 2.5 = **80/100**

**Facilitator:** If you could change one thing?

**P2:** Simplify the tracking screen. Make it two levels — a quick status view and a detailed view. And replace technical jargon with plain language.

**Facilitator:** Would you trust this app with your location?

**P2:** Yes, but I'd want a clear privacy statement explaining what happens with my location data. Is it stored? Shared? Used for anything beyond reporting?

**Facilitator:** Would you recommend it?

**P2:** Yes, with a caveat. I'd recommend it if I knew the government actually responds. The app design is good, but the real test is whether it leads to action.

**Facilitator:** Additional comments?

**P2:** The app is well-designed. My main suggestions are: simplify the tracking screen, clarify the profile setup, make anonymous reporting more visible, explain the karma system, and use plain language instead of technical terms.

---

## Facilitator Notes

**Overall Impression:** P2 was thoughtful and methodical. Less tech-savvy than P1 but still comfortable with apps. Provided excellent feedback on information architecture and terminology. More concerned about privacy and government responsiveness.

**Key Quotes:**
- "The progress bar is very clear — I can see exactly where things stand."
- "It's like a credit score for being a good citizen."
- "The app design is good, but the real test is whether it leads to action."

**Top Issues Identified:**
1. **Anonymous reporting toggle** — The toggle for anonymous reporting was too small and subtle. P2 almost missed it entirely. It needs to be more prominent, perhaps a full card with a shield icon and clear label rather than a tiny toggle buried at the bottom.
2. **Profile photo requirement unclear** — P2 was unsure whether the profile photo was mandatory and wanted it clearly marked as "Optional." Also unclear whether the area field was a dropdown or free text.
3. **Karma explanation — points had no context** — P2 understood the karma points number but had no idea what it meant or what benefits it provided. Needed an info icon or explanation linking trust to priority.
4. **Map filters — no way to filter by status/category** — P2 found the map cluttered with pins and wanted filters for status (open, in progress, resolved) and category. Also suggested category-based pin shapes for quicker identification.

**Session Rating:** Positive. Good SUS score (80). Participant would use the app but wants assurance of government responsiveness. All three portal roles were understandable with consistent design language.
