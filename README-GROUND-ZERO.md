# Ground Zero — WOLF-01

A minimal offline-first fitness web app. Enter the starfield, complete sets one at a time, automatically rest three minutes between sets, switch to your running app and return to stop the run, and come back after local midnight for the next day.

This replaces the previous app at the repository root. It has no backend or account; progress is saved in this device's browser localStorage. Do not clear site data if you want to keep progress.

## Publish
The included GitHub Actions workflow builds and deploys the repository root. In repository **Settings → Pages**, choose **GitHub Actions** as the build and deployment source, then run **Actions → Deploy Ground Zero → Run workflow** if needed.

Expected URL: https://mkto46.github.io/Ground-Zero-V6-Rebirth/ (only usable once GitHub Pages deployment is successful).

## Offline
Once loaded online, the service worker caches the HTML, manifest, and icon. After installation, open from the phone's Home Screen. Revisit online after updates to refresh the cache.

## Features
Mobility Ladder A, gym assisted pull-ups and dips, core Ladder D, running handoff, 3-minute rest periods, 14-day check-in and a local-midnight unlock. Gym is skipped on Sunday.

## Limitations
The 14 days track finished workout days. When 14 days are complete the app stays on the finish screen. The running handoff does not open another app automatically. There is no login or cloud syncing.
