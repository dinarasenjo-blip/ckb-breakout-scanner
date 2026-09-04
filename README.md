[README.md](https://github.com/user-attachments/files/31841098/README.md)
# CKB/USDT 4H Breakout Scanner Pro v4.6

**Real-time professional trading dashboard** for CKB/USDT on Binance.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?style=for-the-badge&logo=vercel)](https://ckb-breakout-scanner.vercel.app)

**Live URL:** [https://ckb-breakout-scanner.vercel.app](https://ckb-breakout-scanner.vercel.app)

---

## Features

- **OBI Real** — Order Book Imbalance from Binance `bookTicker` stream
- **Whale Detector** — Institutional trade detection with dynamic threshold and mega-whale alerts
- **Volume Alarms** — 4H volume anomaly + HFT 10s monitoring
- **Price Alarms** — Take Profit / Stop Loss with directional awareness
- **Long & Short Simulator** — Position simulation with ATR-based targets (TP1 / TP2 / TP3 and SL1 / SL2 / SL3)
- **RVOL Hero** — Relative Volume gauge with session peak tracking
- **Radar de Ignición** — M15 Momentum, H1 Volume Spike, Squeeze Risk
- **Bollinger Bands + ATR** analysis and breakout target calculation
- **Live Order Flow** — Aggressive buy/sell pressure (10s window)
- Ultra-stable WebSocket connection with automatic reconnect and port fallback

---

## Tech Stack

- Pure **HTML + CSS + Vanilla JavaScript**
- Binance REST API + WebSocket streams
- No external frameworks (lightweight, fast, no build step)
- Deployed on **Vercel**

---

## How to run locally

1. Download or clone this repository
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)

No installation or server required.

---

## Deployment

This project is automatically deployed from the `main` branch to Vercel.

Any push to `main` will trigger a new production deployment.

---

## Version

**v4.6** — OBI Real + Ultra-Stable + RVOL Hero

---

## Author

**dinarasenjo-blip**

Data source: [Binance](https://www.binance.com)

---

## Disclaimer

This tool is for educational and informational purposes only.  
It does **not** constitute financial advice. Always do your own research (DYOR) and never risk money you cannot afford to lose.
