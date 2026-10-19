<p align="center">
  <img src="assets/header.svg" alt="Viktor Oleksiukh: technical architect and security officer, builds AI developer tooling" width="100%"/>
</p>

<p align="center">
  <a href="https://linkedin.com/in/viktor-oleksiukh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:oleksuh@gmail.com"><img src="https://img.shields.io/badge/oleksuh@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://bsky.app/profile/stereocoded.bsky.social"><img src="https://img.shields.io/badge/Bluesky-0285FF?style=flat-square&logo=bluesky&logoColor=white" alt="Bluesky"/></a>
  <a href="https://mastodon.social/@stereocode"><img src="https://img.shields.io/badge/Mastodon-6364FF?style=flat-square&logo=mastodon&logoColor=white" alt="Mastodon"/></a>
  <img src="https://img.shields.io/badge/Wrocław%2C%20PL-remote-2F7D4A?style=flat-square" alt="Wrocław, Poland · Remote"/>
</p>

---

I'm the **technical architect and security officer** at a digital agency that builds and runs WordPress platforms for law and financial firms. My job is the layer under the client work: the tools, standards and pipelines that make the whole dev team faster and safer.

These days that mostly means **putting AI into an engineering team in a way that is safe, measurable and actually adopted.**

## 🏗️ What I build at work

The code is closed source, so here are the results. Happy to walk through any of it on a call.

<table>
<tr>
<td width="50%" valign="top">

**🤖 AI coding harness for the dev team**

Claude Code plugins that every developer installs instead of copying configs between 100+ repos. They bundle:
- guards for secrets, commands and branches;
- a quality gate that checks only the changed lines;
- MCP integrations (issue tracker, Figma, hosting, GitHub, Playwright);
- delivery skills, and opt-in telemetry for the rollout.

On the pilot ticket, the work took **45 minutes against a 4-hour estimate**. The plugins have 600+ tests. The rollout is advisory-first: each week one rule moves to strict.

</td>
<td width="50%" valign="top">

**🛡️ Monitoring & security platform**

A Laravel app that watches the whole site fleet:
- plugin and vulnerability inventory (CVSS);
- security-header and CSP grading;
- malware and integrity scans;
- PageSpeed monitoring with regression detection;
- client-ready PDF reports.

Scans run in CI and push signed bundles, so the server never holds production SSH keys.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📄 Document engine**

A drag-and-drop builder in WordPress plus a Node.js + Docker engine that assembles firm-branded Word documents (attorney profiles, practice and industry pages) with a working table of contents, headers and page numbers. It replaced legacy .NET generators that scraped rendered HTML, and avoided a ~$30k/yr SaaS licence. A 237-page book takes about 40 seconds. 400+ tests and 90+ golden pages guard it against visual regressions.

</td>
<td width="50%" valign="top">

**📏 Engineering standards**

Before writing the company's development standards, I measured how the team actually works across 130+ repos and 1,100+ PRs. The result is 14 standards documents and a decision log, turned into tooling that checks them. Plus a layered WordPress security framework and a zero-day response playbook.

</td>
</tr>
</table>

## 🛰️ Side projects

| | Project | What it is | Stack |
|:-:|---|---|---|
| 🎲 | **[inkRPG](https://github.com/codedamage/inkRPG)** | An AI dungeon master for e-readers. It's a single-player tabletop RPG plugin for KOReader: you play authored adventures offline, and when you go off-script a model narrates the outcome as strict JSON that the engine validates. Tested end to end in a Dockerised KOReader emulator. | Lua · LLM · Docker |
| 🎮 | **[Elite-RG35XX](https://github.com/codedamage/Elite-RG35XX)** | A native port of *Elite: The New Kind* to the Anbernic RG35XX handheld. Cross-compiled for armv5te/uClibc through a custom SDL 1.2 backport shim, with a Docker-based headless simulator for screenshots. | C · SDL · Docker |
| 🧠 | **[CodeDex](https://github.com/codedamage/CodeDex)** | A spaced-repetition flashcard app with a hand-rolled SM-2 scheduler and markdown cards. | TypeScript · Next.js |
| 📚 | **epub-translate** 🚧 | Literary EPUB translation with LLMs, built for book series: a series glossary, paragraph-aligned chapters, checks aware of Ukrainian grammatical cases, a repair loop and cost tracking. It grew out of translating novels into Ukrainian for my own reading. | Python · Claude API |

## 🧭 How I work

- **Measure first.** A recommendation starts from data: repo statistics, CVSS, PageSpeed, pilot timings. A number I quote was measured, not estimated.
- **Adoption over purity.** Tooling nobody uses is worth zero. Advisory before strict, few dependencies, few vendors.
- **Systems over one-offs.** If a fix shows up twice, it becomes a tool, a standard or a runbook.
- **AI does the building; engineers own the decisions.** I design the workflow, verify the output and stay responsible for the result.
- **Security-conservative defaults.** Read-only on production, no shared secrets on servers, guardrails before speed.

## 🛠️ Stack

**Daily:**<br/>
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

**AI tooling:**<br/>
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-111111?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-1B2A40?style=flat-square&logo=semgrep&logoColor=white)

**Growing into:**<br/>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)

## 🕹️ Off the clock

I port games to retro handhelds, hack on e-readers (KOReader plugins), and run a self-hosted homelab, because I'd rather own my data and tools. I also fly in X-Plane, explore in Elite Dangerous, paint Warhammer 40k miniatures, and translate the novels I love into Ukrainian for my own shelf.

## 🤝 Let's talk

I'm happy to talk about **AI-assisted developer tooling and rollout**, **platform and security engineering**, and **WordPress architecture at fleet scale**. The fastest way to reach me is [LinkedIn](https://linkedin.com/in/viktor-oleksiukh) or email.
