# 🚀 FocusSense — Distraction Intelligence + Career Engine

> A Chrome extension that tracks distraction patterns, enforces focus, and transforms browsing behavior into actionable insights.

---

## 🚀 Overview  

FocusSense is a productivity-focused Chrome extension designed to help users reduce distractions and improve focus using data.

Unlike traditional blockers, it combines:
- 🔒 Real-time distraction control  
- ⏱ Behavioral tracking  
- 📊 Data-driven insights  
- 🎯 Career-focused learning  

---

## 🧠 Problem  

Users often struggle with:
- Lack of awareness of time spent on distracting websites  
- No measurable productivity insights  
- Tools that rely only on self-discipline  

**Result:** Reduced focus and inefficient work habits  

---

## 💡 Solution  

FocusSense provides an integrated system that:
- Tracks browsing behavior  
- Identifies distraction patterns  
- Enforces focus automatically  
- Converts idle browsing into learning opportunities  

---

## ⚙️ Tech Stack  

- Chrome Extension (Manifest V3)  
- JavaScript, HTML, CSS  
- Chrome APIs (`storage`, `scripting`, `idle`)  
- Chart.js (analytics dashboard)  
- AntiGravity Chrome Extension Framework  

---

## 🔑 Core Features  

### 🔒 Distraction Logger  
- Tracks visits to distracting websites  
- Uses cooldown logic to prevent duplicate logging  
- Stores recent activity locally  

---

### 🎯 Focus Mode  
- Automatically closes distracting tabs  
- Eliminates reliance on willpower  

---

### ✍️ Insight Capture  
- Save highlighted text from any webpage  
- Stores recent insights for later review  

---

### 🧠 Tab Limiter  
- Restricts the number of open tabs  
- Helps maintain a clean and focused workspace  

---

### ⏱ Site Time Tracker  
- Tracks time spent per domain  
- Handles idle detection and tab switching  

---

### 🚀 Career New Tab  
- Displays daily interview questions  
- Helps users improve skills during idle browsing time  

---

## 📊 Analytics & Insights  

The extension converts raw browsing data into meaningful insights:

- Time spent per website  
- Daily usage patterns  
- Focus vs distraction behavior  

👉 Enables users to make **data-driven productivity improvements**

---

## 🏗️ Project Structure  

 
---
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
---
 ## 📸 Screenshots  

### 📊 Dashboard  
![Dashboard](assets/dashboard.png)

### 🔒 Focus Mode Popup  
![Popup](assets/popup.png)

### 🚀 New Tab Career Page  
![New Tab](assets/newtab.png)
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
 


If you found this project useful, consider giving it a ⭐ on GitHub
