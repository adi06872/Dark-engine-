# ⚔️ Adi OS — PWA Install Guide

## Deploy to Netlify (5 minutes, zero coding)

### Step 1 — Go to Netlify
- Open: https://netlify.com
- Click "Sign up" (free) → use Google or GitHub

### Step 2 — Deploy
- After login, you'll see your dashboard
- Click **"Add new site"** → **"Deploy manually"**
- Drag the entire **adi-os-pwa** folder into the upload box
- Wait ~30 seconds → you get a live URL like: `https://random-name.netlify.app`
- (Optional) Click "Site settings" → rename to something like `adi-os`

### Step 3 — Install on Android
1. Open your Netlify URL in **Chrome**
2. A banner will appear at the bottom: **"Add Adi OS to Home Screen"**
3. Tap **Install**
4. Done! ⚔️

### Step 3 — Install on iPhone
1. Open your Netlify URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share button** (box with arrow at bottom)
3. Scroll down → tap **"Add to Home Screen"**
4. Tap **"Add"**
5. Done! ⚔️

---

## What you get
- ✅ Full-screen app (no browser bar)
- ✅ Works offline after first load
- ✅ Data saved on your device (localStorage)
- ✅ Home screen icon
- ✅ Splash screen on launch
- ✅ All 7 sections: Dashboard, Pipeline, Tasks, Habits, Ideas, Analytics, Calendar
- ✅ Mobile-optimized bottom navigation
- ✅ Focus Mode + Deep Work Timer

## Files in this package
- `index.html` — The entire app
- `manifest.json` — Makes it installable as an app
- `sw.js` — Enables offline use
- `icons/` — App icons for home screen
- `netlify.toml` — Netlify config (handles routing)
