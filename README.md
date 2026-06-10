# # SP War Room — Mapa Vivo de Ameaças

**A threat analysis simulation game for security and intelligence professionals.**

🔗 [Play the game](https://flahbocchino.github.io/sp-war-room) · 🇧🇷 Bilingual: PT / EN

---

## What is this?

SP War Room is an interactive intelligence analysis simulator set in São Paulo.

You play as the on-call analyst. Incidents arrive in real time — protests, phishing alerts, suspicious vehicles, anonymous tips, political pressure. Your job is to triage, investigate, prioritize, and produce the executive briefing before time runs out.

The game is not about reflexes. It is about analytical reasoning under pressure.

---

## Gameplay

Each session simulates an operational shift with four phases:

| Phase | What you do |
|---|---|
| **1 — Triage** | Read each incident. Flag for investigation, escalate, or dismiss. |
| **2 — Investigation** | Request additional information. Each query costs 30 seconds. |
| **3 — Prioritization** | Choose which incidents make it into the briefing. Slots are limited. |
| **4 — Briefing** | Write the executive report. The AI evaluates your product. |

---

## Difficulty levels

| Level | Incidents | Time | What changes |
|---|---|---|---|
| 🟢 Junior Analyst | 3–5 | 8 min | Clear sources, pre-indicated confidence, no noise traps |
| 🟡 Mid-Level Analyst | 6–10 | 6 min | Conflicting sources, some pure noise, justification required |
| 🔶 Senior Analyst | 10–15 | 4 min | Planted disinformation, anonymous sources, confirmation bias assessed |
| 🔴 Red Noise | 8+ | 3 min | Everything looks like a threat. Almost nothing is. Political pressure simulated. |

---

## Scoring

- **+20 pts** — Real incident correctly included in the briefing
- **+10 pts** — Noise correctly dismissed
- **−15 pts** — False alarm included in the briefing
- **−20 pts** — Real threat dismissed
- **+ Bonus** — Briefing quality evaluated by AI: structure, volume, recommendation language

---

## Why I built this

I work as a security and intelligence analyst in a diplomatic environment. My daily work involves exactly what this game simulates: receiving fragmented information from multiple sources, evaluating reliability, managing noise, and producing intelligence products under time constraints.

I built SP War Room to make that work visible — not through a resume bullet, but through something anyone can experience directly.

The incident scenarios are fictional but grounded in real operational patterns: protest monitoring, phishing alerts, surveillance indicators, vendor data breaches, political pressure on analytical products, and the specific challenge of Red Noise — the environment where everything looks urgent and almost nothing is.

---

## Technical notes

- Pure HTML, CSS, and JavaScript — no frameworks, no dependencies
- Fully bilingual (Portuguese / English) with real-time language toggle
- Mobile responsive
- Hosted via GitHub Pages
- All incident data is procedurally organized per level — no two shifts are identical in feel

---

## About the author

**Flávia Bocchino**
Security & Intelligence Analyst | OSINT | Risk Assessment | CTI

São Paulo, Brazil

[LinkedIn](https://linkedin.com/in/flaviabocchino) · [GitHub](https://github.com/flahbocchino)

---

© Flávia Bocchino — All rights reserved.
