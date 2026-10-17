# Aquarium & Pond Operations Command Center

A zero-dependency, single-page web application designed for multi-system aquatic telemetry tracking, maintenance scheduling, and automated diagnostic calculations. Built specifically to monitor complex freshwater environments (such as low-tech community tanks, high-tech nano setups, and outdoor bog pond ecosystems).

## Features

- **Multi-System Telemetry Dashboard:** Track temperature, pH, carbonate hardness (dKH), general hardness (dGH), total dissolved solids (TDS), ammonia, nitrite, and nitrate across multiple isolated aquatic setups.
- **Interactive Trend Charts:** Powered by **Chart.js** with target baseline range annotations to instantly visualize parameter stability over time.
- **Automated Safety Interlocks:** Real-time checking of parameter thresholds (e.g., flagging low dKH during CO₂ injection or detecting ammonia spikes) to trigger immediate safety alerts.
- **Smart Dosing & Water Change Calculator:** Built-in calculation engine for remineralization products (like *SaltyShrimp GH/KH+*) and carbonate buffers (*Seachem Alkaline Buffer*), complete with osmotic shock guardrails.
- **Data Persistence & Portability:** Uses local browser storage (`localStorage`) for instant access, paired with full JSON export and import capabilities for backup and cross-device sync.

## Supported Systems

1. **20L Community Tank** (Imagitarium 20L, ~16 gal net volume) — Pressurized CO₂, Oase canister filtration, sensitive inverts, and community nano fish.
2. **UNS 45U Betta Tank** (9.3 gal rimless, ~7.5 gal net volume) — Eheim filtration, Fluval Plant LED 4.0, and single-specimen display layout.
3. **Master Outdoor Bog Pond** (~198 gal gross / ~160 gal net volume) — 165-gallon MacCourt basin paired with a 33-gallon up-flow biological bog filter and cold-hardy livestock.

## Tech Stack

- **HTML5 / Vanilla JavaScript (ES6+)** — Zero build tools, serverless, and portable.
- **Tailwind CSS (via CDN)** — Dark-mode "Lab-Lite" aquatic UI design.
- **Chart.js + Annotation Plugin** — High-performance responsive data visualization.

## Getting Started

1. Download or clone `index.html` into your local workspace.
2. Open `index.html` in any modern web browser (Chrome, Safari, Firefox, Edge).
3. (Optional) On mobile devices, use **"Add to Home Screen"** via your browser menu to run it as a standalone web app.
