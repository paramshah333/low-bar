# Low Bar

A ten second daily check-in for people who have tried habit apps and dropped them.

Most habit apps run on streaks, so one bad day can feel like losing everything. Low Bar asks how today is going and shrinks five basic habits (move, water, food, mind, sleep) to match. Every size of effort counts the same. There are no streaks, no guilt and no lost progress.

**Try it:** open the live link, or add `#sample` to the end of it to open two sample weeks straight away.

## What it does

- **Four levels, four list sizes.** Good, Okay, Low and Rough each have their own version of every habit, from "20 minute walk or workout" down to "Stand up and stretch once".
- **Make it even smaller.** Any habit can drop one more step for the rest of the day and still counts when ticked.
- **Days you showed up.** The last 14 days as circles. A rough day fills in exactly like a good one.
- **This week.** Days showed up, the level picked most often, and the last three end-of-day notes.
- **Built for coming back.** After a gap of two or more days it says "Welcome back. There is nothing to catch up on." After three heavy days in a row it shows one quiet note suggesting a trusted person or a doctor.
- **Sample weeks.** Reviewers can see the return and pattern logic without waiting days. Sample data is never saved and never touches real check-ins.

## How it is built

One self-contained HTML file with no build step and no dependencies. Data stays in the browser's localStorage, uses local dates so the day rolls over at midnight in India, and the app still works if storage is blocked. It supports light and dark mode, reduced motion, keyboard use and screen readers.

## How AI helped

I wrote the product spec, copy and acceptance tests, and used Claude to write the code, run the tests in a headless browser and record the demo.

Everyday wellbeing habits, not medical advice.
