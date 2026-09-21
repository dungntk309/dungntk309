# Hi, I'm Dung 👋

**Senior QA/QC Engineer** working mainly with fintech/payment products, API/web/mobile testing, automation, performance testing, defect investigation, and release validation.

I also build small QA tools and experiments with AI.

> **I vibe-code the implementation, then QA the behavior.**

## Vibe-coded QA projects

These are side projects I build mostly with AI-assisted / vibe coding to solve problems I run into while doing QA work.

### TrustMeImQA
A version-controlled QA workflow source for AI agents.

It connects requirement analysis, gap detection, visual evidence, testcase planning, and testcase generation across Jira, Confluence, ClickUp, and Figma.

**Why I made it:** I was tired of pasting huge QA prompts into every chat and getting inconsistent results.

`AI-assisted` · `QA workflow` · `Jira` · `Confluence` · `ClickUp` · `Figma`

---

### Archaeopteryx
A binary evidence bridge for Jira, Confluence, and ClickUp.

It uses GitHub Actions to retrieve authenticated attachments and package the real files for AI/Vision analysis without putting credentials in the chat.

**Why I made it:** connectors could tell the AI that a screenshot existed, but the AI still couldn't actually see it.

`GitHub Actions` · `API` · `Artifacts` · `Visual Evidence`

---

### Playwright Visual Bridge
A bridge between AI-generated Playwright work and private/internal web environments.

The browser runs where the VPN, session, and credentials already exist, then returns sanitized evidence instead of exposing the private environment to the AI.

**Why I made it:** chat AI can write Playwright, but it usually cannot run against the internal app I am testing.

`Playwright` · `TypeScript` · `Self-hosted Runner` · `AI`

---

### Figma QA Push
A Figma plugin + local relay for pushing selected design frames into Jira as QA evidence.

**Why I made it:** design evidence should be attached to the ticket with traceable identity instead of living in screenshots scattered across chats.

`Figma Plugin` · `Jira` · `Docker` · `Visual QA`

---

### [Atlassian Visual Bridge](https://github.com/dungntk309/Atlassian-Visual-Bridge)
Public reference version of the authenticated Jira / Confluence attachment bridge.

`GitHub Actions` · `Jira API` · `Confluence API`

---

## The bigger idea

```text
Jira / Confluence / ClickUp / Figma
                │
                ▼
          real evidence
                │
                ▼
              AI
                │
                ▼
       QA reasoning / tests
```

I am experimenting with one simple idea:

**AI is much more useful for QA when it can work from real, traceable evidence instead of copied context and guesses.**

## QA stack

`REST Assured` · `Postman` · `Newman` · `Selenium` · `Appium` · `Playwright`  
`k6` · `Gatling` · `SQL` · `Jira` · `Xray` · `Confluence`

## Contact

[LinkedIn](https://linkedin.com/in/dung-nguyen-kim) · [Email](mailto:dungntk309@gmail.com)