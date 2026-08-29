<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d3b2e,100:2f9e6e&height=170&section=header&text=Karan%20Rajeshbhai%20Mungara&fontSize=36&fontColor=f7f5e8&fontAlignY=34&desc=I%20build%20AI%20systems%20you%20can%20audit&descSize=17&descAlignY=54" alt="Karan Rajeshbhai Mungara — I build AI systems you can audit" width="100%">
</p>

<p align="center">
  <a href="https://withkarann.com"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-withkarann.com-2f9e6e?style=flat-square&logo=firefoxbrowser&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/withkarann/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square"></a>
  <a href="https://x.com/withkarann_"><img alt="X" src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white"></a>
  <a href="https://hackerone.com/withkarann_"><img alt="HackerOne" src="https://img.shields.io/badge/HackerOne-494649?style=flat-square&logo=hackerone&logoColor=white"></a>
</p>

<p align="center">
  <a href="https://cal.com/withkarann/introduction"><img alt="Book a call" src="https://img.shields.io/badge/%F0%9F%93%85%20Book%20a%20call-30%20min%2C%20no%20pitch-2f9e6e?style=for-the-badge"></a>
  <a href="mailto:withkarann@gmail.com"><img alt="Email" src="https://img.shields.io/badge/%E2%9C%89%20Email%20me-1B2B34?style=for-the-badge"></a>
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
<tr>
<td colspan="2" valign="top">

### 🦊 [aifoxx](https://aifoxx.com) &nbsp;<sub>aifoxx.com</sub>
<img src="https://img.shields.io/badge/MIT-open_source-2f9e6e?style=flat-square"> <img src="https://img.shields.io/badge/live-2f9e6e?style=flat-square">

An open, **source-cited** directory of AI tooling — with a trust & security report per vendor.
Every compliance claim links to the vendor's own words, and **`null` means unverified, never `false`** — enforced in the schema, not the style guide.

<div align="center">

| 🧰 AI tools | 🔌 MCP servers | 🎛️ Claude Code skills | 🔍 Trust reports |
|:---:|:---:|:---:|:---:|
| **992** | **1,979** | **1,638** | **980** |

</div>

</td>
</tr>
</table>

---

## 🤖 How this gets built

I dispatch agents rather than typing the code myself — and I can tell you exactly how much,
because I built the tool that measures it. **Across my own projects:**

**From [ClaudeSec](https://github.com/aanjaneyasinghdhoni/ClaudeSec)**, which instruments every tool call my agents make:

| | |
|:--|:--|
| **385,647** | tool-call spans logged, across **146 repositories** and 3 agent harnesses |
| **4,843** | alerts raised on my own agents — 22 critical, 1,046 high |

**From my session transcripts:**

| | |
|:--|:--|
| **836** | subagents dispatched, over 1,358 sessions and 67 project directories |
| **~7 : 1** | agent/CLI actions per hand edit (43,790 Bash+MCP vs 6,382 Edit/Write) |

Every tool call routes through a pre-execution hook into ClaudeSec — so the agents that write my
code are watched by the tool I built to watch agents.

---

## 🧰 Stack

**Security & GRC**

<p>
  <img alt="Burp Suite Pro" src="https://img.shields.io/badge/Burp_Suite_Pro-FF6633?style=flat-square&logo=burpsuite&logoColor=white">
  <img alt="OWASP ZAP" src="https://img.shields.io/badge/OWASP_ZAP-00549E?style=flat-square&logo=zap&logoColor=white">
  <img alt="Nuclei" src="https://img.shields.io/badge/Nuclei-1B2B34?style=flat-square">
  <img alt="Semgrep" src="https://img.shields.io/badge/Semgrep-1B2B34?style=flat-square">
  <img alt="CodeQL" src="https://img.shields.io/badge/CodeQL-181717?style=flat-square&logo=github&logoColor=white">
  <img alt="SonarCloud" src="https://img.shields.io/badge/SonarCloud-126ED3?style=flat-square&logo=sonarqubecloud&logoColor=white">
  <img alt="Socket.dev" src="https://img.shields.io/badge/Socket.dev-C93CD7?style=flat-square&logo=socket&logoColor=white">
  <img alt="Gitleaks" src="https://img.shields.io/badge/Gitleaks-1B2B34?style=flat-square">
  <img alt="TruffleHog" src="https://img.shields.io/badge/TruffleHog-1B2B34?style=flat-square">
  <img alt="OSV-Scanner" src="https://img.shields.io/badge/OSV--Scanner-1B2B34?style=flat-square">
  <img alt="Darktrace" src="https://img.shields.io/badge/Darktrace-1B2B34?style=flat-square">
  <img alt="Drata" src="https://img.shields.io/badge/Drata-1B2B34?style=flat-square">
  <img alt="Vulnerability mgmt" src="https://img.shields.io/badge/Vulnerability_mgmt-1B2B34?style=flat-square">
  <img alt="Bug bounty triage" src="https://img.shields.io/badge/Bug_bounty_triage-1B2B34?style=flat-square">
  <img alt="1Password" src="https://img.shields.io/badge/1Password-1B2B34?style=flat-square">
</p>

**AI & agents**

<p>
  <img alt="Agentic engineering" src="https://img.shields.io/badge/Agentic_engineering-1B2B34?style=flat-square">
  <img alt="Claude" src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white">
  <img alt="Claude Code" src="https://img.shields.io/badge/Claude_Code-191919?style=flat-square&logo=anthropic&logoColor=white">
  <img alt="MCP" src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white">
  <img alt="Codex" src="https://img.shields.io/badge/Codex-1B2B34?style=flat-square">
  <img alt="Cursor" src="https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white">
  <img alt="GitHub Copilot" src="https://img.shields.io/badge/GitHub_Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white">
  <img alt="Antigravity" src="https://img.shields.io/badge/Antigravity-1B2B34?style=flat-square">
  <img alt="Gemini" src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white">
  <img alt="NotebookLM" src="https://img.shields.io/badge/NotebookLM-000000?style=flat-square&logo=notebooklm&logoColor=white">
  <img alt="Deep research" src="https://img.shields.io/badge/Deep_research-1B2B34?style=flat-square">
  <img alt="LM Studio" src="https://img.shields.io/badge/LM_Studio-000000?style=flat-square&logo=lmstudio&logoColor=white">
  <img alt="Hugging Face" src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=white">
  <img alt="ElevenLabs" src="https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white">
  <img alt="Seedance" src="https://img.shields.io/badge/Seedance-1B2B34?style=flat-square">
  <img alt="Lovable" src="https://img.shields.io/badge/Lovable-1B2B34?style=flat-square">
  <img alt="Replit" src="https://img.shields.io/badge/Replit-F26207?style=flat-square&logo=replit&logoColor=white">
  <img alt="v0" src="https://img.shields.io/badge/v0-000000?style=flat-square&logo=v0&logoColor=white">
  <img alt="n8n" src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white">
</p>

**Build**

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">
  <img alt="Deno" src="https://img.shields.io/badge/Deno-000000?style=flat-square&logo=deno&logoColor=white">
  <img alt="Express.js" src="https://img.shields.io/badge/Express.js-0A0A0A?style=flat-square&logo=express&logoColor=white">
  <img alt="Vite" src="https://img.shields.io/badge/Vite-9135FF?style=flat-square&logo=vite&logoColor=white">
  <img alt="Tailwind" src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
  <img alt="GSAP" src="https://img.shields.io/badge/GSAP-0AE448?style=flat-square&logo=gsap&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="C" src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white">
  <img alt="PHP · MySQL" src="https://img.shields.io/badge/PHP_%C2%B7_MySQL-777BB4?style=flat-square&logo=php&logoColor=white">
  <img alt="VS Code" src="https://img.shields.io/badge/VS_Code-1B2B34?style=flat-square">
</p>

**Data & platform**

<p>
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img alt="Vercel" src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white">
  <img alt="Cloudflare" src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white">
  <img alt="nginx" src="https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-1B2B34?style=flat-square">
  <img alt="Azure" src="https://img.shields.io/badge/Azure-1B2B34?style=flat-square">
</p>

**Quality & observability**

<p>
  <img alt="Playwright" src="https://img.shields.io/badge/Playwright-1B2B34?style=flat-square">
  <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white">
  <img alt="Vitest" src="https://img.shields.io/badge/Vitest-00FF74?style=flat-square&logo=vitest&logoColor=white">
  <img alt="pgTAP" src="https://img.shields.io/badge/pgTAP-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Sentry" src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white">
  <img alt="PostHog" src="https://img.shields.io/badge/PostHog-000000?style=flat-square&logo=posthog&logoColor=white">
  <img alt="OpenTelemetry" src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
  <img alt="Git CI/CD" src="https://img.shields.io/badge/Git_CI%2FCD-F03C2E?style=flat-square&logo=git&logoColor=white">
</p>

**Design & workplace**

<p>
  <img alt="UI/UX design" src="https://img.shields.io/badge/UI%2FUX_design-1B2B34?style=flat-square">
  <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white">
  <img alt="Canva" src="https://img.shields.io/badge/Canva-1B2B34?style=flat-square">
  <img alt="Screen Studio" src="https://img.shields.io/badge/Screen_Studio-1B2B34?style=flat-square">
  <img alt="Jira" src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white">
  <img alt="Confluence" src="https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white">
  <img alt="Slack" src="https://img.shields.io/badge/Slack-1B2B34?style=flat-square">
  <img alt="Notion" src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white">
  <img alt="Wispr Flow" src="https://img.shields.io/badge/Wispr_Flow-1B2B34?style=flat-square">
</p>

<br>

<p align="center">
  <sub>Writing about AI-assisted pentesting, local inference for compliance, and shipping with agents → <a href="https://withkarann.com/blog"><b>withkarann.com/blog</b></a></sub>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2f9e6e,100:0d3b2e&height=90&section=footer" width="100%">

<p align="center">
  <b>Working on something where AI meets security?</b><br>
  <a href="https://cal.com/withkarann/introduction">Book 30 minutes</a> &nbsp;·&nbsp; <a href="mailto:withkarann@gmail.com">withkarann@gmail.com</a>
</p>
