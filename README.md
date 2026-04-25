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

```text
focussense/
├── manifest.json
├── background.js
├── dashboard/
│   ├── dashboard.html
│   └── dashboard.js
├── newtab/
│   ├── newtab.html
│   └── newtab.js
├── popup/
│   └── popup.js
└── chart.js
⚡ Installation
Clone the repository
git clone https://github.com/YOUR_USERNAME/focussense.git
Open Chrome and go to:
chrome://extensions/
Enable Developer Mode
Click Load Unpacked
Select the project folder
▶️ How to Use
Open the extension
Start a focus session
Browse normally — activity is tracked automatically
View insights in the dashboard
Use the new tab page for daily learning
🎯 Business Value
Improves productivity through awareness
Encourages better focus habits
Demonstrates real-world data tracking and analytics
🚀 Future Enhancements
Focus score and streak tracking
Data export (CSV)
Pomodoro timer integration
Expanded interview question bank
🔐 Privacy
All data is stored locally using chrome.storage.local
No external servers or APIs
No user tracking
🤝 Contributing

Contributions are welcome!
Fork the repository and submit a pull request

### ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub
