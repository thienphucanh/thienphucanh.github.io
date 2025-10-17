# Study Compass

Study Compass is a single-page web application for planning and tracking study sessions directly in your browser. It stores your sessions in local storage so you can log time spent, categorize topics, and watch your streaks grow without creating an account.

## Getting Started
1. Open `index.html` in any modern desktop or mobile browser.
2. Use the **Plan a Session** panel to add a subject, focus area, target duration, and notes.
3. Mark sessions complete when you finish them to update your streak, totals, and weekly goal progress.
4. Use the filters at the top of the schedule to sort by date, status, or subject.

All data lives in your browser, so exporting and importing the JSON backup periodically is a good idea if you switch devices.

## Ideas for What to Do Next
If you want to build on top of the current experience, here are a few directions you can explore:

- **Improve analytics** – calculate trend lines, highlight your most productive hours, or add charts with a lightweight library such as Chart.js.
- **Add reminders** – integrate with the Web Notifications API or calendar exports so upcoming sessions trigger alerts.
- **Collaborative planning** – move storage from local storage to a small backend (Firebase, Supabase, etc.) so you can share schedules with classmates.
- **Focus mode** – create a dedicated timer page that starts a countdown and blocks distracting sites using the Screen Wake Lock API.
- **Mobile optimizations** – audit the layout on smaller screens, add installable PWA support, and cache assets for offline use.

These enhancements can be implemented incrementally—pick the area that excites you most and iterate from there.
