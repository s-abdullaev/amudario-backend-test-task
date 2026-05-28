# Backend Engineer Test Task — Amudar.io

Welcome — and thanks for your interest. We're hiring an **AI-Native Backend Engineer** to join [Amudar.io](https://amudar.io) in Tashkent. The full role and offer are in [JOB_DESCRIPTION.md](./JOB_DESCRIPTION.md) (English / Русский / Oʻzbekcha).

This exercise is **not** a coding marathon. We want to see how you think about systems and how you'd use AI tools to ship one — not 40 hours of your weekend.

---

## Scenario — "FieldPulse"

Design the backend for a fictional Amudar.io-style platform:

- **2,000 solar-powered field stations** across rural Uzbekistan.
- Each station sends weather telemetry + pest-trap photos **every 10 minutes** over unreliable cellular.
- The platform must:
  - Ingest data from the devices.
  - Store time-series cheaply.
  - Run a **daily** ML pipeline that predicts pest-outbreak risk per station.
  - Expose a REST API consumed by a web dashboard and a mobile app.
  - Let admins trigger **ad-hoc** model recomputes for a single station.
- Operated by a **2-person team**. Cost-conscious. Must **save device energy**, **conserve cellular traffic**, and **alert on errors or malfunctioning devices**.

---

## Deliverables (bare minimum)

1. **Architecture diagram** — PNG / SVG / Excalidraw / draw.io / Miro link. Your choice of tool.
2. **Written explanation** (2–3 paragraphs) of how you would implement this architecture **using AI tools** (Claude Code, Cursor, or similar). What would you hand to the AI? What would you keep human?
3. **Pros / Cons** of your chosen architecture — a short bulleted list of each.
4. **Key metrics to monitor** — what dashboards and alerts you would set up to know the system is healthy.

We'll discuss the deeper system-design questions with you in person during the interview.

---

## What we evaluate

- Sensible trade-offs over fancy architecture.
- Understanding of failure modes.
- Clear writing.
- Pragmatic choices, not over-engineering.

---

## How to submit

- Combine your diagram + writeup + pros/cons + metrics into a **single PDF or markdown document** (whichever you prefer).
- Send it to **info@amudar.io** *or* Telegram **[@s_abdullaev_uk](https://t.me/s_abdullaev_uk)**.
- Subject line: `Backend Engineer Test Task — [Your Name]`.
- Please mention roughly **how many hours** you spent on it. No deadline pressure.

---

## License

MIT — see [LICENSE](./LICENSE).
