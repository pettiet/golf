# Training Hub

Personal training site — daily plans, round tracker, strength assessments.

## Hosting

This site is built as a static HTML site for GitHub Pages.

1. Create a new repository on GitHub
2. Upload these files to the repository root
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch**
5. Choose `main` branch, `/ (root)` folder, click Save
6. Wait ~1 minute, then visit `https://<username>.github.io/<repo-name>/`

## File structure

- `index.html` — landing page / hub
- `today_session.html` — Day 1 baseline assessment (golf)
- `strength_assessment.html` — Day 1 evening strength session
- `round_tracker.html` — universal post-round entry form

## How data is stored

All entered data is saved to the browser's `localStorage` on the device. Nothing is sent anywhere — data lives only on the phone or browser where it was entered. Auto-save runs on every change.

To install as an app on iOS: open the URL in Safari → Share → Add to Home Screen.

## Privacy

No personal names or identifying information are stored in this repo. Only generic training content.
