# TOFCL Learning — Personal MVP

A free, local-first Traditional Chinese study web app and Taiwan MBA application planner.

## Included
- Sentence of the Day with Traditional Chinese, pinyin, English and browser audio (zh-TW where available)
- Vocabulary library with add/search/filter, audio, mastery status and saved words
- Flashcards, fill-in-the-blank, and sentence writing practice
- Local progress storage in the current browser
- Export personal data to JSON
- MBA Taiwan roadmap checklist and savings planner
- Responsive mobile and desktop layout
- Basic PWA manifest/service worker for HTTPS hosting

## Run locally
Open `index.html` in a modern browser. Core features work locally. Audio depends on the browser/device's speech voices.

## Publish for web access
Upload `index.html`, `manifest.webmanifest`, and `sw.js` to a static hosting service with HTTPS (for example, GitHub Pages or another free static host). PWA/service-worker features generally require HTTPS or localhost. The app currently saves data to the browser on each device; it does not sync automatically between iPhone and laptop.

## Important limitations
- This is a functional starter MVP, not an official TOCFL product.
- Pronunciation is text-to-speech playback only; mic-based scoring is not implemented.
- Stroke-order animation, full stories, official test content, user accounts and cloud sync are not implemented in this first version.
- University and scholarship deadlines/requirements must be checked on official pages for the exact 2027 MBA program.
- For an iPhone Home Screen widget (a native widget outside the app), additional native iOS development is required. The web app can be added to the Home Screen as an app shortcut/PWA after HTTPS hosting.

## Personal data
All study data is stored locally in browser storage. Use Export data to make a backup before clearing browser data.
