# FocusSense — Distraction Intelligence + Career Engine

![Manifest V3](https://img.shields.io/badge/Manifest-V3-blue?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![No Server](https://img.shields.io/badge/Data-100%25%20Local-brightgreen?style=flat-square)

> A Chrome extension that tracks your distraction patterns, blocks time-wasters during deep work, and turns every new tab into a career growth moment.

---

## Screenshots

### New Tab — Focus Greeter
![New Tab Page](https://raw.githubusercontent.com/narmatha0303/FocusSense-Distraction-intelligence-career-engine-for-deep-work/main/screenshot-newtab.png)
*Personalized greeter with live clock, daily focus intention, and quick access to the career question of the day.*

---

### Operational Intelligence Dashboard
![Analytics Dashboard](https://raw.githubusercontent.com/narmatha0303/FocusSense-Distraction-intelligence-career-engine-for-deep-work/main/screenshot-analytics.png)
*7-day distraction trend, hourly heatmap, productivity score, site distribution — all powered by locally stored data.*

---

### Focus Mode + Deep Work Session
![Focus Dashboard](https://raw.githubusercontent.com/narmatha0303/FocusSense-Distraction-intelligence-career-engine-for-deep-work/main/screenshot-focus-dashboard.png)
*Pomodoro-style deep work timer, site time tracker, daily data challenge with answer reveal, toolkit settings, and the Analyst Impact Report.*

---

### Captured Insights + Reading List
![Insights and Reading List](https://raw.githubusercontent.com/narmatha0303/FocusSense-Distraction-intelligence-career-engine-for-deep-work/main/screenshot-insights.png)
*All your `Ctrl+Shift+S` captures in one place, alongside a personal reading list for saving URLs.*

---

## What It Does

Most productivity tools just block sites. FocusSense goes further — it tracks *why* you get distracted, gives you data about your habits, and uses your idle browser time to sharpen your skills.

**Five core modules in one extension:**

### 1. Distraction Logger
Automatically detects and logs visits to 15+ distracting sites (YouTube, Reddit, Instagram, etc.) with a 60-second cooldown to avoid duplicate entries. Stores up to 7 days of history locally — no server, no tracking.

### 2. Focus Mode
Activate a hard focus session and the extension will automatically close any distracting tab the moment it loads — no willpower required.

### 3. Insight Capture (`Ctrl+Shift+S` / `Cmd+Shift+S`)
Highlight any text on any webpage and press the shortcut to save it as an insight. Falls back to the page title if nothing is selected. Keeps your 50 most recent captures accessible from the dashboard.

### 4. Tab Limiter
Set a maximum number of open tabs. When you exceed the limit, the newest tab is closed automatically — keeping your workspace clean and your focus intact.

### 5. Site Time Tracker
Tracks how many seconds you spend on each domain throughout the day. Measures active window focus, handles idle detection, and respects multi-window workflows.

### Bonus: Career New Tab
Every new tab surfaces a daily interview question from a curated bank of 30 questions across **SQL**, **Analytics**, and **Case Studies** — with a full answer on demand. Perfect for data analysts and PMs in job-search mode.

---

## Tech Stack

- **Manifest V3** Chrome Extension
- **Vanilla JS** — no framework dependencies
- **`chrome.storage.local`** — all data stays on your device
- **`chrome.scripting`** — for content capture and focus mode enforcement
- **`chrome.idle`** — for accurate time tracking
- **Chart.js** — for the analytics dashboard

---

## Installation (Developer Mode)

1. Clone this repository:
   ```bash
   git clone https://github.com/narmatha0303/FocusSense-Distraction-intelligence-career-engine-for-deep-work.git
   ```
2. Open Chrome and go to `chrome://extensions`
3. Enable **Developer Mode** (top right toggle)
4. Click **Load unpacked** and select the project folder
5. Pin the FocusSense icon to your toolbar

---

## Project Structure

```
focussense/
├── manifest.json          # Extension config (MV3)
├── background.js          # Service worker — core logic
├── dashboard/
│   ├── dashboard.html     # Main analytics UI
│   └── dashboard.js       # Dashboard rendering & charts
├── newtab/
│   ├── newtab.html        # New tab override
│   └── newtab.js          # Daily question bank (30 Q&As)
├── popup/
│   └── popup.js           # Extension popup
└── chart.js               # Chart.js (bundled)
```

---

## Privacy

All data is stored locally using `chrome.storage.local`. Nothing is sent to any server. The extension requires broad `<all_urls>` host permissions only to enable the content capture shortcut on any webpage.

---

## Roadmap

- [ ] Custom distraction site list (user-defined)
- [ ] Weekly focus score and streaks
- [ ] Export data as CSV
- [ ] Pomodoro timer integration
- [ ] Expanded question bank (Python, Statistics, Product Sense)

---

## License

MIT © Narmatha 2026
