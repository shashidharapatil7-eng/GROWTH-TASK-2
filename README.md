# ∞ GROWTH TASK — Dark Knight Protocol

> *"It's not who I am underneath, but what I do that defines me."* — Batman

A Batman-themed personal productivity system built as a single-file web app. Track tasks, stay consistent, and grow every day.

---

## 🚀 Live Demo

Once deployed, your app will be live at:
```
https://YOUR-USERNAME.github.io/growth-task/
```

---

## ⚡ Features

- **∞ Daily Motivation Quotes** — 205 quotes from Batman, Stoicism, Athletes, Leaders, Philosophers — new one every day
- **Split View** — Pending tasks on the left, Completed on the right
- **Live Clock** — Real-time date and time in the header
- **Multi-Task Input** — Add 9+ tasks at once per session
- **Task Lifecycle** — Add → Complete → Reschedule → Track
- **Overdue Detection** — Tasks past their date are flagged automatically
- **Weekly Grid** — 7-day overview at a glance
- **Reports** — 7d / 1M / 3M / 6M / 1Y analytics with activity heatmap
- **Batman Download Reports** — Print-ready Batman-styled PDF reports
- **JSON Backup & Import** — Cross-device sync via export/import
- **Streak Tracker** — Consecutive days with completed tasks
- **Fully Mobile Responsive** — Works on all screen sizes
- **No backend needed** — Pure HTML/CSS/JS, data in localStorage

---

## 📦 Deploy to GitHub Pages (Step-by-Step)

### Step 1 — Create GitHub Account
Go to [github.com](https://github.com) and sign up (free).

### Step 2 — Create New Repository
1. Click the **+** button (top right) → **New repository**
2. Name it: `growth-task`
3. Set to **Public**
4. Check **"Add a README file"**
5. Click **Create repository**

### Step 3 — Upload Files
1. In your new repo, click **"Add file"** → **"Upload files"**
2. Upload these files:
   - `index.html`
   - `README.md`
   - `404.html`
   - `.nojekyll`
3. Scroll down → click **"Commit changes"**

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** tab
2. Left sidebar → **Pages**
3. Under **Source** → select **"Deploy from a branch"**
4. Branch: **main**, Folder: **/ (root)**
5. Click **Save**

### Step 5 — Get Your URL
Wait 1-2 minutes, then visit:
```
https://YOUR-USERNAME.github.io/growth-task/
```

---

## 📱 Using on Multiple Devices

Your data lives in your browser's `localStorage`. To sync across devices:

1. Open the app → go to **Download** tab
2. Click **"Backup JSON"** — saves your data file
3. Open the app on your other device
4. Go to **Download** tab → click **"Import JSON"**
5. Select your backup file — all tasks sync instantly

---

## 🦇 Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Pure HTML5 + CSS3 + Vanilla JavaScript |
| Storage | Browser localStorage |
| Fonts | Google Fonts (Bebas Neue, Rajdhani, Oswald, Share Tech Mono) |
| Hosting | GitHub Pages (free, static) |
| Build | None required — single file app |

---

## 📁 File Structure

```
growth-task/
├── index.html      ← The entire app (HTML + CSS + JS)
├── 404.html        ← Redirect for GitHub Pages routing
├── .nojekyll       ← Disables Jekyll processing (required)
└── README.md       ← This file
```

---

## 🎨 Theme

- **Background**: Deep black `#020204` with Gotham city silhouette
- **Accent**: Batman gold `#f5c518` with glow effects
- **Animations**: Flying bats, bat signal, rain, scanlines, city skyline
- **Fonts**: Bebas Neue (display), Rajdhani (body), Share Tech Mono (data)
- **Cursor**: Custom gold ring cursor on desktop

---

## 💾 Data & Privacy

- All data stored **100% locally** in your browser
- No server, no account, no tracking
- Data persists across sessions on the same browser
- Use JSON export/import for cross-device access

---

*∞ GROWTH TASK — Dark Knight Protocol*
