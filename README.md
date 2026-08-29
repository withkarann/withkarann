# Karan Rajeshbhai Mungara

**I build AI systems you can audit.**

Information Security at [Staffbase](https://staffbase.com) — a $1B+ employee communications
company — where I own vulnerability management end to end. Off the clock I build security
tooling around the same idea: it is easy to make AI fast, and hard to make AI provable.

Most teams now have AI writing code, drafting answers and touching production, with no way
to show afterwards what it actually did. That gap is where I work.

📍 Chemnitz, Germany · M.Sc. Web Engineering, TU Chemnitz · [withkarann.com](https://withkarann.com)

---

## What I do at work

| | |
|---|---|
| Vulnerability management | 230+ security issues owned end to end |
| Pentest findings | 140+ retested, including 26 High/Critical |
| Bug bounty | 46 external reports triaged, validated and routed |
| AI vendor reviews | ~4 hours → ~20 minutes, ~$1.67 a run |
| Recognition | **CFO Innovation Award** — the assistant above replaced a commercial tool we were about to buy |

I also run AI-augmented pentests by wiring **Burp Suite Pro to Claude over MCP**, so testing
can be driven in plain language instead of clicking through every step.

---

## Things I've built

### [ClaudeSec](https://github.com/aanjaneyasinghdhoni/ClaudeSec) · AGPL-3.0
Local-first security observability for AI coding agents (Claude Code, Copilot CLI, Codex).
It tails agent transcripts, scores every tool call, and can block a dangerous command before
it runs.

- **673 detection rules** plus a stateful sequence engine — reading `.env` is normal, running
  `curl` is normal, doing both ninety seconds apart is exfiltration
- Every custom regex is compiled through **RE2**, so a user-supplied rule can't ReDoS the host
- **Signed evidence packs** with a hash-chained audit tail — you can prove your own log wasn't
  edited or truncated
- Fully local. Nothing leaves the machine unless you turn it on.

`TypeScript` · `Express` · `Socket.io` · `better-sqlite3` · `RE2` · `OpenTelemetry` · `React 19` · `Docker` · `CodeQL`

### VODP · M.Sc. thesis, TU Chemnitz
*Cost-Effective Vulnerability Scanning and Deduplication Platform for SaaS Security.*
Four scanners, one schema, one list of what's actually real.

- **531 raw findings → 37 canonical submissions** across Burp Suite, ZAP, Nuclei and Dalfox
- Two-stage dedup: exact fingerprint, then `pg_trgm` similarity with weighted fields
- I hand-classified all 531 linkage decisions to get an honest number:
  **99.2% precision, 99.4% recall, 0.8% false-merge rate** *(DVWA benchmark)*
- SUS usability score **82.14** across 14 practitioners
- Automated retest reliability is **explicitly unverified** and named as future work — the
  sample was too small to claim anything

`React` · `Supabase` · `Postgres + pg_trgm` · `Deno Edge Functions` · `n8n` · `Docker`

### Answerdeck · in progress
A compliance intelligence layer for SaaS security teams. Source-grounded answers to security
questionnaires, every one routed through human review.

- Every AI generation writes a **ten-field decision record**, so an auditor can ask why any
  answer was given
- **83 pgTAP tests** over RLS/RBAC, RLS coverage enforced as a CI gate
- EU by design: Supabase EU, Sentry Frankfurt, PostHog EU, consent-gated
- Hand-rolled LLM gateway rather than adopting a dependency after a supply-chain compromise

`Turborepo` · `Supabase + pgvector` · `Deno` · `Semgrep` · `Gitleaks + TruffleHog` · `OSV-Scanner` · `CycloneDX SBOM`

### BrikSync PropOS · private beta
Multi-tenant property operations SaaS, built at Errsol. I designed the RBAC and row-level
security model — then found a cross-tenant leak in my own design.

- Measured with real seeded tokens: **137 foreign rows visible → 0**, with an RLS matrix
  test suite to keep it there
- ~4,400 test cases across 219 test files, 105 migrations
- Custom static checks beyond off-the-shelf tooling: SECURITY DEFINER `search_path` hardening,
  plan-limit sync, public-identity leak detection, circular-import blast radius

`Next.js 16` · `React 19` · `Supabase` · `Upstash Redis` · `Vercel AI Gateway (ZDR)` · `Playwright` · `Semgrep`

### [aifoxx](https://aifoxx.com) · MIT
An open, source-cited directory of AI tooling with a trust report per vendor.

| Tools | MCP servers | Claude Code skills | Trust reports |
|---:|---:|---:|---:|
| 992 | 1,979 | 1,638 | 980 |

Every compliance claim links to the vendor's own words. **`null` means unverified, never
`false`** — enforced in the schema, not just the style guide.

`Vite SSG` · `Fuse.js` · `i18next` · `Firecrawl` · `Playwright` · `release-please`

---

## How I work with AI agents

I run coding agents across five codebases, each with a purpose-written `CLAUDE.md` rather than
a generic template. A few rules I've had to learn the hard way:

- **A UI gate is a UX hint, not a control.** Every enforcement decision lives server-side and,
  where data-shaped, in RLS.
- **A new server action with no test does not push** — checked by script against a ratcheting
  baseline that may only shrink.
- **No self-review by the implementing agent.** Full review on a different, stronger model
  every merge.
- **Identifier drift is greppable; value drift is invisible.** Changing a constant from 1 to 3
  still compiles, still typechecks, still passes a mocked suite — while the seed script, an
  RLS threshold, five `?? 3` fallbacks and four doc pages quietly disagree. So that one gets a
  machine check with no allowlist.
- **The agent may never claim my approval.** Don't write "the founder approved X" unless X was
  actually said — cite the message or the commit.
- Work dispatches in **batches of three**, then a mandatory stop, review, and a deliberately
  fresh context handoff. Long sessions rot.

Model routing is a table, not a vibe: heavy synthesis, security judgement, default
implementation and mechanical fan-out each get a different model.

---

## Currently

Researching Nuclei templating, agentic browsing, and continuous vendor monitoring — likely
landing in aifoxx. Also an active participant in a public cloud-sandbox isolation bug bounty.

Running **Errsol Technologies LLP** since 2019 (DPIIT-recognised, founded at 21 in my third
year of university). Current client work is under NDA.

---

## Elsewhere

[withkarann.com](https://withkarann.com) · [LinkedIn](https://www.linkedin.com/in/withkarann/) · [X](https://x.com/withkarann_) · [HackerOne](https://hackerone.com/withkarann_)

*Writing about AI-assisted pentesting, local inference for compliance, and shipping with
agents at [withkarann.com/blog](https://withkarann.com/blog).*
