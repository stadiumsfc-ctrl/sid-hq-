# SID HQ — Daily Command Centre
### Personal Task & Reminder PWA

---

## What's inside

```
stadium-pwa/
├── index.html      ← The entire app (one file)
├── manifest.json   ← PWA config (name, icons, theme)
├── sw.js           ← Service worker (offline support)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

---

## HOW TO HOST (3 options)

### Option A — Netlify Drop (easiest, free, 2 minutes)
1. Go to https://app.netlify.com/drop
2. Drag the entire `stadium-pwa` folder into the browser
3. Netlify gives you a live URL instantly (e.g. https://sid-hq.netlify.app)
4. Open that URL on your phone → "Add to Home Screen"
5. Open on desktop → Chrome will show "Install" button in address bar

### Option B — GitHub Pages (free, version controlled)
1. Create a free GitHub account at github.com
2. Create a new repo called `sid-hq`
3. Upload all files from this folder
4. Go to Settings → Pages → Source: main branch → Save
5. Your URL: https://YOUR_USERNAME.github.io/sid-hq/

### Option C — Run locally (desktop only)
1. Install Node.js from nodejs.org
2. Open Terminal / Command Prompt in this folder
3. Run: `npx serve .`
4. Open http://localhost:3000 in Chrome
5. Chrome will show "Install" button → click it → desktop app!

---

## INSTALL ON PHONE (after hosting)

### iPhone / Safari
1. Open the hosted URL in Safari
2. Tap the Share button (box with arrow)
3. Tap "Add to Home Screen"
4. Tap "Add" — appears as an app icon!

### Android / Chrome
1. Open the hosted URL in Chrome
2. Tap the 3-dot menu
3. Tap "Add to Home Screen" or "Install App"
4. Tap "Install"

### Desktop / Chrome
1. Open the hosted URL in Chrome
2. Look for the install icon (⊕) in the address bar, right side
3. Click it → "Install"
4. Opens as a standalone window with no browser chrome!

---

## FEATURES

- ✅ Today / Tomorrow / Overdue / Future date grouping
- ✅ 11 pre-built areas: Stadium (5 sub-areas), Klarity, Job Search, Self Finance, Pepe, CD Leganés
- ✅ Add, edit, delete tasks — click title to edit inline
- ✅ Subtasks with checkboxes, inline edit, delete
- ✅ Priority levels (High / Med / Low)
- ✅ Schedule tasks to any date
- ✅ Add custom areas with colour coding
- ✅ Works offline (service worker cache)
- ✅ All data stored locally on your device (no server needed)
- ✅ Mobile-responsive with bottom navigation
- ✅ Progress tracking per day

---

## DATA

All your tasks are saved in your browser's localStorage — they persist across sessions on the same device/browser. To back up, you can periodically export via browser DevTools > Application > Local Storage.

---

Built for Siddharth Sharma | Stadium FC + Klarity
