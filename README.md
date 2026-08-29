<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d3b2e,100:2f9e6e&height=170&section=header&text=Karan%20Mungara&fontSize=44&fontColor=f7f5e8&fontAlignY=34&desc=I%20build%20AI%20systems%20you%20can%20audit&descSize=17&descAlignY=54" alt="Karan Mungara — I build AI systems you can audit" width="100%">
</p>

<p align="center">
  <a href="https://withkarann.com"><img src="https://img.shields.io/badge/Portfolio-withkarann.com-2f9e6e?style=for-the-badge&logo=firefoxbrowser&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/withkarann/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://x.com/withkarann_"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"></a>
  <a href="https://hackerone.com/withkarann_"><img src="https://img.shields.io/badge/HackerOne-494649?style=for-the-badge&logo=hackerone&logoColor=white"></a>
</p>

<p align="center">
  <b>Information Security @ Staffbase</b> &nbsp;·&nbsp; Security automation, AI tooling & GRC engineering &nbsp;·&nbsp; Chemnitz 🇩🇪
</p>

---

### It is easy to make AI **fast**. It is hard to make AI **provable**.

Most teams now have AI writing code, drafting answers and touching production — with no way to
show afterwards what it actually did. Everything I build closes that gap.

---

## 🛡️ At Staffbase &nbsp;<sub><sup>$1B+ employee communications company</sup></sub>

I own vulnerability management end to end — then automate the rest of the security team's work
so our hours go to judgement instead of copy-paste.

| | |
|:--|:--|
| 🎯 **Vulnerability management** | 230+ issues owned · 140+ pentest findings retested (26 High/Critical) · 46 bug-bounty reports triaged |
| ⚡ **AI vendor reviews** | ~4 hours → **~20 minutes**, at ~$1.67 a run |
| 📋 **GRC automation** | 10+ security questionnaires in 3–4 days. Biggest was **900+ true/false questions — one wrong answer** |
| 💰 **ROI, not procurement** | Accurate enough that we **cancelled the commercial tool** we were evaluating |
| 🏆 **Recognition** | **CFO Innovation Award** |
| 🔍 **AI-augmented pentesting** | Burp Suite Pro wired to Claude over MCP — testing driven in plain language |

> The thread through all of it: **get real ROI out of the AI you already pay for, instead of buying the next tool.**

---

## 🔨 What I'm building

<table>
<tr>
<td width="50%" valign="top">

### 🔒 [ClaudeSec](https://github.com/aanjaneyasinghdhoni/ClaudeSec)
<img src="https://img.shields.io/badge/AGPL--3.0-open_source-2f9e6e?style=flat-square"> <img src="https://img.shields.io/badge/673-detection_rules-1B2B34?style=flat-square">

Local-first security observability for AI coding agents. Tails agent transcripts, scores every
tool call, blocks dangerous commands before they run.

- **Stateful sequence engine** — reading `.env` is fine, running `curl` is fine, doing both 90 seconds apart is exfiltration
- Every custom regex compiled through **RE2** — a user rule can't ReDoS your host
- **Signed, hash-chained evidence** — prove your own audit log wasn't edited

</td>
<td width="50%" valign="top">

### 🎯 [VODP](https://vodp.dev) &nbsp;<sub>vodp.dev</sub>
<img src="https://img.shields.io/badge/M.Sc._thesis-TU_Chemnitz-4169E1?style=flat-square"> <img src="https://img.shields.io/badge/531→37-findings-1B2B34?style=flat-square">

Four scanners in, one honest list out. Burp Suite, ZAP, Nuclei and Dalfox normalised,
deduplicated, auto-retested.

- **531 raw findings → 37 real ones**
- I hand-classified all 531 decisions: **99.2% precision · 99.4% recall · 0.8% false-merge** <sub>(DVWA benchmark)</sub>
- Retest reliability **published as unverified** — the sample was too small to claim it

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📋 [Answerdeck](https://answerdeck.app) &nbsp;<sub>answerdeck.app</sub>
<img src="https://img.shields.io/badge/in_progress-F59E0B?style=flat-square"> <img src="https://img.shields.io/badge/EU-by_design-0F766E?style=flat-square">

A compliance intelligence layer for SaaS security teams. Source-grounded questionnaire answers,
every one through human review.

- Every AI generation writes a **10-field decision record** — an auditor can ask *why*
- **83 pgTAP tests** over RLS/RBAC; RLS coverage enforced as a CI gate
- Supabase EU · Sentry Frankfurt · PostHog EU

</td>
<td width="50%" valign="top">

### 🏢 [BrikSync PropOS](https://briksync.com) &nbsp;<sub>briksync.com</sub>
<img src="https://img.shields.io/badge/private_beta-6D28D9?style=flat-square"> <img src="https://img.shields.io/badge/~4,400-tests-1B2B34?style=flat-square">

Multi-tenant property operations SaaS. I designed the RBAC + row-level-security model — then
found a cross-tenant leak in my own design.

- Measured with real tokens: **137 foreign rows → 0**
- 219 test files · 105 migrations
- Custom checks: `SECURITY DEFINER` search_path, plan-limit sync, identity-leak detection

</td>
</tr>
</table>

### 🦊 [aifoxx](https://aifoxx.com) &nbsp;<sub>aifoxx.com · MIT</sub>

An open, **source-cited** directory of AI tooling — with a trust & security report per vendor.

<div align="center">

| 🧰 AI tools | 🔌 MCP servers | 🎛️ Claude Code skills | 🔍 Trust reports |
|:---:|:---:|:---:|:---:|
| **992** | **1,979** | **1,638** | **980** |

</div>

Every compliance claim links to the vendor's own words. **`null` means unverified, never `false`** — enforced in the schema, not the style guide.

---

## 🧰 Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=typescript,react,nextjs,nodejs,deno,vite,tailwindcss&theme=dark" alt="TypeScript, React, Next.js, Node.js, Deno, Vite, Tailwind"><br>
  <img src="https://skillicons.dev/icons?i=postgresql,supabase,sqlite,redis,vercel,cloudflare,docker,nginx&theme=dark" alt="Postgres, Supabase, SQLite, Redis, Vercel, Cloudflare, Docker, nginx"><br>
  <img src="https://skillicons.dev/icons?i=githubactions,sentry,vitest,bash,linux,workers,grafana&theme=dark" alt="GitHub Actions, Sentry, Vitest, Bash, Linux, Workers, Grafana">
</p>

**🔐 Security** &nbsp;
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-000000?style=flat-square&logo=owasp&logoColor=white)
![Nuclei](https://img.shields.io/badge/Nuclei-1B2B34?style=flat-square)
![Semgrep](https://img.shields.io/badge/Semgrep-1B2B34?style=flat-square)
![CodeQL](https://img.shields.io/badge/CodeQL-2088FF?style=flat-square&logo=github&logoColor=white)
![SonarCloud](https://img.shields.io/badge/SonarCloud-F3702A?style=flat-square&logo=sonarcloud&logoColor=white)
![Socket](https://img.shields.io/badge/Socket.dev-6D28D9?style=flat-square)
![Gitleaks + TruffleHog](https://img.shields.io/badge/Gitleaks_+_TruffleHog-B91C1C?style=flat-square)
![OSV-Scanner](https://img.shields.io/badge/OSV--Scanner-4285F4?style=flat-square&logo=google&logoColor=white)
![CycloneDX](https://img.shields.io/badge/CycloneDX_SBOM-0F766E?style=flat-square)
![pgTAP](https://img.shields.io/badge/pgTAP_RLS_suites-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**🤖 AI & agents** &nbsp;
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Vercel AI Gateway](https://img.shields.io/badge/Vercel_AI_Gateway-000000?style=flat-square&logo=vercel&logoColor=white)
![Local LLMs](https://img.shields.io/badge/Local_LLMs_(LM_Studio,_Gemma)-000000?style=flat-square&logo=ollama&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

---

## 🤖 How I run AI agents in production

Five codebases, each with a purpose-written `CLAUDE.md`. Rules I learned the hard way:

> 🚧 **A UI gate is a UX hint, not a control.** Every enforcement decision lives server-side and, where data-shaped, in RLS.

> 🧪 **A new server action with no test does not push.** Script-enforced against a ratcheting baseline that may only shrink.

> 👀 **No self-review by the implementing agent.** Full review on a different, stronger model, every merge.

> 🕵️ **Identifier drift is greppable. Value drift is invisible.** Changing a constant from 1 to 3 still compiles, still typechecks, still passes a mocked suite — while a seed script, an RLS threshold, five `?? 3` fallbacks and four doc pages quietly disagree. That one gets a machine check with **no allowlist**, on purpose.

> ✋ **The agent may never claim my approval.** Don't write "the founder approved X" unless X was actually said — cite the message or the commit.

Work dispatches in **batches of three**, then a mandatory stop, review, and a deliberately fresh
context handoff. Long sessions rot. Model routing is a table, not a vibe.

---

## 🔬 Currently

Researching **Nuclei templating**, **agentic browsing** and **continuous vendor monitoring** — likely landing in aifoxx.
Active in a public cloud-sandbox isolation bug bounty.

Running **[Errsol Technologies LLP](https://errsol.com)** since 2019 — DPIIT-recognised, founded at 21 in my third year of university. Current client work is under NDA.

<br>

<p align="center">
  <sub>Writing about AI-assisted pentesting, local inference for compliance, and shipping with agents → <a href="https://withkarann.com/blog"><b>withkarann.com/blog</b></a></sub>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2f9e6e,100:0d3b2e&height=90&section=footer" width="100%">
