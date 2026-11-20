# Life Quest (PWA starter)

This is a phone-friendly Progressive Web App. It uses a Monday–Sunday week and lets you select one of the 24 challenges, record daily attempts, earn 10 XP per attempt, and save a weekly reflection.

## Install on Android
A PWA must be served from HTTPS (or localhost) to be installable. It cannot be installed directly by opening the HTML file from a download.

### Easiest route: GitHub Pages
1. Create/sign in to a GitHub account.
2. Create a new public repository named `life-quest`.
3. Upload `index.html`, `manifest.webmanifest`, `sw.js`, and `icon.svg` to the repository root.
4. In the repository, open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. Open its HTTPS URL on your Android phone in Chrome.
7. In Chrome, tap ⋮ → **Install app** or **Add to Home screen**.

## Notes
- Weeks start Monday and end Sunday, using the device's local calendar.
- Data is stored in browser localStorage on that device. It does not sync to another device.
- This starter does not send push notifications. The separate ChatGPT daily reminder is independent.
- The 24 challenge names are transcribed from the page images shared in the conversation. Use the book itself for the full instructions behind each challenge.
