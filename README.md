# Parhai Dost · پڑھائی دوست

A voice-first numeracy tutor for out-of-school children in Sindh, Pakistan. Children hear questions in **Sindhi or Urdu**, look at pictures from daily life, and answer by tapping. No reading, typing or login needed.

Built by **Iftekhar An-Naafi**, Computer Science Teacher, Beaconhouse Nawabshah Campus, as a Teacher Project for **ILAP 2027** (Strategic Intent: Accessibility & Inclusion · SDG 10).

## Features

- Five-level learning ladder: counting to 5, counting to 10, number recognition, addition, subtraction
- Spoken prompts and praise in Sindhi or Urdu (uses the phone's built-in voice)
- Adaptive difficulty: 3 correct in a row moves up, 2 wrong in a row moves down
- Gentle correction: after two mistakes, the tutor counts the objects aloud with the child
- Teacher panel: anonymous child codes, 10-question pre-check and post-check, saved results, one-tap export
- Works offline after the first visit and can be installed on the home screen
- Privacy first: no names, no accounts, no server; results stay on the phone

## Run it

Open `index.html` in Chrome. For offline mode and "Add to Home screen", host it over HTTPS (GitHub Pages works).

## Deploy on GitHub Pages

1. Create a new public repository, e.g. `parhai-dost`.
2. Upload all files in this folder (keep the `icons` folder).
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`, and save.
4. After a minute the app is live at `https://<your-username>.github.io/parhai-dost/`.

## Voice note

Many Android phones include an Urdu voice but not a Sindhi one. Install Urdu text-to-speech in **Settings → Accessibility → Text-to-speech** if it is missing. Recorded voice clips by student volunteers are the next milestone.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app (HTML, CSS, JavaScript) |
| `manifest.webmanifest` | Lets the app install to the home screen |
| `sw.js` | Service worker for offline use |
| `icons/` | App icons |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |
