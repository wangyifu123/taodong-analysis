<div align="center">

# Econ-Sentiment Twin Think Tank · 财情双生智库

**Finance × Emotion · Unity of Opposites · All-in-One Asset Decision System**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Version](https://img.shields.io/badge/version-v1.0-blue)
![Zero Build](https://img.shields.io/badge/zero--build-100%25_vanilla-brightgreen)
![Bilingual](https://img.shields.io/badge/中文%20%7C%20EN-bilingual-4FC3F7)
![Free APIs](https://img.shields.io/badge/data-free%20APIs-orange)
![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages%20%7C%20Nginx-success)

**WEALTH & WISDOM · WITH WARMTH**
**TRANSFORM SUFFERING INTO WISDOM · CONFLICT INTO WIN-WIN · WORRY INTO GROWTH**

</div>

---

Econ-Sentiment Twin Think Tank is a **personal asset-decision toolkit** that fuses rational financial analysis with market-sentiment judgment across six dimensions: macro surveillance, cycle positioning, fund flows, equities-bonds-FX, gold, and FX major pairs.

**100% static · Zero build · Zero backend** — Every page is a single-file HTML that runs anywhere; all data is pulled live in the browser from free public APIs.

> 🌐 **Live Demo**: [http://118.25.197.75:3050/](http://118.25.197.75:3050/) (Chinese, default entry)
> 🇺🇸 **English**: [http://118.25.197.75:3050/index-en.html](http://118.25.197.75:3050/index-en.html)

---

## ✨ Highlights

| Feature | Description |
|---------|-------------|
| 🌍 **7 Subsystems** | Macro Surveillance / Merrill Clock / Kondratieff Cycles / Fund Flow / S·B·FX / Gold / FX Major Pairs |
| 🧠 **Finance-Emotion Methodology** | 5-stage framework: Problem Definition → Decomposition → Cycle Positioning → Data Evidence → Falsification (falsifiability > interpretability) |
| 🇨🇳🇺🇸 **Bilingual** | Fully separated Chinese & English pages (`apps/` + `apps-en/`) with a "中 \| EN" language pair; Chinese is the default entry |
| 📡 **Free Live Data** | FX / gold / 8-nation indices / 90-day FX history — all free APIs, no key, CORS-friendly |
| 📊 **Multi-Dimension Engine** | Y/W/D/H nested cycle positioning with 4 independent analysis dimensions (fundamental / technical / sentiment / quant) |
| 🛡 **Falsification Conditions** | Every judgment carries explicit invalidation conditions — no hindsight rationalization |
| ⚡ **Zero-Build Deploy** | Pure HTML + CSS + Vanilla JS; runs on GitHub Pages / Nginx / any static server |

---

## 🎯 7 Subsystems

| # | System | Directory | Purpose | Quick Use Case |
|---|--------|-----------|---------|----------------|
| 01 | **Macro Surveillance** | `apps/01-macro-surveillance/` | 5-dimension global stress dashboard | Before the open, check the Composite Stress Index + "Market Contagion" → gauge risk appetite → size positions |
| 02 | **Merrill Clock** | `apps/02-merrill-clock/` | 8-nation synchronized cycle positioning | Select 3 nations → view clock quadrants + 10Y spreads → find arbitrage windows |
| 03 | **Zhou Jintao Cycles** | `apps/03-zhoujintao-cycle/` | Kondratieff 50-60y long waves | Read "Core Conclusions" monthly → calibrate macro strategy → set asset duration |
| 04 | **Fund Flow** ⭐ | `apps/04-fund-flow/` | 8-nation capital chain + live trio | The must-see: top 4-source status → live quotes → central-bank balance sheets |
| 05 | **Stocks·Bonds·FX** | `apps/05-stock-bond-fx/` | 8-nation × 3-market 3D trends | Select 5 nations → check Y/M/W 3D signals → long the strong uptrends |
| 06 | **Gold XAUUSD** | `apps/06-gold-xauusd/` | 4-dimension single-asset deep dive | Intraday: daily signal + candles → mid-term: gold/silver ratio + weights |
| 07 | **FX Major Pairs** | `apps/07-fx-pairs/` | 6 majors × 4D engine (Finance-Emotion Methodology) | Check Y/W/D/H signals pre-trade → enter on multi-dimension resonance → set falsification stops |

> 💡 Subsystem 07 is the **complete practice of the Finance-Emotion Methodology**: 6 selectable major pairs (EUR/USD, USD/JPY, GBP/USD, USD/CHF, AUD/USD, USD/CAD) with a built-in AI research snapshot as fallback — the page still shows authoritative research even if all APIs go down.

### 📐 Finance-Emotion Methodology

A framework that unifies financial analysis (Finance) with market psychology/emotion judgment (Emotion):

```
① Problem Definition → What is this pair trading? (fundamental? momentum? carry?)
② Decomposition       → Fundamentals / Technicals / Sentiment / Quant (4 independent dimensions)
③ Cycle Positioning   → Month (60D+30 momentum) / Week (20D+10) / Day (MA5/20+RSI+MACD) / Hour (5D)
④ Data Evidence       → Free-API real data (open.er-api.com live + frankfurter.dev 90-day history)
⑤ Falsification Test  → 2-3 explicit invalidation conditions per pair (falsifiability > interpretability)
```

> Core principle: **Falsifiability > Interpretability** — every judgment must state its invalidation conditions upfront; honesty about uncertainty beats hindsight rationalization.

---

## 📸 Screenshots

| Portal (Chinese) | FX Major Pairs · Finance-Emotion |
|------------------|----------------------------------|
| ![Portal](_assets/screenshots/portal-top.png) | ![FX Pairs](_assets/screenshots/fx-v14-top.png) |

| Fund Flow · Live Trio | Portal (English) |
|----------------------|------------------|
| ![Fund Flow](_assets/screenshots/flow-en.png) | ![Portal EN](_assets/screenshots/portal-en.png) |

---

## 🧭 Bilingual Architecture

Chinese is the **default entry**; Chinese & English pages are **fully separated** (no JS toggling — SEO-friendly, crawlable):

```
Portal ZH index.html ──EN──→ Portal EN index-en.html
Portal EN index-en.html ──中──→ Portal ZH index.html
apps/XX (ZH) ──EN──→ apps-en/XX (EN)      apps-en/XX (EN) ──中──→ apps/XX (ZH)
```

- Unified brand: **财情双生智库 · Econ-Sentiment Twin Think Tank** (side by side)
- English pages use `<html lang="en">` + dedicated meta descriptions
- All 7 subsystems have both Chinese and English versions (`apps/` + `apps-en/`)

---

## 🚀 Quick Start

```bash
# 1. Clone
git clone https://github.com/YOUR_USERNAME/macro-analysis.git
cd macro-analysis

# 2. Serve locally (any option)
python -m http.server 8080     # Python
npx serve .                    # Node.js

# 3. Open in browser
open http://127.0.0.1:8080/
```

> Or simply double-click `index.html` — every page is a single-file HTML with zero build steps.

---

## 📁 Directory Structure

```
macro-analysis/
├── LICENSE                            ← MIT License
├── README.md                          ← This file (Chinese)
├── README-en.md                       ← English readme
├── .gitignore                         ← Git ignore rules
├── index.html                         ← 🏠 Portal · Chinese (default entry)
├── index-en.html                      ← 🌐 Portal · English
├── _assets/                           ← Shared assets
│   ├── logo.png                       ← Logo (transparent background)
│   └── screenshots/                   ← UI screenshots (referenced by README)
├── apps/                              ← 7 subsystems · Chinese
│   ├── 01-macro-surveillance/index.html
│   ├── 02-merrill-clock/index.html
│   ├── 03-zhoujintao-cycle/index.html
│   ├── 04-fund-flow/
│   │   ├── index.html                 ← v5.0 (latest)
│   │   └── index-v1.html              ← v1.0 (3-nation original)
│   ├── 05-stock-bond-fx/index.html
│   ├── 06-gold-xauusd/
│   │   ├── index.html                 ← v2.0 (latest)
│   │   └── index-v1.html              ← v1.0 (basic)
│   └── 07-fx-pairs/index.html         ← FX Major Pairs · Finance-Emotion
└── apps-en/                           ← 7 subsystems · English (parallel to apps)
    ├── 01-macro-surveillance/index.html
    ├── 02-merrill-clock/index.html
    ├── 03-zhoujintao-cycle/index.html
    ├── 04-fund-flow/index.html
    ├── 05-stock-bond-fx/index.html
    ├── 06-gold-xauusd/index.html
    └── 07-fx-pairs/index.html
```

---

## ⏱ Data Sources & Freshness

| Layer | Data | Frequency | Source |
|-------|------|-----------|--------|
| 🔄 **Live** | FX rates · 8 nations | Daily UTC 00:02 | [open.er-api.com](https://open.er-api.com) |
| | Gold XAUUSD | Second-level | [api.gold-api.com](https://gold-api.com) |
| | CN/US indices | Intraday | [qt.gtimg.cn](https://qt.gtimg.cn) |
| | Nikkei / DAX / FTSE / KOSPI | Intraday | [push2delay.eastmoney.com](https://push2delay.eastmoney.com) |
| | FX majors (live) | Daily UTC 00:02 | open.er-api.com |
| | FX majors (90-day history) | Business-day close | [api.frankfurter.dev](https://frankfurter.dev) |
| 📅 **Official** | M2 / social financing / CB sheets / CPI | Monthly/weekly | Central banks |
| 📊 **Estimates** | Equity/real-estate market cap | Annual snapshot | Exchanges/institutions |
| | TEDPIX / MOEX indices | No free source | ⚠️ Model inference (labeled) |
| 🧠 **Research** | FX research snapshots | Built-in reference | Public info + multi-factor reasoning |

> 📌 Every page shows a **data-source status badge** at the top (live / official / model) and a full "Data Sources & Schedule" table at the bottom.

---

## 🌐 Deployment

### Option 1: GitHub Pages (recommended for open source)

```bash
cd macro-analysis
git init
git add .
git commit -m "feat: Econ-Sentiment Twin Think Tank macro-analysis v1.0 · 7 subsystems (bilingual)"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/macro-analysis.git
git push -u origin main
```

1. GitHub repo → **Settings** → **Pages**
2. Source: **Deploy from a branch** → Branch: **main** / **(root)**
3. Visit: `https://YOUR_USERNAME.github.io/macro-analysis/`

### Option 2: Nginx / BT Panel (current production)

Deployed on Tencent Cloud (Ubuntu 22.04 + BT nginx), listening on port `3050`:

```nginx
server {
    listen 3050;
    server_name 118.25.197.75;
    root /www/wwwroot/118.25.197.75_3050;
    index index.html;
    location / {
        try_files $uri $uri/ =404;
    }
    location ~* \.(png|jpg|svg|css|js)$ {
        expires 30d;   # static asset cache
    }
    location ~* (README|LICENSE|\.gitignore|\.env) {
        return 404;    # sensitive-file protection
    }
}
```

---

## 🎨 Design System

- **Primary background**: Deep Black `#0D0D0F`
- **Secondary background**: Starry Blue `#0A1628`
- **Accent**: Signature Gold `#D4AF37`
- **Up (A-share convention)**: Red `#E53935` · **Down**: Green `#43A047`
- **Typography**: Noto Sans SC / Noto Serif SC / JetBrains Mono

Brand philosophy: **Finance + Emotion twin-born** · Yin-Yang balance · Unity of opposites · Deep, calm, wise · Gold as the accent.

---

## 🛠 Tech Stack

- **Frontend**: Pure HTML + CSS + Vanilla JS (**zero build**, single-file architecture)
- **Charts**: [Chart.js](https://www.chartjs.org/) (CDN)
- **Data**: Free public APIs (no key required)
  - FX: [open.er-api.com](https://open.er-api.com)
  - Gold: [api.gold-api.com](https://gold-api.com)
  - Indices: [qt.gtimg.cn](https://qt.gtimg.cn) + [push2delay.eastmoney.com](https://push2delay.eastmoney.com)
  - FX history: [api.frankfurter.dev](https://frankfurter.dev)
- **Deploy**: Any static server (GitHub Pages / Nginx / CloudStudio / Vercel)

---

## 📋 Version History

| System | Version | Status |
|--------|---------|--------|
| Macro Surveillance | v1.0 | ✅ Stable |
| Merrill Clock | v4.0 | ✅ Stable |
| Zhou Jintao Cycle Report | v5.1 | ✅ Stable |
| Fund Flow Surveillance | v5.0 | ✅ Latest |
| Stocks·Bonds·FX | v1.0 | ✅ Stable |
| Gold XAUUSD | v2.0 | ✅ Stable |
| FX Major Pairs 4D | v1.4 | ✅ Latest (Finance-Emotion) |

---

## 🤝 Contributing

We welcome contributions:

- 🐛 **Report issues**: Open an [Issue](https://github.com/YOUR_USERNAME/macro-analysis/issues) with a bug description or feature request
- 🚀 **Submit code**: Fork → edit → Pull Request
- 📚 **Improve docs**: Fix typos, add translations, enrich use cases
- 📊 **New data sources**: Integrate more free APIs (CORS-friendly preferred)

---

## 📜 Disclaimer

All data on this site is for **research and education only** and is **NOT investment advice**. Markets carry risk; invest with caution. Data comes from free public interfaces and may be delayed or inaccurate; model-inferred values are clearly labeled.

---

## 👤 Author

**Econ-Sentiment Twin Think Tank · 财情双生智库** · Yi He Zhong

*Transform suffering into wisdom · conflict into win-win · worry into growth · let wisdom be warm*

---

## 📄 License

This project is licensed under the **MIT License** (see [LICENSE](LICENSE)).

MIT permits anyone to freely use, copy, modify, merge, publish, distribute, sublicense and/or sell copies of the software, provided the original copyright and permission notices are retained.

### Third-Party Resources

| Resource | Copyright / License |
|----------|---------------------|
| Chart.js (CDN) | MIT License |
| 财情双生 logo | © 2026 Econ-Sentiment Twin Think Tank, all rights reserved (not open under MIT) |
| Free data APIs | Their own terms of service (open.er-api.com / gold-api.com / qt.gtimg.cn / push2delay.eastmoney.com / frankfurter.dev) |
