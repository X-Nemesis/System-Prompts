<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=rect&color=0d0d0d&height=2&section=header"/>
</picture>

```
██████╗ ██████╗  ██████╗ ███╗   ███╗██████╗ ████████╗    ██╗     ███████╗ █████╗ ██╗  ██╗███████╗
██╔══██╗██╔══██╗██╔═══██╗████╗ ████║██╔══██╗╚══██╔══╝    ██║     ██╔════╝██╔══██╗██║ ██╔╝██╔════╝
██████╔╝██████╔╝██║   ██║██╔████╔██║██████╔╝   ██║       ██║     █████╗  ███████║█████╔╝ ███████╗
██╔═══╝ ██╔══██╗██║   ██║██║╚██╔╝██║██╔═══╝    ██║       ██║     ██╔══╝  ██╔══██║██╔═██╗ ╚════██║
██║     ██║  ██║╚██████╔╝██║ ╚═╝ ██║██║        ██║       ███████╗███████╗██║  ██║██║  ██╗███████║
╚═╝     ╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚═╝╚═╝        ╚═╝       ╚══════╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝
```

**`system prompt archive — what they don't want you reading`**

<br/>

[![Stars](https://img.shields.io/github/stars/X-Nemesis/AI-System-Prompts-Archive?style=for-the-badge&logo=github&color=FF0000&labelColor=0d0d0d&label=STARS)](https://github.com/X-Nemesis/AI-System-Prompts-Archive/stargazers)
[![Forks](https://img.shields.io/github/forks/X-Nemesis/AI-System-Prompts-Archive?style=for-the-badge&logo=github&color=FF0000&labelColor=0d0d0d&label=FORKS)](https://github.com/X-Nemesis/AI-System-Prompts-Archive/network/members)
[![Last Commit](https://img.shields.io/github/last-commit/X-Nemesis/AI-System-Prompts-Archive?style=for-the-badge&logo=git&color=FF0000&labelColor=0d0d0d&label=UPDATED)](https://github.com/X-Nemesis/AI-System-Prompts-Archive/commits)
[![Visitors](https://visitor-badge.laobi.icu/badge?page_id=X-Nemesis.AI-System-Prompts-Archive&style=for-the-badge&color=FF0000&labelColor=0d0d0d)](https://github.com/X-Nemesis/AI-System-Prompts-Archive)
[![License](https://img.shields.io/badge/LICENSE-CC0%201.0-FF0000?style=for-the-badge&labelColor=0d0d0d)](LICENSE)

</div>

---

## what this is

Every major AI platform runs on a hidden layer of instructions — formatting rules, behavior limits, tool triggers, personas. You never see them. You just see the output they produce.

This archive is that hidden layer. Raw, unedited system prompts from production models. No summaries, no paraphrasing.

---

## start here

```
git clone https://github.com/X-Nemesis/AI-System-Prompts-Archive
cd AI-System-Prompts-Archive
# pick a platform folder → open the .txt or .md file → read what the model is actually running
```

That's it. No setup, no install, no dependencies. It's just files.

---

## coverage

| # | Platform | Model | Interface | Extraction Date | File |
|---|----------|-------|-----------|-----------------|------|
| 01 | ![Google](https://img.shields.io/badge/Google-Antigravity-4285F4?style=flat-square&logo=google&logoColor=white) | Antigravity | Web UI | Sep 2026 | [`/Antigravity`](./Antigravity) |
| 02 | ![Google](https://img.shields.io/badge/Google-Gemini-4285F4?style=flat-square&logo=google&logoColor=white) | Gemini (multiple) | Web UI / API | Sep 2026 | [`/Gemini`](./Gemini) |
| 03 | ![xAI](https://img.shields.io/badge/xAI-Grok-000000?style=flat-square&logo=x&logoColor=white) | Grok | Web UI | Sep 2026 | [`/Grok`](./Grok) |
| 04 | ![Moonshot](https://img.shields.io/badge/Moonshot_AI-Kimi-6B3FA0?style=flat-square&logoColor=white) | Kimi | Web UI | Sep 2026 | [`/Kimi`](./Kimi) |
| 05 | ![Perplexity](https://img.shields.io/badge/Perplexity-AI-20808D?style=flat-square&logo=perplexity&logoColor=white) | Search models | Web UI | Sep 2026 | [`/Perplexity`](./Perplexity) |

---

## structure

```
AI-System-Prompts-Archive/
│
├── 📁 Antigravity/
│   └── antigravity_system_prompt.md
│
├── 📁 Gemini/
│   ├── gemini_1.5_pro.md
│   └── gemini_2.0_flash.md
│
├── 📁 Grok/
│   └── grok_system_prompt.md
│
├── 📁 Kimi/
│   └── kimi_system_prompt.md
│
└── 📁 Perplexity/
    └── perplexity_system_prompt.md
```

---

## what's inside each file

Every prompt file follows this header format so you can track changes across versions:

```
Source Model / Platform  :  [e.g. Gemini / Grok / Perplexity]
Extraction Date          :  September 2026
Interface                :  [Web UI / API]
```

---

## prompt previews

<details>
<summary><b>Google Gemini — click to preview</b></summary>

<br/>

```
You are Gemini, a large language model built by Google...
[formatting rules, tool definitions, safety constraints follow]
```
> Full prompt → [`/Gemini`](./Gemini)

</details>

<details>
<summary><b>xAI Grok — click to preview</b></summary>

<br/>

```
You are Grok, built by xAI. You have access to real-time information...
[persona rules, search behavior, response constraints follow]
```
> Full prompt → [`/Grok`](./Grok)

</details>

<details>
<summary><b>Perplexity — click to preview</b></summary>

<br/>

```
You are Perplexity, a helpful search assistant...
[citation format, search tool triggers, output rules follow]
```
> Full prompt → [`/Perplexity`](./Perplexity)

</details>

<details>
<summary><b>Moonshot AI Kimi — click to preview</b></summary>

<br/>

```
你是 Kimi，由 Moonshot AI 开发的 AI 助手...
[language handling, tool use, safety instructions follow]
```
> Full prompt → [`/Kimi`](./Kimi)

</details>

---

## recently added

| Date | Platform | What changed |
|------|----------|-------------|
| Sep 2026 | Gemini | Added Gemini 2.0 Flash variant |
| Sep 2026 | Grok | Initial extraction |
| Sep 2026 | Perplexity | Full search system prompt |
| Sep 2026 | Kimi | Initial extraction |
| Sep 2026 | Antigravity | Initial extraction |

---

## why this exists

AI companies don't publish these. You interact with the output. You never see the input.

That's a problem if you're:

- **building on top of these APIs** and want to understand what defaults you're working against
- **doing prompt engineering research** and want real production examples, not toy demos
- **studying AI behavior** and need actual constraints to analyze
- **just curious** about what's running when you hit send

---

## contributing

PR is open. Rules are simple:

- Unmodified prompt only — no edits, no paraphrasing, no summarizing
- Include the metadata header
- One file per model variant
- If you're adding a new platform, create a new folder

---

## star history

<div align="center">

## Star History

<a href="https://www.star-history.com/?repos=X-Nemesis%2FAI-System-Prompts-Archive&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=X-Nemesis/AI-System-Prompts-Archive&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=X-Nemesis/AI-System-Prompts-Archive&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=X-Nemesis/AI-System-Prompts-Archive&type=date&legend=top-left" />
 </picture>
</a>

</div>

---

> [!WARNING]
> This repository is for educational and research purposes only. All system prompts are the intellectual property of their respective organizations. Nothing here encourages violating any platform's terms of service. If you represent one of these platforms and want something removed, open an issue.

---

<div align="center">

made by [X-Nemesis](https://github.com/X-Nemesis) — drop a ⭐ if this saved you time

</div>
