# Role 2 Meds — Offline PWA

A Progressive Web App (PWA) for offline medication dosing reference.
Once installed, it works **completely without internet**.

---

## How to Install on Your Phone

### Option A: Free Hosting (Easiest — 2 minutes)

1. Go to **[GitHub](https://github.com)** and create a free account (if you don't have one)
2. Create a new repository named `role2-meds`
3. Upload all 4 files/folders from this zip:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/` folder (with both .png files)
4. Go to **Settings → Pages** → set source to `main` branch → Save
5. Your app is now live at: `https://YOUR-USERNAME.github.io/role2-meds/`
6. Open that URL on your phone:
   - **Android**: Tap the install banner, or Menu → "Add to Home Screen"
   - **iPhone**: Tap Share (□↑) → "Add to Home Screen"
7. The app icon appears on your home screen. It now works **offline forever**.

### Option B: Netlify Drop (Even Faster)

1. Go to **[app.netlify.com/drop](https://app.netlify.com/drop)**
2. Drag the entire `role2-pwa` folder onto the page
3. Your app gets a live URL instantly
4. Open on your phone and add to home screen (same as step 6 above)

### Option C: Local File (No Hosting Needed)

1. Transfer `index.html` to your phone (AirDrop, email, USB, etc.)
2. Open it in your mobile browser — it works fully offline as a single file
3. Note: You won't get the "app icon on home screen" experience this way,
   but all the medication data and functionality works.

---

## What You Get

- Full-screen app experience (no browser chrome)
- Works completely offline after first load
- All 25+ medications with weight-based dosing
- Scenario filters (RSI, Procedural Sedation, Cardiac, etc.)
- Search across all medications
- Patient weight calculator with bracket dosing
- "Offline Ready" badge confirms the app is cached

---

## Updating the App

To push updates, just replace the files at your hosting location and
increment the version in `sw.js` (change `role2-meds-v1` to `v2`, etc.).
The next time a user opens the app with internet, it auto-updates.
