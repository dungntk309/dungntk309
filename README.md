<div align="center">

# Nguyễn Thị Kim Dung

**Senior QA/QC Engineer · Fintech / Payment · AI-assisted QA**

I test products for a living.  
When a QA workflow annoys me enough, I **vibe-code a tool for it**.

<br/>

![QA](https://img.shields.io/badge/QA%2FQC-Senior-2ea44f?style=flat-square)
![Fintech](https://img.shields.io/badge/domain-fintech%20%2F%20payment-555?style=flat-square)
![Selenium](https://img.shields.io/badge/Selenium-Automation-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Appium](https://img.shields.io/badge/Appium-Mobile%20Automation-662D91?style=flat-square)
![AI Assisted](https://img.shields.io/badge/building%20with-AI-7c3aed?style=flat-square)

</div>

---

## 👋 About me

Most of my day-to-day work is still very QA:

- analyze requirements and hunt for gaps;
- test API / Web / Mobile flows;
- build and maintain **web/mobile automation mainly with Selenium and Appium**;
- validate payment and transaction behavior end-to-end;
- investigate defects through API, DB, logs and integrations;
- support regression, release validation and delivery.

The coding part of my side projects is mostly **AI-assisted / vibe-coded**.

I am not trying to pretend every side project below was handcrafted line-by-line.

My loop is usually:

```text
QA pain point
    ↓
"this is annoying"
    ↓
vibe-code a tool with AI
    ↓
break it like a QA
    ↓
fix / simplify / repeat
```

---

## 🧪 Side quests I vibe-coded

### 🧠 TrustMeImQA
**Because copy-pasting a giant QA prompt into every chat got old.**

A repo-driven QA workflow for AI agents: requirement analysis, gap detection, evidence review, QC scope and testcase generation.

Instead of pasting the whole QA workflow into every conversation, I use the repository itself as the workflow source. In **ChatGPT Web**, the chat starts from `AGENTS.md`, routes the command, and loads only the modules needed for that task.

```text
before
giant prompt + ticket + PRD + evidence
                ↓
          huge chat context

now
ChatGPT Web
     ↓
AGENTS.md
     ↓
route command
     ↓
load only the QA modules needed
     ↓
ticket / PRD / evidence
```

The point is not token cost — I use ChatGPT Web. The win is cleaner conversations, less prompt stuffing, easier versioning, and QA rules that live in Git instead of being trapped inside one giant message.

**The setup is intentionally lightweight: ChatGPT Plus + GitHub.**  
No separate LLM API billing is needed for my QA reasoning loop.

`ChatGPT Web` `ChatGPT Plus` `Repo-driven workflow` `Modular context` `Jira` `Confluence` `ClickUp` `Figma`

<sub>🔒 Private — contains internal workflow material.</sub>

---

### 🦖 Archaeopteryx
**Because “there is an attachment” is not the same as actually seeing the attachment.**

A GitHub Actions bridge that retrieves authenticated binary evidence from Jira, Confluence and ClickUp so AI/Vision can inspect the real file.

`GitHub Actions` `REST API` `Artifacts` `Visual Evidence`

<sub>🔒 Private — used with internal/authenticated sources.</sub>

---

### 🎭 Playwright Visual Bridge
**Because AI can write Playwright, but my internal app is behind VPN and credentials.**

Run Playwright where the private environment already exists, then send sanitized execution/UI evidence back to the AI.

This is one of my **vibe-coded experiments**, not the main automation stack I use day-to-day.

`Playwright` `TypeScript` `Self-hosted Runner` `Private Environment`

<sub>🔒 Private — execution layer for private environments.</sub>

---

### 🎨 Figma QA Push
**Because sending screenshots around manually is boring.**

A Figma plugin + local relay that pushes selected design frames into Jira as traceable QA evidence.

`Figma Plugin` `Jira` `Docker` `Visual QA`

<sub>🔒 Private.</sub>

---

### 🔌 [Atlassian Visual Bridge](https://github.com/dungntk309/Atlassian-Visual-Bridge)
**The public one.**

A lightweight reference implementation for retrieving authenticated Jira / Confluence attachments through GitHub Actions.

`GitHub Actions` `Jira API` `Confluence API`

---

## 🧩 What all of these are really about

```text
requirement ───────┐
design ────────────┤
attachment ────────┼──► real evidence ─► AI ─► QA reasoning
private browser ───┤
logs / runtime ────┘
```

I am mostly experimenting with two questions:

> **How useful can AI become for QA when it gets real, traceable evidence instead of just copied context?**

> **How much cleaner can the workflow get if Git stores the QA rules and ChatGPT Web only loads what the current task actually needs?**

---

## 🛠 QA toolbox

**Web / Mobile Automation**  
`Selenium` `Appium` `TestNG`

**API Testing / Automation**  
`REST Assured` `Postman` `Newman`

**Performance / Data**  
`k6` `Gatling` `SQL` `Database Validation` `Logs`

**Workflow**  
`Jira` `Xray` `Confluence` `Agile / Scrum`

**Things I somehow ended up touching while vibe-coding**  
`Playwright` `TypeScript` `Python` `Bash` `Docker` `GitHub Actions`

---

<div align="center">

### QA first. Code when needed. AI whenever it saves me from repetitive work.

[LinkedIn](https://linkedin.com/in/dung-nguyen-kim) · [Email](mailto:dungntk309@gmail.com)

</div>
