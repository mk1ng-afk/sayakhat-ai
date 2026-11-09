# Sayakhat AI — MVP (version 2)

Working prototype of Sayakhat AI, a planner that builds three domestic trips in Kazakhstan around a group's budget and shows the full price per person.

Course project, Technological Entrepreneurship, Astana IT University. Group CS-2422: Sadykbek Miras, Kairat Sultan.

## What it does
- Input: group budget, number of people, days, departure city (Almaty / Astana), date, interests.
- Output: three trips with a day plan, price breakdown by partner, refund rules and price per person.
- "How many are going?" control recalculates each person's share.
- Rule-based assistant edits the plan ("cheaper", "no hikes", "250k", "5 of us", "for 3 days").
- Choosing a trip gives a group-chat message and a booking request (saved only in the browser).
- Non-standard cases: invalid input is explained; if no trip fits the budget, the page offers fixes.

## Technical overview
- Single HTML file with CSS and plain JavaScript; no framework, no server.
- Sample data (10 destinations, illustrative partners and prices) is stored inside index.html.
- Booking requests: browser localStorage. Test data: a feedback line copied by the tester.
- Hosting: GitHub Pages.

## Not available yet
Real partner prices and availability, sending requests to partners, online payment, accounts, reviews, a language-model assistant.
