# Paper Prototype Testing — Interview 1 (Participant P1)
**Participant Code:** P1
**Date:** [Insert Date]
**Duration:** 38 minutes
**Role Tested:** Citizen Flows
**Facilitator:** [Name]
**Note-taker:** [Name]
**Recording:** Yes (video + audio)

---

## Pre-Interview

**Facilitator:** Thank you for participating. Today we're testing a prototype for an app called Civic Snap — it's designed to help citizens report civic issues like potholes, broken streetlights, and garbage problems. This is a paper prototype, so I'll be showing you printed screens and swapping them based on what you do. There are no wrong answers — we're testing the design, not you. Please think out loud as you go. I'll be recording this session. Is that okay?

**P1:** Sure, that's fine.

**Facilitator:** Great. Before we start, a few quick questions. What's your age range?

**P1:** 25 to 34.

**Facilitator:** How would you rate your comfort with smartphone apps, 1 to 5?

**P1:** Definitely a 5. I use a lot of apps daily.

**Facilitator:** Have you ever reported a civic issue to authorities?

**P1:** Yes. Once I called the BBMP helpline about a pothole near my apartment. Nothing happened for three weeks. I also tweeted at the municipal account once about garbage not being collected. That actually worked faster, weirdly.

**Facilitator:** Have you used any civic or government apps before?

**P1:** I tried the BBMP app once but it was really slow and confusing. I gave up after two minutes.

**Facilitator:** What frustrates you most about reporting civic issues currently?

**P1:** You never know what happens after you report. Did someone receive it? Is anyone working on it? There's zero transparency. And having to call or email feels like shouting into a void.

**Facilitator:** What would make you more likely to report an issue if you had an app?

**P1:** If I could track it like a delivery — see exactly where it is in the process — I'd definitely use it. Also, if it was quick. I'm not writing a paragraph about a pothole.

**Facilitator:** Perfect. Let's begin the tasks.

---

## Task 1: Account Creation & Login

**Facilitator:** Imagine you just downloaded the Civic Snap app. You want to create an account using your phone number so you can start reporting issues. Go ahead and tell me what you'd do.

*[Facilitator places Landing Page screen in front of P1]*

**P1:** Okay, so I see "Civic Snap" with a logo that says [CS] and the tagline "Report city issues in seconds. Track resolution in real time." There are three steps shown: ① Snap photos, ② Auto Route, ③ Track & Verify. Two buttons: "Get Started" and "Sign In." I'd tap "Get Started."

*[Facilitator swaps to Phone Login screen]*

**P1:** Now it says "Civic Snap — Report city issues in seconds" at the top. There's a phone field with +91 and a number pre-filled: 78350 57890. Below that, a divider that says "— OR —" and then two buttons: "Google" and "Email." At the bottom it says "By continuing, you agree to our Terms & Conditions." I'd type my number... but wait, I don't see a "Continue" or "Next" button anywhere on this screen. Where do I tap after entering my number?

**Facilitator:** What would you expect?

**P1:** There should be a big button at the bottom — "Continue" or "Verify" or something. But it's just not here. I'd probably look for a button below the phone field, but there's nothing. This is confusing — I've entered my number and now I'm stuck.

*[Facilitator explains there should be a Continue button — noting this as a design issue]*

**P1:** Okay, so I'd tap Continue if it were there. It's straightforward conceptually — just phone number, no email, no password. Feels quick. But that missing button is a real problem. People would think the app is broken or they did something wrong.

*[Facilitator swaps to OTP Verification screen]*

**P1:** Now it says "Civic Snap" at the top with the subtitle "Verify phone." It says "6 digit code sent to +91XXX-90." Six boxes for the code: [1][2][3][_][_][_]. Below that, "Didn't receive code? Resend in 0:50." There's a "Verify & Continue" button and a "← Change Number" link.

**Facilitator:** What do you notice about this screen?

**P1:** The six code boxes are clear. I like the countdown timer — "Resend in 0:50" tells me exactly when I can request a new code. The "Change Number" link at the bottom is good in case I typed it wrong.

*[Facilitator swaps to Create Profile screen]*

**P1:** Now it says "Create Profile." Fields: Name with [XXX XXX], Age with [XX] and a dropdown arrow, Location with 📍 "Choose on map," and Email ID with [XX@X.X]. There's a "Continue" button.

**P1:** Wait — this screen has a "Continue" button! Why didn't the phone login screen have one? That's inconsistent. Anyway, I'd fill in my name, use the dropdown for age, tap "Choose on map" for location, and enter my email.

**Facilitator:** Good observation. I'll note that.

**Facilitator:** Anything confusing here?

**P1:** The location says "Choose on map" — do I pick it from a map or type it? And there's no photo upload at all — the wireframe just has Name, Age, Location, Email. That's actually simpler. But no photo means I can't add one even if I wanted to.

*[Facilitator swaps to Home Dashboard]*

**P1:** Now I'm on the home screen. It says "Welcome back Rahul……" at the top with a [Public] badge, a person icon, and a bell icon. Below that, a stats row: My Reports: 12, Karma Points: 247, Verified: 11. Then a section called "Quick Report" that says "Report any city issue in seconds" with an "AI Auto Tag" label. And a big button [+ New Report]. Below that, "Active Reports" with a "View All" link, and two cards: CS-01412 [In Progress] with an image — Water leak, and CS-01563 [Pending] with an image.

**Observations:**
- Confusion at phone login — no Continue button visible after entering number
- Understood OTP flow immediately once past login
- Asked about area input method (dropdown vs type)
- Questioned whether photo is mandatory
- Profile has no photo field in wireframe — can't add one even if wanted
- Positive overall impression after onboarding
- Home dashboard data clearly visible: stats, report cards, Quick Report section

---

## Task 2: Report a Pothole

**Facilitator:** You're walking home and notice a large pothole on your street. You want to report it through the app. Show me what you'd do.

**P1:** I'm on the home screen. I see "+ New Report" — that's the big action button. I'd tap that.

*[Facilitator swaps to Report Hazard screen]*

**P1:** Now it says "Civic Snap — Report Hazard" at the top. There's a "+ Click Image" button to take a photo. Below that, a section labeled "AI Auto Tags™" with three chips: [Auto Detect] [Routes List] [+ Add Tag]. Then a text field that says "Context / Add details: ………" and a "Submit Report" button at the bottom.

**Facilitator:** What are you thinking?

**P1:** The AI Auto Tags section is interesting — it shows "Auto Detect" and "Routes List" as tags. So the app automatically detects what the issue is and routes it? That's clever. But I notice the tag chips don't have X buttons on them. What if the AI gets it wrong? I can't remove an incorrect tag.

*[Facilitator points to the [+ Add Tag] button]*

**P1:** Oh, I can add my own tags with the "+ Add Tag" button. But I still can't remove the auto-detected ones. If the app says "Streetlight" for something that's clearly a pothole, my report could get routed to the wrong department. That's a problem.

**P1:** I'd write "Large pothole near the bus stop, about 2 feet wide" in the Context field and tap Submit Report.

*[Facilitator swaps to Submission Confirmation screen]*

**P1:** Big green checkmark. It says "Report Submitted — Your hazard report has been received & logged in the system." Ticket ID: #CS-2029-0857. And two buttons: [Track this Report] and [Report Another Issue].

**Facilitator:** How do you feel about this flow?

**P1:** Very satisfying. The report ID — #CS-2029-0857 — makes it feel official. And the AI auto-tagging is a neat idea, but not being able to remove wrong tags is a real issue. The flow is direct: photo, tags, details, submit. Quick.

**Observations:**
- Found "+ New Report" button immediately
- AI Auto Tags section understood but frustrated — no X button to remove incorrect tags
- [+ Add Tag] button noticed but removal of auto-tags impossible
- No category selection screen — goes straight to photo/tags
- Positive about report ID and submission confirmation

---

## Task 3: Check Report Status

**Facilitator:** You reported a broken streetlight last week. You want to check if it's been fixed. What would you do?

**P1:** I'm on the home screen. I see "Active Reports" with two cards: CS-01412 [In Progress] — Water leak, and CS-01563 [Pending]. I'd tap on the In Progress one.

**Facilitator:** Alternatively, what if you had many reports and didn't see it on the home screen?

**P1:** I'd look for a "My Reports" option. I'd tap "View All" next to Active Reports.

*[Facilitator swaps to My Reports screen]*

**P1:** Now I see "← My Reports" at the top with a search bar that says "🔍 Search your Reports." Two cards below: [In Progress] #CS-057 — Pothole on MG Road with an image placeholder and a [Track →] link, and [Resolved] #CS-058 — Broken Streetlight with a ✅ Verified by You badge.

**Facilitator:** Tap the In Progress one.

*[Facilitator swaps to Live Tracking screen]*

**P1:** This is the tracking screen. It says CS-[ID] at the top. I see a progress bar: Reported → BWSSB → On Site → Done. The "On Site" step is highlighted as the current one. Below that, it says "ETA: 28/March 2025." Then it shows "Agency: BWSSB" with a stop icon and "BWSSB" with a field report icon. There's a "View Activity Logs" link and a "Verify Repair" button. 

**Facilitator:** What do you think of this screen?

**P1:** This is exactly what I wanted — transparency. I can see exactly where my report is in the process: Reported → BWSSB → On Site → Done. The ETA gives me a timeline. And the agency information shows which department is handling it.

**P1:** One thing though — the screen has a lot of information. The activity log and field report sections are below the fold. I might not scroll down if I just want a quick status check. But the progress bar at the top is very clear — that's the first thing I see.

**Facilitator:** Good point. Is the main status clear at a glance?

**P1:** Yes, the progress bar at the top is very clear. That's the first thing I see.

**Observations:**
- Found My Reports via bottom nav easily
- Status color coding was immediately understood
- Progress bar was the standout feature
- Delay notice appreciated for transparency
- Screen felt information-dense — might benefit from progressive disclosure
- Activity log and agency tasks are below the fold

---

## Task 4: Verify a Fix

**Facilitator:** You receive a notification that the pothole you reported has been repaired. The app asks you to verify the fix. What do you do?

**P1:** I'd tap the notification. 

*[Facilitator swaps to Verify Repair screen]*

**P1:** The header says CS-[ID] and the title says "VERIFY REPAIR — Citizen Sign Off Required." That's clear — I need to confirm the fix. I see two image placeholders side by side labeled "Before" and "After." Below that, it says "GPS Locked: 2026-03-28 | Crew ID: 535 ER." So it shows me exactly when and where the repair was verified.

**Facilitator:** What would you do next?

**P1:** I'd compare the before and after photos. If the after photo looks good, I'd tap the "VERIFY" button. There's also a link that says "Not happy? Details" — that must be the dispute option.

**Facilitator:** What do you think about the dispute option?

**P1:** "Not happy? Details" is a bit vague. What happens when I click "Details"? Does it let me say why I'm unhappy? I'd want specific options — like "Wrong location" or "Temporary fix only" — not just a blank field.

**Facilitator:** Is the distinction between Confirm and Dispute clear?

**P1:** Yes. Confirm is green, Dispute is orange. The colors help. But I'd want a confirmation dialog before disputing — like "Are you sure you want to dispute this repair?"

*[Facilitator swaps to confirmation after tapping Confirm]*

**P1:** Now it says "Karma badge earned · +18 trust points added to your profile." That's a nice gamification touch. It makes me feel like my participation matters.

**Facilitator:** Would the karma system motivate you?

**P1:** Honestly, yes. It sounds silly but getting points and badges would make me want to report more issues and verify more fixes. It turns civic duty into something rewarding.

**Observations:**
- Verify Repair screen title clearly states "Citizen Sign Off Required"
- Before/After comparison was clear
- GPS lock + Crew ID added trust
- "Not happy? Details" link for disputes is vague — no confirmation dialog or reason selector
- Wanted specific dispute reasons and a confirmation dialog
- Karma/trust points were well-received
- Gamification seen as motivating, not childish

---

## Task 5: Browse Nearby Issues (Time Permitting)

**Facilitator:** You're curious about what other issues people in your area have reported. Show me how you'd browse them.

**P1:** On the home screen, I see "Nearby Issues" in the Quick Report section. I'd look for a map view.

*[Facilitator swaps to Public Reports Map screen]*

**P1:** I see a search bar that says "🔍 Search area or Issue" and a map with colored pins. Below the map, there are colored dots: ● Reported ● Pending ● Resolved — these are filters. And below that, a "Nearby Issues" section showing "Pothole MG Road" with an image and "Broken Streetlight" with an image.

**Facilitator:** Tap on one.

*[Facilitator swaps to Public Issue Detail screen]*

**P1:** It says "← Public Issue" at the top with an image placeholder showing a road. The title is "Pothole MG Road" with an "● In Progress" status badge. Below that, "Reported by: Priya S." and "2 hrs ago," then "📍 Church Street, MG Road, Ward 65, Bengaluru" and a description: "Large pothole near MG Road entrance…"

**P1:** I notice there's no personal data visible about who reported it beyond their first name and last initial. That's good for privacy.

**Observations:**
- Map view was intuitive
- Color-coded pins were understood immediately
- "Support This Report" feature was well-received
- Public info felt appropriate — no personal data visible

---

## Task 6: View Notifications

**Facilitator:** You want to check if there are any updates on the reports you've submitted. Show me how you'd look at your notifications.

**P1:** On the home screen, I see a bell icon 🔔 in the top right with a red dot on it. I'd tap that.

*[Facilitator swaps to Notifications screen]*

**P1:** Okay, this says "← Notifications" at the top with a "Mark All Read" link on the right. Below that, grouped by date. Under "Today": "Report CS-2024-0849 was updated · 2 hrs ago." Under "24/01/2026": "Report CS-2025-0689 was marked resolved · 29/01/24 4:30" and "Report CS-2025-0689 awaiting your feedback."

**Facilitator:** What would you tap on?

**P1:** The one about awaiting my feedback — that sounds like it needs action from me. I'd tap that one and go to the verification screen, like we just did in the earlier task.

**Facilitator:** What do you think of the notification screen overall?

**P1:** It's clean and organized. The grouping by date helps. The red dot on the home screen icon is a good visual cue that I have unread notifications. But I notice it only shows text — no preview images or icons for the notification type. It might be helpful to have small icons showing whether it's an update, a resolved report, or an action item.

**P1:** Also, I'd want to be able to swipe to dismiss individual notifications, not just "Mark All Read." And maybe a filter — show only notifications that need my action, like verification requests.

**Observations:**
- Found notifications via bell icon immediately
- Understood date grouping
- Prioritized action-oriented notifications (verification requests)
- Wanted notification type icons/visual differentiation
- Suggested swipe-to-dismiss and filtering by action-needed
- "Mark All Read" understood immediately

---

## Task 7: View & Edit Profile

**Facilitator:** You want to update your profile information, like your area or photo. Show me how you'd get to your profile and what you'd change.

**P1:** On the home screen, I see a person icon 👤 next to the bell. I'd tap that.

*[Facilitator swaps to Profile screen]*

**P1:** Now I'm on the profile screen. It says "← [A] Ayush Patel | Indiranagar" at the top. Below that: ⭐ 1250 Karma Points. Then stats: "23 Reports | 18 Resolved." Below that, menu items: [My Reports] [Notification & Billing]. And a [Sign Out] button at the bottom.

**Facilitator:** Where would you go to edit your information?

**P1:** I'd look for an "Edit Profile" or a pencil icon... I see menu items below: [My Reports] and [Notification & Billing]. But I don't see an obvious "Edit Profile" button. Maybe I tap on the [A] avatar at the top? Or is there a settings gear?

**Facilitator:** What would you expect?

**P1:** I'd expect a clear "Edit Profile" button somewhere prominent. Either a pencil icon next to my name, or an "Edit" button near the top. Without it, I'm not sure how to change my area or name.

*[Facilitator points out the avatar area]*

**P1:** Oh, I could tap on the [A] avatar to change it. That's a bit hidden — not everyone would guess that. And for changing my area, I'm not sure where that option is.

**Facilitator:** How about the karma section?

**P1:** 1250 Karma Points with the star is clear. And the stats — 23 Reports, 18 Resolved — give me a quick overview of my activity. But what do the karma points actually do? Is it just a number, or does it give me something? There's no explanation here.

**P1:** Oh, I see there's a "Sign Out" button at the bottom. That's pretty definitive. No confusion there.

**Observations:**
- Found profile via person icon
- Karma points visible but meaning unclear
- Edit profile path was not obvious — no visible "Edit" button
- Expected pencil icon or dedicated edit button
- Suggested tap-on-photo pattern is hidden
- Sign out was clear and accessible
- Wanted explanation of karma system benefits

---

## Task 8: Field Worker — View & Complete Task

**Facilitator:** Now I'd like you to switch roles. You're a field worker named Ramesh who works for BBMP. You've been assigned a task — a broken manhole cover on 12th Main, Indiranagar. Show me how you'd start and complete this task.

*[Facilitator places Field Worker Login screen]*

**P1:** Okay, this is a different app — "Civic Sende — Field Worker Portal." It wants an Employee ID field with [X X X X] and a Department dropdown that says [Select Department ▼]. No phone number login this time. I'd type my employee ID and select my department.

*[Facilitator swaps to Field Worker Dashboard]*

**P1:** Now I see "Hi Ramesh! | My Work" at the top. Stats: 2 High Priority | 2 Medium | 1 Completed. Below that, task cards. The first one says "[High Priority] SLA-2hr — Broken Manhole Cover, Indiranagar, 12th Main | #TK-4521 | [Start]." And a second: "[High Priority] SLA-6hr — Water Pipe Burst | [Start]."

**Facilitator:** What do you notice?

**P1:** The SLA timer is prominent — 2 hours for a high priority task. That's tight. The second task also has an SLA of 6 hours. The priority badges are color-coded which matches what I saw in the citizen app.

*[Facilitator swaps to Task Details screen]*

**P1:** Task details. It says "← Task Details | #TK-4521 | [High Priority]" at the top. Title: "Broken Manhole Cover." Two image placeholders for before and after. Description: "Large Manhole Cover Missing." Location: 📍 Indiranagar with a map pin. Button: [Complete].

**P1:** The map is useful for navigation. I'd go to the location, take a before photo, do the work, take an after photo, then submit.

*[Facilitator swaps to GPS Checkout screen]*

**P1:** GPS Checkout screen. Header: "← GPS Checkout | #TK-4521." It says "GPS → Verified: Indiranagar, 12th Main." Then "Before Photo: [↑ Upload Photo]" and "After Photo: [↑ Upload Photo]." Below that, "Notes (Optional): [text field]" and a "Submit Checkout" button.

**P1:** The GPS verification is smart — it confirms I'm actually at the location. I can't just submit from home. The notes field being optional is good — sometimes there's nothing extra to say.

**Facilitator:** Anything surprising about this portal?

**P1:** The flow is straightforward — login, see tasks, start a task, go to location, submit completion with proof. No unnecessary steps. The SLA timers add urgency. Compared to the citizen app, this feels more task-focused, which makes sense for workers.

**P1:** One thing — I don't see a way to flag a problem. Like, what if I get to the location and the issue is already resolved? Or what if it's worse than described? Can I report back that the description doesn't match reality?

**Observations:**
- Understood field worker login immediately (Employee ID + Department)
- Dashboard stats and SLA timers were clear and added urgency
- Task details with map and photos intuitive
- GPS verification appreciated for accountability
- Wanted ability to flag discrepancies between report and actual issue
- Notes field being optional was appreciated
- Flow described as straightforward and task-focused

---

## Task 9: Government Official — Review Reports & Assign Tickets

**Facilitator:** One more role. You're a government official at the BWSSB office. You need to review incoming reports and assign a ticket to a field worker. I'll show you the paper screens.

*[Facilitator places Government Official Login screen]*

**P1:** Another different login — "Civic Snap — Official Portal." It asks for Office Email ID [text field], Department [Select ▼], and Password [● ● ●]. Three fields. More secure than the citizen or field worker logins, which makes sense for government accounts.

*[Facilitator swaps to Government Dashboard]*

**P1:** The dashboard says "Hello BWSSB Office" with stats: 12 Critical | 28 Pending | 156 Resolved. Below that, there's a heatmap grid with shaded cells. And below that, "Reported Queue [See All]" with a card: "[High Priority] SLA-2hr — Manhole Opened #TK-4521."

**P1:** The heatmap is interesting — I can see which wards have the most issues. Darker areas mean more reports. This is useful for resource allocation.

*[Facilitator swaps to Reports Queue]*

**P1:** A list page that says "Reports ——— [+ Create Manual]" at the top. Three cards: Card 1 "[High Priority] — Manhole Open 📍 Indiranagar" with [Assign] [Details] buttons. Card 2 "[Medium Priority] — Garbage 📍 MG Road" with [Assign] [Details]. Card 3 "[Medium Priority]" with just an [Assign] button.

*[Facilitator swaps to Assign Ticket screen]*

**P1:** "← Assign Tickets | #TK-0591" at the top. Employee Name field with [🔍 Search Name] and a Note text area. Button: [Assign].

**P1:** But I notice this screen only has a name search. I don't see any information about the worker — how many tasks they have, what their current workload is, or if they're even available. Just searching by name isn't enough for smart assignment. I'd need to see their status.

*[Facilitator swaps to Ticket Details screen]*

**P1:** "← Ticket Details | #TK-0591 | [User Details]" at the top. Two image placeholders for before/after, title "Manhole Opened," location 📍 Indiranagar, description area, and progress showing "● Reported → ● BWSSB Assigned."

**P1:** The progress bar shows me where the ticket is in the process. The "User Details" link is useful — I can see who reported the issue and contact them if needed.

*[Facilitator swaps to User Details screen]*

**P1:** "User Details | #TK-059" at the top. It shows Name: Rajesh, Phone Number: XXX-XXX, Email: X@.com, Location: Whitefield, Karma Points: 1250. Buttons: [Message] [Call]. And a link: "Report User !"

**P1:** Karma points here is interesting — 1250. That tells me this is an active, trusted reporter. Higher priority for high-karma reports makes sense.

*[Facilitator swaps to Create Manual Ticket screen]*

**P1:** "← Create Manual Ticket" at the top. Location field with [🔍 Search Location], Images [↑ Upload Img], Priority buttons: [High] [Medium] [Low], Description text area, and a [Create] button. This is for when someone calls in an issue by phone instead of using the app.

**Facilitator:** What do you think of this government portal overall?

**P1:** It's functional. The heatmap and stats give a good overview. The ticket assignment could be better with worker availability info. The manual ticket creation is clean. My main concern would be: in a real scenario, there could be hundreds of reports. The queue needs filtering — by priority, by area, by department.

**Observations:**
- Understood secure three-field login for official portal
- Dashboard stats and heatmap functional but heatmap needs a legend
- Wanted worker workload/context in assignment screen
- Liked User Details with karma points for trust assessment
- Manual ticket creation straightforward
- Suggested filtering for the reports queue (priority, area, department)
- Consistent design language with citizen and field worker apps noted

---

## Post-Interview

**Facilitator:** Which task was the easiest?

**P1:** Reporting the pothole was easiest. The flow was very guided.

**Facilitator:** Which was hardest?

**P1:** Probably the tracking screen. It had a lot of information. Not hard to understand, just dense. I'd want a simplified view and a detailed view.

**Facilitator:** Was there any screen where you weren't sure what to do?

**P1:** The profile setup screen — I wasn't sure if the photo was required. And the area field — is it a dropdown or free text?

**Facilitator:** Did any label or icon confuse you?

**P1:** The "Digital Handshake" term in the tracking screen. I didn't know what that meant at first. I had to read the context to figure it out.

**Facilitator:** How did you feel about the number of steps to report an issue?

**P1:** It's fine. Five steps but each is quick. I'd say it takes about 60-90 seconds total, which is acceptable.

**Facilitator:** Did you understand what happens after you submit?

**P1:** Yes. The confirmation screen made it clear — report ID, status, estimated time. And I can track it.

**Facilitator:** Now I'll ask you to rate some statements from 1 to 5...

*[SUS questionnaire administered — scores recorded]*

**SUS Responses:**
| # | Statement | Score |
|---|-----------|-------|
| 1 | I think I would like to use this app frequently | 5 |
| 2 | I found the app unnecessarily complex | 2 |
| 3 | I thought the app was easy to use | 5 |
| 4 | I think I would need technical support | 1 |
| 5 | Functions were well integrated | 4 |
| 6 | Too much inconsistency | 1 |
| 7 | Most people would learn quickly | 5 |
| 8 | App was cumbersome | 1 |
| 9 | I felt confident using the app | 5 |
| 10 | Needed to learn a lot before getting going | 1 |

**SUS Score Calculation:**
- Odd: (5-1) + (5-1) + (4-1) + (5-1) + (5-1) = 4+4+3+4+4 = 19
- Even: (5-2) + (5-1) + (5-1) + (5-1) + (5-1) = 3+4+4+4+4 = 19
- Total: 38 × 2.5 = **95/100**

**Facilitator:** If you could change one thing, what would it be?

**P1:** Make the tracking screen less dense. Maybe show just the progress bar and status by default, with an option to expand for details.

**Facilitator:** Would you trust this app with your location data?

**P1:** Yes, because it needs my location to report issues. But I'd want to know it's only used for that purpose and not shared with third parties.

**Facilitator:** Would you recommend it to a friend?

**P1:** Absolutely. If this app actually works and the government responds, it would be a game-changer.

**Facilitator:** Any additional comments?

**P1:** The karma system is clever. And the transparency in tracking is exactly what's missing from current systems. I'd love to see this become real.

---

## Facilitator Notes

**Overall Impression:** P1 was highly engaged and positive throughout. As a tech-savvy user, they moved through tasks quickly. Key concerns were about information density on the tracking screen and clarity on the profile setup form.

**Key Quotes:**
- "This is exactly what I wanted — transparency."
- "If this app actually works and the government responds, it would be a game-changer."
- "The karma system is clever."

**Top Issues Identified:**
1. **No Continue button on login page** — After entering phone number, P1 could not find a Continue button and was stuck. Critical blocking issue.
2. **Tracking screen too dense** — Overwhelmed with information. P1 and P2 both found the tracking screen had too much data at once, needed progressive disclosure (simple view + detailed view).
3. **Tag editing — no way to remove** — AI auto-detected tags appeared as chips with no X/cross button. If the AI misidentified an issue, users had no way to remove incorrect tags before submission.
4. **No dispute flow — no confirmation, no reason selector** — P1 wanted a confirmation dialog before disputing ("Are you sure?") and the ability to specify dispute reasons (e.g., "Wrong location"). No such flow existed in the paper prototype.

**Session Rating:** Very positive. High SUS score (95). Participant would use and recommend the app across all three roles.
