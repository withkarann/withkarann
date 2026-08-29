<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d3b2e,100:2f9e6e&height=170&section=header&text=Karan%20Rajeshbhai%20Mungara&fontSize=36&fontColor=f7f5e8&fontAlignY=34&desc=I%20build%20AI%20systems%20you%20can%20audit&descSize=17&descAlignY=54" alt="Karan Rajeshbhai Mungara — I build AI systems you can audit" width="100%">
</p>

<p align="center">
  <a href="https://withkarann.com"><img src="https://img.shields.io/badge/Portfolio-withkarann.com-2f9e6e?style=flat-square&logo=firefoxbrowser&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/withkarann/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://x.com/withkarann_"><img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white"></a>
  <a href="https://hackerone.com/withkarann_"><img src="https://img.shields.io/badge/HackerOne-494649?style=flat-square&logo=hackerone&logoColor=white"></a>
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
because I built the tool that measures it. **Across my own projects, not employer work:**

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

**🔐 Security & GRC** &nbsp;
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-000000?style=flat-square&logo=owasp&logoColor=white)
![Nuclei](https://img.shields.io/badge/Nuclei-1B2B34?style=flat-square)
![Semgrep](https://img.shields.io/badge/Semgrep-1B2B34?style=flat-square)
![CodeQL](https://img.shields.io/badge/CodeQL-2088FF?style=flat-square&logo=github&logoColor=white)
![SonarCloud](https://img.shields.io/badge/SonarCloud-F3702A?style=flat-square&logo=sonarcloud&logoColor=white)
![Socket.dev](https://img.shields.io/badge/Socket.dev-6D28D9?style=flat-square)
![Gitleaks](https://img.shields.io/badge/Gitleaks-B91C1C?style=flat-square)
![TruffleHog](https://img.shields.io/badge/TruffleHog-B91C1C?style=flat-square)
![OSV-Scanner](https://img.shields.io/badge/OSV--Scanner-4285F4?style=flat-square&logo=google&logoColor=white)
![Darktrace](https://img.shields.io/badge/Darktrace-1B2B34?style=flat-square)
![Drata](https://img.shields.io/badge/Drata-6D28D9?style=flat-square)
![CycloneDX SBOM](https://img.shields.io/badge/CycloneDX_SBOM-0F766E?style=flat-square)
![1Password](https://img.shields.io/badge/1Password-3B66BC?style=flat-square&logo=1password&logoColor=white)

**🤖 AI & agents** &nbsp;
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-000000?style=flat-square)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white)
![Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white)
![Antigravity](https://img.shields.io/badge/Antigravity-4285F4?style=flat-square&logo=google&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![NotebookLM](https://img.shields.io/badge/NotebookLM-1B72E8?style=flat-square&logo=googlenotebooklm&logoColor=white)
![LM Studio](https://img.shields.io/badge/LM_Studio-000000?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white)
![Lovable](https://img.shields.io/badge/Lovable-FF4785?style=flat-square)
![v0](https://img.shields.io/badge/v0-000000?style=flat-square&logo=v0&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

**⚙️ Build · Data · Platform** &nbsp;

<img src="https://skillicons.dev/icons?i=typescript,react,nextjs,nodejs,deno,vite,tailwindcss,python,c,php&theme=dark" width="428" alt="TypeScript, React, Next.js, Node.js, Deno, Vite, Tailwind, Python, C, PHP"><br>
<img src="https://skillicons.dev/icons?i=postgresql,supabase,sqlite,redis,docker,vercel,cloudflare,nginx,aws,azure&theme=dark" width="428" alt="Postgres, Supabase, SQLite, Redis, Docker, Vercel, Cloudflare, nginx, AWS, Azure">

**🔬 Quality & observability** &nbsp;
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![pgTAP](https://img.shields.io/badge/pgTAP-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry_(EU)-362D59?style=flat-square&logo=sentry&logoColor=white)
![PostHog](https://img.shields.io/badge/PostHog_(EU)-1D4AFF?style=flat-square&logo=posthog&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**🎨 Design & workplace** &nbsp;
![UI/UX](https://img.shields.io/badge/UI%2FUX_design-2f9e6e?style=flat-square)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-00C4CC?style=flat-square&logo=canva&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Wispr Flow](https://img.shields.io/badge/Wispr_Flow-000000?style=flat-square)

<br>

<p align="center">
  <sub>Writing about AI-assisted pentesting, local inference for compliance, and shipping with agents → <a href="https://withkarann.com/blog"><b>withkarann.com/blog</b></a></sub>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2f9e6e,100:0d3b2e&height=90&section=footer" width="100%">
