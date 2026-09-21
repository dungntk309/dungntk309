<div align="center">

# Nguyễn Thị Kim Dung

**Senior QA/QC Engineer · Fintech / Payment · AI-assisted QA**

I test products for a living.  
When a QA workflow annoys me enough, I **vibe-code a tool for it**.

<br/>

![QA](https://img.shields.io/badge/QA%2FQC-Senior-2ea44f?style=flat-square)
![Fintech](https://img.shields.io/badge/domain-fintech%20%2F%20payment-555?style=flat-square)
![AI Assisted](https://img.shields.io/badge/building%20with-AI-7c3aed?style=flat-square)
![Playwright](https://img.shields.io/badge/Playwright-45ba4b?style=flat-square&logo=playwright&logoColor=white)

</div>

---

## 👋 About me

Most of my day-to-day work is still very QA:

- analyze requirements and hunt for gaps;
- test API / Web / Mobile flows;
- validate payment and transaction behavior end-to-end;
- investigate defects through API, DB, logs and integrations;
- automate repetitive checks;
- support regression, release validation and delivery.

The coding part is mostly **AI-assisted / vibe-coded**.

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
**Because copy-pasting a giant QA prompt every time got old — and burned context for no good reason.**

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

Less repeated prompt context, easier versioning, and the QA rules live in Git instead of inside one giant message.

`ChatGPT Web` `Repo-driven workflow` `Context efficiency` `Jira` `Confluence` `ClickUp` `Figma`

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

> **How much repeated prompt/context can I remove by treating Git as the workflow source and ChatGPT Web as the reasoning client?**

---

## 🛠 QA toolbox

**Testing**  
`REST Assured` `Postman` `Newman` `Selenium` `Appium` `Playwright`

**Performance / Data**  
`k6` `Gatling` `SQL` `Database Validation` `Logs`

**Workflow**  
`Jira` `Xray` `Confluence` `Agile / Scrum`

**Things I somehow ended up touching while vibe-coding**  
`TypeScript` `Python` `Bash` `Docker` `GitHub Actions`

---

<div align="center">

### QA first. Code when needed. AI whenever it saves me from repetitive work.

[LinkedIn](https://linkedin.com/in/dung-nguyen-kim) · [Email](mailto:dungntk309@gmail.com)

</div>
