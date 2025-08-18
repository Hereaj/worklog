# worklog

This repository tracks progress from my Autosterea Software Engineering internship. Below is a summary of the major tasks completed each week.

## Tools Learned
- Replit
- Lovable
- Codex OpenAI
- Cursor
- WindSurf
- Built and deployed custom MCP servers (travel-route, aurora-alert) in local and virtual HTTP environments.
- React Native
- Expo Router
- Expo Go
- EAS CLI (Expo Application Services)
- TestFlight & App Store Connect
- App Store release/update process
- Google Play Store release with EAS
- GPT-5 model exploration in IDEs such as Lovable and Cursor
- CSV parsing and beta feedback workflows

## Projects
- **Resume app:** enhanced with AI-assisted planning and debugging.
- **EDSO workout calendar:** application for coaches to manage programs and assign workouts to clients. Supports full CRUD operations for tracking workouts.
- **Restap app:** React Native timer for tracking rest intervals between workout sets.
- **Travel-route MCP server:** personalized routes validated in local and virtual environments.
- **Aurora-alert MCP server:** predicts auroras using NOAA data and HTTP deployment.

## Workflow Highlights
- Used agent tools, Lovable and Replit, concurrently to optimize both frontend and backend development.
- Developed detailed plans with Codex and iterated on improvements.
- Implemented solutions, fixed problems, and debugged tests with AI assistance.
- Finalized the class attendance feature and introduced biometric login for the mobile app.
- Streamlined the release cycle for iOS and Android using EAS for App Store and Google Play.
- Built gym entity and the Restap app to manage clients by gym and track rest times.
- Resolved git merge conflicts and created a testbed gym for universal client testing.
- Developed personalized travel-route and aurora-alert MCP servers and verified HTTP deployment.
- Parsed movement metrics into CSV and gathered beta feedback to sync measures across gym and client pages.

## Week Summaries

### Week 1
- **Day 1:** Set up tools, ran initial tests, and began front-end development.
- **Day 2:** Built the Postgrd EDSO dashboard using Vibe coding.
- **Day 3:** Implemented the programs page for EDSO.
- **Day 4:** Implemented the clients page for EDSO.
- **Day 5:** Performed live testing and finalized code.

### Week 2 (June 23–28, 2025)
- **Day 1:** Created coach-side client management and workout calendar.
- **Day 2:** Linked client app to the production database and improved calendar navigation.
- **Day 3:** Organized workouts by date and fixed timezone bugs.
- **Day 4:** Implemented secure JWT login with email invitations.
- **Day 5:** Added workout results storage and completion tracking.
- **Day 6:** Optimized the codebase and polished the interface.

### Week 3 (June 30–July 6, 2025)
- **Day 1:** Built React Native app with Expo Router and tab navigation.
- **Day 2:** Completed authentication flow with login, password reset, and session storage.
- **Day 3:** Created workouts, profile, explore, and workout detail screens.
- **Day 4:** Added gradient buttons, styled inputs, and swipeable workout views.
- **Day 5:** Implemented date-based navigation, completion tracking, and pull-to-refresh.
- **Day 6:** Finalized Expo configuration with smooth animations for iOS and Android.

### Week 4 (July 7–July 13, 2025)
- **Day 1:** Built the app with Expo Go and tested the mobile build.
- **Day 2:** Unified button colors and shapes for consistent UI.
- **Day 3:** Learned EAS configuration and launched an iOS test build.
- **Day 4:** Updated the review page after rejection and resubmitted; added class features in the coach app.
- **Day 5:** Fixed add/delete workout bugs in the mobile app.
- **Day 6:** Resolved coach app issues with workouts, clients, programs, and classes.
- **Day 7:** Released the mobile client app on the Apple App Store.

### Week 5 (July 14–July 20, 2025)
- **Day 1:** Implemented the class attendance feature in the mobile app.
- **Day 2:** Handled race conditions from coach and client concurrency and updated the UI with a blue-purple gradient.
- **Day 3:** Added client list viewing feature.
- **Day 4–6:** Troubleshooting and debugging.
- **Day 7:** Narrowed down the class attendance issue and began rebuilding, reaching 70% completion.

### Week 6 (July 21–July 27, 2025)
- **Day 1:** Finished the class attendance feature in the mobile app.
- **Day 2:** Fixed race conditions and added biometric login.
- **Day 3:** App Store requested a review of the updated version.
- **Day 4:** Added Google Play data deletion request feature in the coach app.
- **Day 5–6:** Attempted to build a gym entity with coach subset; build failed and rolled back.
- **Day 7:** Planned fixes and next steps.

### Week 7 (July 28–August 3, 2025)
- **Day 1:** Built the Gym entity.
- **Day 2–3:** Developed the "restap" React Native mobile app to track rest time between workout sets.
- **Day 4–5:** Troubleshot issues related to the gym entity.
- **Day 6:** Off.
- **Day 7:** Completed the gym feature enabling coaches to manage clients by gym.

### Week 8 (August 4–August 10, 2025)
- **Day 1:** Resolved a git merge conflict by force pushing a rollback.
- **Day 2:** Fixed minor CRUD operation issues in the app.
- **Day 3:** Created a testbed gym and programs for universal client testing.
- **Day 4:** Implemented an MCP server for testing and explored the GPT-5 model with IDEs like Lovable, Cursor, and ChatGPT.
- **Day 5:** Began collecting feedback from beta test users.
- **Day 6–7:** Built a personalized travel-route MCP server to validate local and virtual deployment.

### Week 9 (August 11–August 17, 2025)
- **Day 1:** Built a personalized travel-route MCP server for local and virtual testing.
- **Day 2–3:** Fixed UI on the /gyms page preparing for a gyms calendar where clients can browse assigned workouts.
- **Day 4:** Gathered UX requirements, created the database schema and frontend components, and parsed 50 movement metrics into CSV for client tracking.
- **Day 5:** Resolved issues from the "measures" feature syncing gym and client pages and built an Aurora-alert MCP server to predict auroras using NOAA data.
- **Day 6:** Ran Restap EAS build and locally tested the Aurora-alert server over HTTP for deployment.
- **Day 7:** Off.
## Weekly Logs
- [Internship Logs](internship/README.md)
- [Detailed Summaries](weekly_summaries)
