# Gym Business Audit System

A complete B2B consulting product built for CrossFit and boutique fitness gym owners. Conceived, designed, and deployed at **Wodapalooza** (Miami, FL) as a live lead qualification and business development tool.

---

## What this is

Most gym owners know something is wrong with their business. They just cannot name it. This system gives them a name for it in under 3 minutes, and gives me a structured entry point for a consulting conversation.

It is built around four revenue pillars: **Retention, Revenue, Acquisition, and Systems.** Every gym has gaps in at least two of them. The audit surfaces which ones, scores the gym's health out of 100, and generates a prescription report — all without a spreadsheet or a discovery call.

---

## What is in this folder

| File | What it is |
|---|---|
| `GymQuickAudit.html` | Interactive lead capture quiz with real-time revenue gap calculation and hidden admin panel. Mobile-first, single HTML file, no dependencies. |
| `gym-audit-template.md` | Reusable 100-point video call diagnostic. Used for pre-call intake and post-call reporting. |
| `Gym_Audit_Report_Sample.pdf` | Anonymized sample audit report delivered to a gym owner after a consulting engagement. |
| `Unbroken_Dynamics_Partnership_Deck.pptx` | B2B partnership pitch deck used with gym software vendors and coaching organizations. |

---

## How the HTML tool works

1. Gym owner answers 12 questions across the four pillars
2. Real-time score updates as they go (0-100 health score)
3. On submit: they see their score, top gaps, and a prioritized prescription
4. Their data is captured in browser localStorage and accessible via a hidden admin panel (tap the footer 5 times)
5. Admin panel shows all leads, scores, and a breakdown by pillar

**Tech:** Vanilla HTML/CSS/JS. No backend, no dependencies, no API keys. Intentional — it needs to run on a phone at a noisy gym expo with spotty wifi.

---

## Why this exists in a CS/IM portfolio

Customer success is not just about managing accounts after the sale. It is about understanding a customer's business well enough to diagnose it, prescribe a fix, and get them to act on it.

This tool does that. It also demonstrates:

- **Systems thinking** — four-pillar framework, scoring logic, weighted gap analysis
- **Product sense** — mobile-first UX, admin panel for lead management, offline-capable design
- **AI-augmented workflow** — built with Claude as a co-builder; the framework, copy, and scoring weights all went through multiple iteration cycles
- **Real deployment** — this ran at a live industry event, not a classroom project

---

*Part of the [portfolio](https://github.com/matthieuvanderelst/portfolio) of Matthieu Vander Elst.*
