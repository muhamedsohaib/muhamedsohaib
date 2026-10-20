## Muhammad Sohaib

I build **AI coding integrations, developer tools, and operational automation** in
Dubai, UAE. I care about what happens beyond the demo: preserving existing setups,
verifying real behavior, and making changes reversible.

My operations background shapes how I build software: turn recurring failures
into testable, reusable tools rather than one-off fixes.

### Core engineering skills

`TypeScript` `JavaScript` `Node.js` `API integrations` `CLI & developer tooling`
`AI coding-agent integrations` `Automated testing (Vitest)` `Configuration safety & rollback`
`Git / GitHub` `Python` `PostgreSQL` `Next.js` `n8n`

## Featured open-source contribution

### Pollinations — Codex and Claude Code router harnesses

**Merged into [Pollinations](https://github.com/pollinations/pollinations) on September 28, 2026.**

I built the Codex Router and Claude Code Router harness adapters for the Polli CLI,
with `on`, `off`, and `status` lifecycle commands. The goal wasn't just to
connect coding agents to another API: it was to make the integration safe to
try in an environment someone already relies on.

- **Protect existing setups:** use supported router configuration paths, keep
  credentials in router-managed storage, and reject changes to configuration
  the integration doesn't own.
- **Make setup reversible:** use an isolated Claude Code Router profile,
  targeted cleanup of Polli-owned state, and rollback when setup checks fail.
- **Verify real behavior:** test streaming, tool calling, and child-key usage
  with actual clients and routers. **19/19 targeted adapter tests passed.**

**Independent recognition:** In October 2026, XERJ selected the merged
implementation for its **Corpus Hub** as an attributed reference for AI coding
agents. My contributor page went live on October 20.

[**Merged pull request #15289**](https://github.com/pollinations/pollinations/pull/15289) ·
[**XERJ Corpus Hub contributor page**](https://hub.xerj.org/contributors/muhamedsohaib) ·
[**LinkedIn write-up**](https://www.linkedin.com/feed/update/urn:li:share:7518309042612797440/)

**Currently building**

- **Project Zero** — an Amazon seller operating layer combining seller data, competitor
  intelligence, deterministic analytics, seller-specific memory and controlled
  automation. Auditable tools with human approval gates rather than black-box agents.
- **Marketplace Decision Brief Generator** — a browser-based CSV tool that compares
  marketplace KPIs against targets and guardrails, ranks operating gaps, and converts
  them into prioritised actions. Keeps observed facts, hypotheses, recommendations and
  unknowns explicitly separated.

**Background**

Currently working at the intersection of marketplace operations, AI integrations,
and workflow automation.

BBA — NUST Business School.

---

[LinkedIn](https://www.linkedin.com/in/muhamedsohaib/) · muhammadsohaibsaif@gmail.com
