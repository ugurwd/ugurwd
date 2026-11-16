## Uğur İnal

**Agentic AI Engineer** · multi-agent systems with approval gates, evals and cost control · Python / TypeScript · finance background (Co-Founder, Interim CFO & CIO)

I build AI systems that real people rely on for real decisions, with the checks that make them safe to trust: human approval steps, test gates, cost limits and logs you can audit. I came to software from finance and operations, so I build for the person who has to sign off on the output.

Based in Istanbul · open to full-time remote roles · [LinkedIn](https://linkedin.com/in/ugur-inal) · ugur.inal.ui@gmail.com

---

### Selected work

**AI operating system for a NZ$600m-scale project finance** (Fjordland Group, 2026–)
I run a land-based salmon farm project's finance workstream on a system I built (~110k lines of Python). A 240-month cohort-based financial model, frozen and SHA-256-hashed model runs, 11 release gates, and board, lender and agency packs built by scripts. Re-cutting the model to each investor's term sheet used to take weeks; it now takes hours. The co-founders and the board work from it.

**CandidPnL: a self-improving trading lab that shows every loss** (2026–) · [candidpnl.wakaresearch.com](https://candidpnl.wakaresearch.com)
A rule-based US-equities paper-trading bot with a Claude-driven improvement loop: daily self-review and a hypothesis log, weekly experiments in a sandboxed worktree with an allow-list of editable files, and a backtest gate that tightens with every run to penalise multiple testing. Paper trading only; every trade is published.

**Content agents for a real-estate office** (2026)
A six-agent pipeline (planner, copywriter, designer, brand checker) that turns a brief into a post and sends it to the client as a Telegram approval card. A human publishes. Over the first 20 briefs: 9 approved, 3 cancelled, with total AI cost of $33.

**İvvme: AI health and nutrition coach** (CTO, live) · [app.ivvme.com](https://app.ivvme.com)
Model tiering per task, cost logging on every LLM call, a per-user monthly budget guard, voice meal logging, rules for handing over to a human, and 1,100+ tests. Shipped in short, dated release cycles with a smoke test on every release.

**Te Huata: invoice-to-accounting AI** (Waka Research, live proof of concept)
Invoice → AI account coding → approval by authority limit → Xero, with budget reconciliation. Pilot in contracting.

**Aflaj: digital-twin demo** · [demo](https://aflaj.wakaresearch.com/en/demo-twin/)
An interactive twin of a fictional recirculating-aquaculture facility, with energy, water and heat scenarios.

---

### How I build

- Typed orchestration over frameworks: thin provider adapters (model pinning, cost and token metering, backoff, a fallback provider), with review as a separate call on a different model
- Human-in-the-loop by design: approval cards, four-eyes checks, nothing irreversible without a person
- Gates before release: tests, evals, backtests and hash-chained logs

**Stack:** Python (FastAPI, Pydantic) · TypeScript (Node, React, Next.js, Vite) · PostgreSQL, Redis · Claude, OpenAI, Gemini · Docker, Cloudflare, Vercel, DigitalOcean

---

### Research & recognition

- Co-author, *Leveraging artificial intelligence to democratise access to land and water data in Aotearoa New Zealand: potential and risks.* Local Environment 31(8), Taylor & Francis, 2026. [DOI 10.1080/13549839.2025.2560355](https://doi.org/10.1080/13549839.2025.2560355)
- Kuaha Matihiko: NZ$703k National Science Challenge funding (Our Land and Water, 2022–23); I led its LLM semantic search
- Microsoft for Startups Founders Hub (2025–)

---

### About this profile

My repositories are private because most of them hold client or company work. **I'm happy to give access to specific code when asked:** email me with the project you'd like to see.

*Associate degree, Tourism & Travel Agency Management, Akdeniz University (2010). Software and AI self-taught since 2021.*
