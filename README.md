# 🌧️ Rainwater Harvesting Sustainability Dashboard

> **Day 11 of 30 Days · 30 SIH Solutions** — by [Harish Kumar](https://github.com/hv88786-debug) | Alpha Coders | GEC Ajmer

[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML%20%2B%20JS-green?style=flat-square)](https://github.com/hv88786-debug)
[![No Framework](https://img.shields.io/badge/Framework-None-blue?style=flat-square)](#)
[![Offline](https://img.shields.io/badge/Works-Offline-brightgreen?style=flat-square)](#)
[![Bilingual](https://img.shields.io/badge/Language-EN%20%2B%20Rajasthani-orange?style=flat-square)](#)
[![SIH 2025](https://img.shields.io/badge/SIH-2025-red?style=flat-square)](#)

---

## 🚀 Live Demo

> Open `dashboard_bilingual.html` directly in your browser — no server, no install, no internet needed.

---

## 🧠 What Is This?

A **fully offline, single-file** rainwater harvesting assessment dashboard built for Smart India Hackathon 2025.

Enter your roof area, annual rainfall, and system efficiency — the dashboard gives you:
- How much water you can harvest per year
- AI-powered recommendations to improve your system
- Risk analysis with a 0–100 score
- Government schemes you're eligible for
- Community and environmental impact
- A judge-ready presentation mode

**No server. No API. No framework. One HTML file.**

---

## ✨ Features

### 🤖 AI Intelligence Center
| Feature | Description |
|---|---|
| AI Water Advisor | 7 intervention candidates ranked by impact — top 3 served based on your numbers |
| Risk Analysis Engine | Scores 0–100 across rainfall reliability, system efficiency, and storage loss |
| Smart Timeline | Staged action plan — Immediate / Next Season / Long-Term |
| AI Sustainability Score | Weighted gauge across 3 components with verdict |

### 📊 Data & Calculations
| Feature | Description |
|---|---|
| Core Assessment | Annual harvest, water saving score, status badge |
| 5-Year Projection | SVG line chart — harvested vs potential, 8% growth model |
| Community Calculator | Enter colony size → collective liters + families + CO₂ |
| Seasonal Breakdown | Monsoon / Summer / Winter harvest split |

### 🏛️ Government Integration
| Scheme | Eligibility |
|---|---|
| Jal Shakti Abhiyan Subsidy | Roof ≥ 500 sq ft, Harvest ≥ 5,000 L |
| State RWH Incentive | Roof ≥ 800 sq ft, Harvest ≥ 10,000 L |
| Green Building Credit | Roof ≥ 1,200 sq ft, Harvest ≥ 20,000 L |
| Farm / Rural Water Grant | Any farm catchment, Harvest ≥ 3,000 L |

### 🌍 Environmental Impact
- Eco Impact Score (animated SVG ring)
- CO₂ avoided per year
- Tree hydration equivalent
- Household months of water supply
- UN SDG 6, 11, 13 live contribution mapping

### 🏆 Achievement System
- 🛡️ **Water Guardian** — Harvest 20,000+ L/yr
- 🌿 **Eco Champion** — 75%+ efficiency with <25% loss
- 🌐 **Climate Protector** — 70+ Sustainability Score
- 👥 **Community Hero** — 1,200+ sq ft, 30,000+ L/yr

### 🗣️ Bilingual Support
- Full **English ↔ Rajasthani** instant language switch
- Every string translates — headings, buttons, labels, placeholders, validation messages, AI recommendations, risk analysis, export report, presentation mode, guided tour
- Rural-friendly Rajasthani language (no Google Translate, 100% offline)

### 🎤 Presentation Mode
- One-click full-screen judge-ready overlay
- AI Score + Top 3 recommendations + Unlocked badges

### 🧭 Guided Tour
- 8-step interactive walkthrough with spotlight
- Keyboard navigable (← → arrows, Escape to exit)
- Fully bilingual — tour text also switches with language

### 📄 Export
- Print / Save as PDF — full formatted report
- Copy report text — language-aware content

---

## 🛠️ Tech Stack

```
HTML5          → Structure + semantic layout
CSS3           → Government-dashboard design, animations, SVG
Vanilla JS     → All logic, calculations, rendering
SVG            → Charts, rings, gauges (no library)
```

**Zero dependencies. Zero CDN. Zero build tools.**

---

## 📁 Project Structure

```
day-11-rainwater-harvesting/
│
└── dashboard_bilingual.html    ← Entire project (single file)
```

---

## ⚡ How to Run

```bash
# Clone the repo
git clone https://github.com/hv88786-debug/30-days-30-sih.git

# Navigate to Day 11
cd 30-days-30-sih/day-11

# Open in browser
open dashboard_bilingual.html
# OR just double-click the file
```

No npm install. No pip install. No `localhost`. Just open and use.

---

## 🧮 Calculation Logic

```
Annual Harvest (L) = Roof Area (sq ft) × 0.0929 (→ m²)
                   × Annual Rainfall (mm) × (Efficiency / 100)

Water Saving Score = weighted blend of:
  - Capture % of max potential      (40 pts)
  - System efficiency               (35 pts)
  - Rainfall reliability index      (25 pts)

CO₂ Avoided = Harvested L × 0.298 g/L ÷ 1000 (→ kg)
```

---

## 🗺️ Roadmap (Future Scope)

- [ ] Firebase backend for real community leaderboard
- [ ] Geolocation-based rainfall auto-fill (IMD API)
- [ ] Photo upload for roof area estimation (AI vision)
- [ ] PWA / installable offline app
- [ ] More regional languages (Hindi, Gujarati, Marathi)

---

## 👨‍💻 About the Builder

**Harish Kumar**
First-year B.Tech CSE | GEC Ajmer | Alpha Coders

Running a personal challenge: **30 Days · 30 SIH Solutions** — shipping one Smart India Hackathon problem statement solution every single day as a portfolio + prep series.

- 🐙 GitHub: [@hv88786-debug](https://github.com/hv88786-debug)
- 📸 Instagram: [@hv__harish](https://instagram.com/hv__harish)
- 💼 LinkedIn: [Harish Kumar](https://linkedin.com/in/)

---

## 📅 30 Days · 30 SIH Solutions

| Day | Project | Status |
|-----|---------|--------|
| 01 | Career Compass — EdTech Assessment | ✅ Done |
| 02 | ... | ✅ Done |
| ... | ... | ... |
| 10 | SmartTimetable — ERP System | ✅ Done |
| **11** | **Rainwater Harvesting Dashboard** | **✅ Done** |
| 12 | Coming soon... | 🔄 |

---

## 📄 License

MIT License — free to use, modify, and distribute with attribution.

---

<div align="center">

**⭐ Star this repo if it helped you! ⭐**

*Built with 💚 for Smart India Hackathon 2025*

</div>
