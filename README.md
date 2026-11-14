# VESPERA V6.1 — Liquid Glass

A visual refinement of VESPERA V6. The existing app details and functionality are retained; the interface styling is simplified into a clearer, more consistent liquid-glass system.

## Included
- Existing home dashboard, player rank, XP, tasks and activity summary.
- Daily tasks, task library, filters and XP progression.
- Activity log, exercise library and seven-day activity chart.
- Local assistant for organizing selected tasks and the day.
- Floating translucent glass navigation bar on mobile and desktop.
- In-app notification center and optional browser notifications.
- Six full-interface accent themes: blue, pink, violet, cyan, emerald and amber.
- Refined dark-blue liquid-glass V icon.
- Arabic/English interface, local storage, backup import/export, PWA manifest and offline shell.

## Notifications note
In-app notifications are stored locally. Browser/system notifications require HTTPS, browser support and user permission. Due-task checks run when the app is opened; this package does not include a remote push server or guaranteed background delivery while the app is closed.

## Privacy
No account, cloud AI, external AI API, or external runtime library is used. Data stays in this browser's local storage. Export a backup before clearing browser data.

## Run
Upload all files to the root of a static HTTPS host, or open `index.html` locally. Service-worker/PWA installation requires HTTPS (or localhost).
