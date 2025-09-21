# Week 14 (September 15 - September 21, 2025)

## Overview
Resolved JWT mix-ups blocking attendance analytics and leaderboard data in the mobile app, then refined the layout of all related measurement, gym, and attendance screens.

## Day-by-Day Summary
- **Day 1 (Mon Sep 15):** Fixed the attendance analysis requests by ensuring the client JWT token was used when fetching streak status, total attendance dates, and preference data from the coach backend.
- **Day 2 (Tue Sep 16):** Corrected the leaderboard API calls to send the client token instead of the coach token when requesting attendance standings.
- **Day 3 (Wed Sep 17):** Validated the leaderboard authentication fix across the mobile flows to confirm all leaderboard data loads with the client JWT.
- **Day 4 (Thu Sep 18):** Polished the /measure and /measures/history screens, tightening spacing and aligning typography for the refreshed layout.
- **Day 5 (Fri Sep 19):** Updated the /gyms screen styling to match the new layout patterns and improve hierarchy.
- **Day 6 (Sat Sep 20):** Refined the /attendance and /leaderboard screens with consistent padding, colors, and responsive behavior.
- **Day 7 (Sun Sep 21):** Off.
