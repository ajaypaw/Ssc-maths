# SSC CGL / CHSL Maths Practice Portal — v10 Full UI

A mobile-first rebuild of the existing portal. The question bank and core test logic from the v5 portal are retained.

## UI / features added
- Rebuilt mobile UI for Dashboard, Setup, Confidence Test, CBT, Result, My Errors, Analytics and Concept Mastery
- App-style mobile header + fixed bottom navigation
- Chapter search on Dashboard
- Dashboard progress/accuracy cards and chapter progress bars
- Install-app prompt when the browser exposes PWA installation
- CBT desktop palette moved to the left to match current SSC-style layout patterns
- CBT zoom A− / A+ / Reset controls
- Question palette filters: All / Unanswered / Answered / Review
- Thumb-friendly mobile exam dock
- Submit confirmation sheet with Answered / Marked / Unanswered counts
- Real in-progress local auto-save + Resume Test after refresh/reopen
- Result performance insight + result filters
- My Errors search + Slow / Recent filters
- Keyboard shortcuts (1–4 options, arrows, M) and horizontal swipe navigation in tests
- Dark theme retained
- PWA manifest + service worker

## Run / install
For PWA installation and service-worker features, serve this folder from HTTPS or localhost and open `index.html` in a compatible browser. The standalone app can then be added to the Android home screen.
