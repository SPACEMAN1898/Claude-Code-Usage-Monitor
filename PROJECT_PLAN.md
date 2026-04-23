# Claude Code Usage Monitor — Project Plan

**Repo:** `SPACEMAN1898/Claude-Code-Usage-Monitor`  
**Stack:** Python · Claude API usage tracking  
**Branch:** `main`  
**Last Updated:** 2026-04-24  

---

## What It Is

Monitors Claude API / Claude Code token usage over time. Provides reset-hour alignment (`reset_hour_utc`) so the dashboard correctly reflects time-to-reset against Claude.ai's billing cycle.

---

## Current Status

**Maintenance / Utility** — Clean, synced, low-activity.  
Last commit added `reset_hour_utc` parameter for billing cycle alignment. No active development planned.

---

## Phases

### Phase 1 — Core Monitor ✅ COMPLETE
- [x] Usage tracking and reporting
- [x] Version management
- [x] `reset_hour_utc` parameter for billing cycle alignment

---

### Phase 2 — Enhancements 🔲 OPTIONAL
**If usage monitoring becomes critical for Praxentis cost tracking:**

- [ ] Per-project breakdown (which repo/app is consuming most tokens)
- [ ] Budget alerts (Telegram/Slack when usage exceeds threshold)
- [ ] Historical trend graphs
- [ ] Integration with Praxentis billing dashboard
- [ ] **CHECKPOINT:** Monitor shows per-project spend; alert fires when >80% of monthly budget used

---

## Notes

- This is a utility/tooling repo, not a customer-facing product
- Priority: Low — maintain as needed, upgrade only if Claude API costs become a concern
