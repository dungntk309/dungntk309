<div align="center">

# Nguyễn Thị Kim Dung

**Senior QA/QC Engineer · Fintech / Payment · Web / Mobile Automation**

I test products for a living.  
When a QA workflow annoys me enough, I usually build something to make it less annoying.

<br/>

![QA](https://img.shields.io/badge/QA%2FQC-Senior-2ea44f?style=flat-square)
![Fintech](https://img.shields.io/badge/domain-fintech%20%2F%20payment-555?style=flat-square)
![Selenium](https://img.shields.io/badge/Selenium-Automation-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Appium](https://img.shields.io/badge/Appium-Mobile%20Automation-662D91?style=flat-square)

</div>

---

## 👋 About me

Most of my day-to-day work is very QA:

- analyze requirements and hunt for gaps;
- test API / Web / Mobile flows;
- build and maintain **web/mobile automation mainly with Selenium and Appium**;
- validate payment and transaction behavior end-to-end;
- investigate defects through API, DB, logs and integrations;
- support regression, release validation and delivery.

For side projects, I mostly **vibe-code the implementation, then test the behavior like a QA**.

```text
QA pain point
    ↓
"this is annoying"
    ↓
build a small tool
    ↓
break it like a QA
    ↓
fix / simplify / repeat
```

---

## 🧪 Side projects

### 🧠 TrustMeImQA
**Because copy-pasting a giant QA prompt into every chat got old.**

A repo-driven QA workflow for requirement analysis, gap detection, evidence review, QC scope and testcase generation.

Instead of keeping the whole workflow inside one giant prompt, the repository stores the rules and structure. In **ChatGPT Web**, the chat starts from `AGENTS.md`, routes the task, and loads only the relevant modules.

```text
before
giant prompt + ticket + PRD + evidence

now
ChatGPT Web
     ↓
AGENTS.md
     ↓
route task
     ↓
load relevant QA modules
     ↓
ticket / PRD / evidence
```

I mostly use **ChatGPT Plus + GitHub** for this. Git keeps the QA rules versioned; ChatGPT handles the reasoning; GitHub Actions is just the glue for the parts ChatGPT cannot reach directly.

`ChatGPT Web` `ChatGPT Plus` `Repo-driven workflow` `Jira` `Confluence` `ClickUp` `Figma`

<sub>🔒 Private — contains internal workflow material.</sub>

---

### 🦖 Archaeopteryx
**Because “there is an attachment” is not the same as actually seeing the attachment.**

A GitHub Actions bridge that retrieves authenticated binary evidence from Jira, Confluence and ClickUp so the actual file can be inspected instead of relying only on metadata.

I use GitHub Actions here because the job is short-lived, needs credentials, and only runs when evidence is requested — no separate server needed.

`GitHub Actions` `REST API` `Artifacts` `Visual Evidence`

<sub>🔒 Private — used with internal/authenticated sources.</sub>

---

### 🎭 Playwright Visual Bridge
**Because the browser I need to test is sometimes behind VPN and credentials.**

Runs Playwright where the private environment already exists, then returns sanitized execution/UI evidence.

This is a **side experiment**, not the main automation stack I use day-to-day.

`Playwright` `TypeScript` `Self-hosted Runner` `Private Environment`

<sub>🔒 Private.</sub>

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

## 🧩 What these projects are really about

```text
requirements ──────┐
design ────────────┤
attachments ───────┼──► usable evidence ─► QA analysis / testing
private browser ───┤
logs / runtime ────┘
```

Mostly: keeping QA context, evidence and repetitive workflow steps **traceable, reusable and easier to work with**.

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

**Things I ended up touching while building side tools**  
`Playwright` `TypeScript` `Bash` `Docker` `GitHub Actions`

---

<div align="center">

### QA first. Build tools when they make the QA work better.

[LinkedIn](https://linkedin.com/in/dung-nguyen-kim) · [Email](mailto:dungntk309@gmail.com)

</div>
