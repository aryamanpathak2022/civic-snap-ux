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

**P2:** Okay, I see the app name and a "Get Started" button. I'll tap that.

*[Facilitator swaps to Login screen]*

**P2:** It wants my phone number. There's a country code already set to +91, which is good. I'll type my number...

*[P2 types number, then pauses]*

**P2:** I've entered my number, but... where's the Continue button? I don't see any button to proceed. I'd expect a "Continue" or "Next" or "Verify" button right below the phone field, but there's nothing there.

**Facilitator:** What would you do?

**P2:** I'd probably tap somewhere else on the screen to see if the button appears, or I might think something is broken. It's confusing — the most important button on this screen is missing. I'd eventually figure there should be a button and ask someone or try scrolling down.

*[Facilitator notes the missing Continue button as a design issue]*

**P2:** Assuming the button was there, I'd tap Continue. The flow is simple conceptually — just phone number, no email, no password. But that missing button is a real problem. People would think the app is broken or that they did something wrong.

**Facilitator:** Good question. Let's continue.

*[Facilitator swaps to OTP screen]*

**P2:** Now it's asking for a 6-digit OTP. I see six boxes and a timer. I'd enter the code. There's a "Resend OTP" option which is useful — sometimes SMS takes time.

**Facilitator:** Anything you notice or wonder about?

**P2:** The "Change phone number" link at the bottom — that answers my earlier question. So I can go back if I entered the wrong number. Good.

*[Facilitator swaps to Profile Setup]*

**P2:** Now it wants my name, area, and a profile photo. I'd fill in my name. For area, I'd... hmm, is this a list I choose from or do I type? It's not clear. And the photo — do I need to upload one? I'd rather skip it if I can.

**Facilitator:** What would you expect?

**P2:** I'd expect the area to be auto-detected from my phone's location, or at least a dropdown with my ward name. And the photo should be optional — not everyone wants their face on a civic app.

*[Facilitator swaps to Home Dashboard]*

**P2:** Now I'm on the home screen. I see my name, some quick actions, and a section called "Active Reports." It's empty right now since I haven't reported anything. The layout is clean.

**Facilitator:** How did you feel about the onboarding?

**P2:** It was straightforward. Four steps is reasonable. My only concern is the profile photo — it should clearly say "optional." And the area field needs to be clearer about how to input it.

**Observations:**
- Confusion at phone login — no Continue button visible after entering number
- Asked about changing phone number later (found the link)
- Confused about area input method
- Strong preference for optional profile photo
- Wanted auto-detect for area/ward
- Clean layout appreciated

---

## Task 2: Report a Pothole

**Facilitator:** You're walking home and notice a large pothole. Report it through the app.

**P2:** On the home screen, I see "Report Issue" as the biggest button. I'd tap that.

*[Facilitator swaps to Report screen]*

**P2:** Now I see categories. Road Damage, Streetlight, Garbage, Water Issue. I'd tap Road Damage. The icons help — I can see a road with a crack.

**Facilitator:** What are you thinking?

**P2:** The categories cover most common issues. But what if my issue doesn't fit any category? I see there's an "Other" option at the end. That's good.

**P2:** Now it's asking for a photo. I'd take a picture. There's a note saying "AI auto-tags" — so the app figures out what the problem is from the photo?

**Facilitator:** Yes, that's the idea.

**P2:** That's impressive if it works well. But I'd want to verify what it detected. What if it misidentifies the problem?

*[Facilitator shows auto-detected tags]*

**P2:** Okay, so it shows tags like "Pothole," "Road Crack," "Surface Damage" as chips. But... I don't see an X or close button on these chips. If it says "Streetlight" for a pothole, how do I remove that? I can't just tap them to dismiss — there's no way to remove wrong tags. This is a significant problem. I should be able to remove any tag the AI got wrong before I submit my report.

**Facilitator:** What would you expect?

**P2:** Each tag chip should have a small X button so I can remove ones that are incorrect. Like how you remove filters on shopping apps. I'd also want to add my own tags, but fixing wrong AI tags is the priority. Without that control, my report could get routed to the wrong department.

**P2:** Now there's a section for optional details. I'd write "Large pothole, about 2 feet wide, near the bus stop on 80 Feet Road." And then there's a location button — "Use Current Location." I'd tap that.

**Facilitator:** What about the map?

**P2:** I see a small map preview with a pin. I can drag the pin if the location isn't accurate. That's useful — sometimes GPS is off by a few meters.

**P2:** At the bottom, there's a "Submit Report" button. And a small note about anonymous reporting. I almost missed that — it's quite small.

**Facilitator:** Would you use anonymous reporting?

**P2:** For a pothole, no. But for something like illegal construction or encroachment, yes. I'd want the option to be more visible though. Maybe a toggle switch instead of small text.

*[Facilitator swaps to Confirmation screen]*

**P2:** "Report Submitted!" with a report ID — CS-2026-0847. Status is "Received" and it says "Estimated response: 48 hours." I can track the report or go back home.

**Facilitator:** How do you feel?

**P2:** Satisfied. The report ID makes it feel official. The 48-hour estimate sets expectations. I like that I can track it right away. The whole process felt like it took about 2 minutes, which is acceptable.

**Observations:**
- Found Report Issue button immediately
- Appreciated "Other" category option
- AI auto-detected tags have no X/cross button — can't remove incorrect tags (critical issue)
- Wanted ability to add custom tags as secondary need
- GPS location step was clear
- Map pin adjustment appreciated
- Anonymous reporting toggle too small/subtle
- Report ID and ETA were confidence-builders
- Overall flow felt well-paced

---

## Task 3: Check Report Status

**Facilitator:** You reported a broken streetlight last week. Check if it's been fixed.

**P2:** On the home screen, I see "Active Reports" but I'm not sure if the streetlight would show there since it was last week. Let me check the bottom navigation. I see "Home," "Reports," "Map," "Notifications," "Profile." I'd tap "Reports."

**Facilitator:** Good. What do you see?

*[Facilitator swaps to My Reports screen]*

**P2:** I see a list of my reports. Each one has a colored badge — green, yellow, red. The streetlight one has a yellow badge saying "In Progress." I'd tap on it.

**Facilitator:** What do the colors mean to you?

**P2:** Green means done, yellow means happening, red means waiting or urgent. That's pretty standard — like traffic lights. Easy to understand.

*[Facilitator swaps to Live Tracking screen]*

**P2:** Okay, this is the tracking screen. I see a progress bar at the top with stages. The streetlight is at "In Progress." Below that, there's a yellow notice saying "Awaiting materials for electrical repair. ETA shifts to March 20."

**Facilitator:** What do you think?

**P2:** The progress bar is very clear — I can see exactly where things stand. The delay notice is honest, which I appreciate. But... there's a lot more below. I see "Activity Log" and "Agency Tasks." That's a lot of information on one screen.

**Facilitator:** Is it overwhelming?

**P2:** Not overwhelming, but dense. I'm someone who likes to see everything, so I'd scroll through it all. But my wife, who's less tech-savvy, might find it confusing. Maybe there should be a simple view and a detailed view.

**Facilitator:** What would the simple view show?

**P2:** Just the progress bar, current status, and estimated completion date. That's what most people care about. The detailed view can have the activity log, agency tasks, and all the technical details.

**P2:** One more thing — I see "Stage-gates" at the top. What does that mean? I had to read the context to understand it's like checkpoints in the process. The term itself isn't very citizen-friendly.

**Facilitator:** Good feedback. What about "Digital Handshake"?

**P2:** Same thing. It sounds technical. I'd prefer something like "Field Worker Tasks" or "What's Being Done."

**Observations:**
- Used bottom nav "Reports" tab (not "My Reports" label)
- Color-coded status badges instantly understood
- Progress bar was the clearest element
- Delay notice appreciated
- Screen too information-dense for average users
- "Stage-gates" and "Digital Handshake" terminology too technical
- Suggested simple vs. detailed view toggle

---

## Task 4: Verify a Fix

**Facilitator:** You get a notification that the pothole has been repaired. The app asks you to verify. What do you do?

**P2:** I'd tap the notification.

*[Facilitator swaps to Verify Fix screen]*

**P2:** I see two photos side by side — before and after. The before shows the pothole, the after shows it filled. Below, there's GPS coordinates and a timestamp. I'd compare the photos carefully.

**Facilitator:** What would you do next?

**P2:** If the after photo looks good, I'd tap "Confirm Fix." If not, "Dispute." The buttons are big and clear.

**Facilitator:** What do you think about the dispute option?

**P2:** There's a note saying disputes trigger a supervisor review within 24 hours. That's reassuring. But I'd want a confirmation popup before disputing — like "Are you sure?" Because disputing probably creates extra work for someone.

**Facilitator:** What if the after photo doesn't match the location?

**P2:** That's a good question. The GPS and timestamp help, but what if the field worker took a photo of a different pothole that was already fixed? I'd want to be able to flag that specifically — like "Wrong location" as a dispute reason.

**Facilitator:** That's a great insight.

*[Facilitator swaps to confirmation after Confirm]*

**P2:** Now it says "Karma badge earned · +18 trust points." That's a nice touch. It makes me feel like I contributed something.

**Facilitator:** Would the karma system motivate you?

**P2:** Honestly, yes. It's a small thing but it makes civic participation feel rewarding. I'd probably check my karma score occasionally. It's like a credit score for being a good citizen.

**Facilitator:** Is the karma concept clear?

**P2:** Mostly. But I'd want to know what the points mean. Can I redeem them? Do they give me any status? Or is it just for show? A small info icon explaining the karma system would help.

**Observations:**
- Before/after comparison intuitive
- GPS + timestamp built trust
- Wanted confirmation dialog before disputing
- Suggested specific dispute reasons (e.g., "Wrong location")
- Karma system well-received but needed explanation
- Compared karma to "credit score for being a good citizen"

---

## Task 5: Browse Nearby Issues

**Facilitator:** You're curious about issues others have reported nearby. Browse them.

**P2:** On the home screen, I see "Nearby Issues" with a "Map View" link. I'd tap that.

*[Facilitator swaps to Map View]*

**P2:** I see a map with colored pins. Red, yellow, green — matching the status colors I already learned. I'd tap a red pin.

*[Facilitator swaps to Public Issue View]*

**P2:** I see the issue details — type, location, date, status, and a photo. There's no personal information about who reported it, which is good for privacy. And there's a "Support This Report" button.

**Facilitator:** What does that do?

**P2:** I'm guessing it's like an upvote — if many people support the same issue, it gets higher priority. That's smart. It helps the government understand which issues affect the most people.

**Facilitator:** Anything confusing?

**P2:** The map is a bit cluttered when there are many pins. I'd want a filter — like show only unresolved issues, or filter by category. Also, I can't tell from the pin what type of issue it is without tapping. Maybe different shapes for different categories?

**Observations:**
- Map navigation was intuitive
- Color consistency with status badges appreciated
- Privacy respected — no personal info visible
- "Support This Report" feature well-understood
- Map clutter concern with many pins
- Suggested category-based pin shapes or filters

---

## Task 6: View Notifications

**Facilitator:** You want to check if there are any updates on your submitted reports. Show me how you'd look at your notifications.

**P2:** On the home screen, I see a bell icon with a red dot in the top right. That usually means I have notifications. I'd tap that.

*[Facilitator swaps to Notifications screen]*

**P2:** This is the notifications screen. It says "Notifications" at the top and there's a "Mark All Read" button. The notifications are grouped by time — "Today" and then older dates.

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

**P2:** On the home screen, I see a profile icon in the top right. I'd tap that.

*[Facilitator swaps to Profile screen]*

**P2:** This is my profile. I see my name "Priya Sharma," my area "Indiranagar," and a big karma section. It says 1250 Karma Points with a star. Below that, there are stats: 23 Reports, 18 Resolved. That's a quick summary of my activity — I like that.

**Facilitator:** How would you edit your information?

**P2:** Hmm, I'm looking for an "Edit" button... I don't see one. There's no pencil icon, no "Edit Profile" link. I'd expect it near my name or photo. Maybe I'm supposed to tap on my photo to change it? That's not very obvious.

**Facilitator:** What would you expect?

**P2:** I'd expect a clear "Edit Profile" button, probably near the top. And for specific fields, I'd expect to tap on each one — like tapping on my area to change it, tapping on my name to edit it. But none of that is indicated here.

**P2:** Menu items below show "My Reports" and "Notification & Billing." And there's a "Sign Out" button at the bottom. But no edit option for my profile itself.

**Facilitator:** What about the karma points?

**P2:** 1250 points is nice, but what does it mean? Is it just a score? Can I redeem it? Does it give me priority? There should be a small info icon or link explaining what karma points do. I'd want to know if being a high-point user means my reports get handled faster.

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

**P2:** This is a different login — "Civic Sende — Field Worker Portal." It wants Employee ID and Department. I'd type my employee ID and select my department from the dropdown.

*[Facilitator swaps to Field Worker Dashboard]*

**P2:** "Hi Ramesh! | My Work" at the top. I see priority stats: 2 High, 2 Medium, 1 Completed. The task cards below show High Priority first with an SLA timer — 2 hours. That's urgent. Task #TK-4521 with a "Start" button.

**Facilitator:** What do you notice about the task cards?

**P2:** The priority badges are clear — red for high. The SLA timers help me understand urgency. I can see the task title and location at a glance before even opening it.

*[Facilitator swaps to Task Details screen]*

**P2:** Task details. "Broken Manhole Cover" title, High Priority badge, two photo areas, description that says "Large Manhole Cover Missing," and a map showing Indiranagar location with a pin. I can see exactly where I need to go. There's a "Complete" button at the bottom.

**P2:** The photo areas — one says "Before" and one says "After." That makes sense. I take a photo when I arrive and one when I finish.

*[Facilitator swaps to GPS Checkout screen]*

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

**P2:** "Civic Snap — Official Portal." It asks for Office Email ID, Department dropdown, and Password. Three fields instead of one. I'd fill these in and tap Login.

*[Facilitator swaps to Government Dashboard]*

**P2:** "Hello BWSSB Office" with stats: 12 Critical, 28 Pending, 156 Resolved. That's a lot of information at a glance, which is good for a manager. Below that, a heatmap. I'm not sure I understand this right away — what do the darker areas mean?

**Facilitator:** What would you guess?

**P2:** I'd guess darker means more issues in that area. But a legend would help — like "darker = more reports" somewhere visible. Without one, I'm guessing.

*[Facilitator swaps to Reports Queue]*

**P2:** Reports queue. Multiple cards with priority badges, titles, locations, and "Assign" and "Details" buttons. I'd look for the highest priority one first.

**P2:** But with many reports, this list will get long. I'd want filters — by priority, by area, by date. Scrolling through everything isn't efficient when you have hundreds of reports.

*[Facilitator swaps to Assign Ticket screen]*

**P2:** Assign Tickets. Search for Employee Name and add a Note. I'd search for a worker and assign the ticket.

**P2:** But I don't know which worker to assign. The search just gives me names. I need to see their current workload, what area they cover, how many tasks they already have. Just a name search isn't enough for smart decisions.

*[Facilitator swaps to Ticket Details screen]*

**P2:** Ticket Details for #TK-0591. Before/after photos, title "Manhole Opened," location pin, description, and progress showing "Reported → BWSSB Assigned." And there's a "User Details" link.

*[Facilitator swaps to User Details screen]*

**P2:** User Details shows the citizen's info — name, phone, email, location, karma points (1250). "Message" and "Call" buttons for contact. And a "Report User" link for flagging misuse. Good — I can reach out to the citizen if I need more details.

**P2:** The karma points here are useful. If someone has 1250 points, they're a trusted, active reporter. If it's low, maybe the report is less reliable. It helps me prioritize.

*[Facilitator swaps to Create Manual Ticket screen]*

**P2:** Create Manual Ticket. Location search, image upload, priority buttons (High, Medium, Low — good, not a dropdown), and description. And a "Create" button. This is for phone-in reports from citizens who don't use the app.

**P2:** The priority buttons are clear — I can see all three options without opening a dropdown. For an older person like me, that's helpful. Bigger touch targets.

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

**P2:** The profile setup — the area field and photo requirement were unclear. And on the tracking screen, terms like "Stage-gates" and "Digital Handshake" were confusing.

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
