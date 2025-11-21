# 📊 Monthly All-in-One Tracker

A beautiful, minimal habit and mood tracker with interactive charts. Built with a soft lavender aesthetic for embedding in Notion or standalone use.

![Preview](https://img.shields.io/badge/Status-Live-85c88a?style=flat-square)
![License](https://img.shields.io/badge/License-Personal_Use-9b8aa5?style=flat-square)

---

## ✨ Features

- **4 Metric Line Charts** — Track Study, Stress, Sleep, and Mood with smooth colored lines
- **8 Daily Habits Grid** — Visual checkbox system with colorful completion circles
- **Monthly Summary** — Auto-calculated averages for each metric
- **Responsive Design** — Works on desktop, tablet, and mobile
- **Notion Ready** — Embed directly using `/embed` block

---

## 🎨 Design

| Element | Color |
|---------|-------|
| Study | Purple `#9b8aa5` |
| Stress | Orange `#e8a87c` |
| Sleep | Blue `#7eb8da` |
| Mood | Green `#85c88a` |
| Border | Lavender `#d4c5e2` |

---

## 🚀 Quick Start

### Option 1: Embed in Notion
1. Copy your GitHub Pages URL
2. In Notion, type `/embed`
3. Paste the URL
4. Resize as needed

### Option 2: Use Standalone
Simply open `index.html` in any browser.

---

## 📁 Files

```
my-tracker/
├── index.html    # Main tracker (interactive)
└── README.md     # This file
```

---

## 🛠️ Customization

Edit `index.html` to personalize:

### Change Habits
Find the `habits` array around line 180:
```javascript
const habits = [
    'Meditation',
    'Reading',
    'Gym',
    // Add your own...
];
```

### Change Colors
Find the color definitions in the `<style>` section:
```css
.legend-line.study { background: #9b8aa5; }
.legend-line.stress { background: #e8a87c; }
```

### Add Your Data
Replace the `sampleData` object with your actual tracking data:
```javascript
const sampleData = {
    study:  [7, 8, 6, ...],  // Your daily values
    stress: [5, 4, 5, ...],
    sleep:  [7, 6, 8, ...],
    mood:   [7, 8, 7, ...]
};
```

---

## 📱 Screenshots

| Desktop | Mobile |
|---------|--------|
| Full chart + habits grid | Responsive scrollable view |

---

## 💜 Credits

- **Chart.js** — Interactive charts
- **Design Inspiration** — Minimal bullet journal aesthetics

---

## 📄 License

Personal use only. Feel free to customize for your own tracking needs.

---

<p align="center">
  <i>Happy tracking! May your habits bloom like lavender</i> 🌿
</p>
