# 📅 Habit Tracker

A beautiful, offline-first habit tracking Progressive Web App (PWA) — works on your phone and laptop, no account needed.

> **Live App →** `https://personal-habit-tracker-sy.netlify.app`

---

## ✨ Features

- ✅ **Daily habit tracking** — check off habits and build streaks
- 📊 **Monthly grid view** — see your full month at a glance
- 📈 **Analytics & charts** — visualize progress over time
- 🔥 **Streak tracking** — stay motivated with current and best streaks
- 📤 **Export to CSV / JSON** — download your data anytime
- 📥 **Import JSON** — restore or transfer data between devices
- 📱 **Installable PWA** — add to home screen like a native app
- ⚡ **Fully offline** — works without internet after first load
- 🔒 **No account, no server** — all data stays on your device

---

## 📁 File Structure

```
habit-tracker/
├── index.html          # Main PWA (mobile + desktop)
├── habit-tracker.html  # Standalone desktop version
├── manifest.json       # PWA manifest (icons, name, theme)
├── sw.js               # Service worker (offline support)
├── icon-192.png        # App icon (192×192)
├── icon-512.png        # App icon (512×512)
└── README.md
```

---


## 📱 Installing on Your Phone

1. Open `https://personal-habit-tracker-sy.netlify.app/` in your mobile browser
2. **iOS (Safari):** Tap Share → "Add to Home Screen"
3. **Android (Chrome):** Tap the install prompt or Menu → "Add to Home Screen"
4. The app opens fullscreen like a native app, works offline

---

## 💻 Using on Laptop

Just open the PWA link in any browser — it works like a regular web app. No installation needed.

Or use the dedicated desktop version at `/habit-tracker.html` for the classic tab-based layout.

---

## 🔄 Syncing Between Devices

Data is stored in **localStorage** — it's per-device and doesn't sync automatically.

To move data between phone and laptop:

1. On Device A → **Export JSON**
2. Transfer the file (email, AirDrop, Google Drive, etc.)
3. On Device B → **Import JSON**

---






## 📄 License

Sachin Yadav — free to use, modify, and share.
