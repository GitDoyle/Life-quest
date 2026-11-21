# Life Quest

A phone-friendly Progressive Web App for working through 24 wellbeing achievements across four pillars. Tick off each achievement once when you complete it; the app records the completion date and awards 10 XP. Progress is based on unique achievements completed, not repeating one challenge each day for a week.

## Install on Android
A PWA must be served from HTTPS (or localhost) to be installable. It cannot be installed directly by opening the HTML file from a download.

### Easiest route: GitHub Pages
1. Open the repository's **Settings → Pages**.
2. Under Build and deployment, choose **Deploy from a branch**, select the branch and `/ (root)`, then Save.
3. Wait for GitHub Pages to publish the site. Open its HTTPS URL on your Android phone in Chrome.
4. In Chrome, tap ⋮ → **Install app** or **Add to Home screen**.

## Notes
- Achievement checkmarks and completion dates are saved in browser localStorage on that device; they do not sync to another device.
- Existing data from the earlier weekly-check-in version is left untouched and is not converted into completed achievements, since an attempt does not necessarily mean an achievement was completed.
- This app does not send push notifications.
- The 24 achievement names are transcribed from the page images shared in the conversation. Use the book itself for the full instructions behind each achievement.
