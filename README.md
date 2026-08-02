<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=FF6B6B&center=true&vCenter=true&width=600&lines=CrushCheck+%F0%9F%8D%AC;Fair+Difficulty%2C+Not+Forced+Payments;Built+for+AI+SEEKHO+%E2%80%94+Assignment+2" alt="Typing SVG" />

### 🍬 A crowdsourced difficulty & tips companion for Candy Crush Saga players

![Status](https://img.shields.io/badge/status-MVP%20in%20progress-yellow?style=flat-square)
![Tier](https://img.shields.io/badge/tier-Micro-blue?style=flat-square)
![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android-lightgrey?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Made with React Native](https://img.shields.io/badge/made%20with-React%20Native-61DAFB?style=flat-square&logo=react)
![Backend](https://img.shields.io/badge/backend-Supabase-3ECF8E?style=flat-square&logo=supabase)

</div>

---

## 📌 What is this?

**CrushCheck** solves a real, validated problem: Candy Crush Saga players routinely get stuck on levels for days, feeling pushed to spend real money on boosters just to progress. CrushCheck crowdsources real difficulty data from players — showing which levels have a high "forced-purchase rate" *before* you hit them — paired with free, community-submitted strategy tips.

> 📄 Full research, validation, and product plan: [`assignment2.md`](./assignment2.md)

---

## 🎯 The Problem (in one glance)

<div align="center">

| Signal | Finding |
|---|---|
| 🗣️ Negative review mining | Players describe higher levels as "impossible" without spending gold bars |
| 💬 Community dwelling | Decade-old forum threads show the same "stuck for a week, forced to pay" pattern, still active today |
| 📊 Classification | **Painkiller**, not a vitamin — real, recurring financial frustration |

</div>

---

## 🏗️ How it works

```mermaid
flowchart LR
    A[Player stuck on a level] --> B{Check CrushCheck}
    B --> C[View crowdsourced<br/>difficulty score]
    B --> D[Browse free<br/>community tips]
    C --> E[Decide: keep playing<br/>free or skip smart]
    D --> E
    E --> F[Submit own result<br/>back to the community]
    F --> B

    style A fill:#FF6B6B,color:#fff
    style B fill:#4ECDC4,color:#fff
    style E fill:#FFD93D,color:#000
```

---

## ⚙️ Tech Stack

```mermaid
graph TD
    subgraph Client
        RN[React Native<br/>Expo]
    end
    subgraph Backend
        SB[Supabase<br/>Postgres + Auth + Realtime]
    end
    subgraph Payments
        RC[RevenueCat + Stripe]
    end
    subgraph Hosting
        VC[Vercel<br/>Web Dashboard]
    end

    RN --> SB
    RN --> RC
    SB --> VC

    style RN fill:#61DAFB,color:#000
    style SB fill:#3ECF8E,color:#000
    style RC fill:#635BFF,color:#fff
    style VC fill:#000,color:#fff
```

| Layer | Choice | Why |
|---|---|---|
| Frontend | React Native (Expo) | One codebase, two stores, fast solo build |
| Backend | Supabase | Free at 0–1k users, built-in auth + realtime |
| Payments | RevenueCat + Stripe | No custom billing — solved problem, not the moat |
| Hosting | Vercel | Zero-ops deploys for the companion dashboard |

---

## 🗺️ Roadmap

```mermaid
gantt
    title 20-Day Build Timeline
    dateFormat  YYYY-MM-DD
    axisFormat  Day %d
    section Discover
    Discovery memo & community check     :a1, 2026-08-01, 2d
    section Build
    Backend + schema setup               :a2, after a1, 2d
    Core difficulty + tips feature       :a3, after a2, 5d
    Paywall + onboarding                 :a4, after a3, 2d
    section Launch
    Internal bug bash                    :a5, after a4, 2d
    Soft launch                          :a6, after a5, 2d
    Collect feedback                     :a7, after a6, 3d
    Retrospective                        :a8, after a7, 1d
```

- [x] Problem validated with real review + community data
- [x] Product plan documented ([assignment2.md](./assignment2.md))
- [ ] MVP built (difficulty lookup + tips)
- [ ] Subscription paywall live
- [ ] Soft launch to first community
- [ ] User feedback collected
- [ ] Closing retrospective

---

## 💰 Monetization

<div align="center">

| Tier | Price | What you get |
|---|---|---|
| 🆓 Free | $0 | Unlimited difficulty lookups, view top-voted tips |
| ⭐ Premium | $2.99/mo | Unlimited tip submissions, ad-free, early access to new levels |

</div>

---

## 📂 Repo Structure

```
ai-seekho/
├── assignment1.md
├── assignment2.md      ← full product plan (this project)
└── README.md            ← you are here
```

---

## 🙋 Reflection

> The most surprising finding during validation: this exact complaint pattern — "stuck for a week, forced to pay" — shows up in forum posts from over a decade ago *and* in reviews posted this year, almost word for word. That durability is what convinced me this is a real, lasting painkiller and not a passing complaint.

---

<div align="center">

Made with 🍬 and a healthy amount of frustration at energy bars, for **AI SEEKHO**.

</div>
