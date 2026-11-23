# Number Buddies

A child-friendly number practice app for numbers 1–100. It is a static website and can be hosted directly with GitHub Pages.

## Run locally
Open `index.html` in a modern browser. No build step or dependencies are required.

## Publish with GitHub Pages
1. Create a GitHub repository (for example, `number-buddies`).
2. Upload `index.html` and this `README.md` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`, then save.
6. Wait for the Pages URL to appear in the Pages settings.

## Features
- Ten levels: 1–10, 11–20, …, 91–100.
- Practice in small groups of up to four numbers.
- Trace practice with a finger, stylus, mouse, and an animated/outlined demonstration.
- Spoken number playback and listening identification (uses the browser's Speech Synthesis API).
- Number sequencing exercise.
- Prominent repeat controls.
- Two learner profiles: Unicorn and Bear.
- Per-profile progress saved in browser `localStorage`; no database, account, or cloud storage.
- Parent corner protected by a PIN (default `1234`), with progress summaries and PIN change.

## Notes
- Audio uses the browser/device's built-in text-to-speech voices. Voice availability varies by browser and operating system; the app needs no audio files or network service.
- Browser storage is local to the current browser and device. It can be erased if site data is cleared, and it does not sync between devices.
- The parent PIN is a basic child-navigation barrier, not strong security. Anyone with access to browser developer tools or local storage can bypass it. Change the default PIN before use.
- Tracing demonstrations use the browser's number glyph outline; stroke order can vary by font. The child can trace over the guide, then clear and repeat as often as desired.
