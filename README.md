# Hi, I'm Dung 👋

**Senior QA/QC Engineer · Fintech & Payment · AI-assisted Quality Engineering**

I work across requirement analysis, risk-based testing, API/web/mobile validation, automation, defect investigation, release readiness, and Agile/Scrum delivery.

Lately, I have been building an **evidence-first QA toolchain**: instead of asking AI to trust copied prompts or incomplete connector context, the workflow connects requirements, real visual evidence, private browser execution, and versioned QA rules.

---

## What I build

```text
Requirements / Work Items
Jira · Confluence · ClickUp
          │
          ▼
     TrustMeImQA
   QA reasoning layer
          │
          ├───────────────┐
          │               │
          ▼               ▼
   Archaeopteryx     Figma QA Push
 binary evidence      Figma → Jira
     bridge              evidence
          │               │
          └───────┬───────┘
                  ▼
           inspectable evidence
                  │
                  ▼
       QA analysis / testcases


Private Web / VPN / Credentials
          │
          ▼
 Playwright Visual Bridge
          │
          ▼
 sanitized browser evidence
          │
          ▼
      replaceable AI client
```

The common design principle is simple:

> **Do not ask the model to trust context it cannot verify. Give it reproducible evidence.**

---

## Selected projects

### 🧠 TrustMeImQA
**Evidence-first QA orchestration**

A version-controlled QA workflow source for AI agents working with Jira, Confluence, ClickUp, Figma, runtime evidence, requirement analysis, business-gap review, QC scope planning, and testcase generation.

Key ideas:
- modular skills instead of one giant prompt;
- source-of-truth and freshness validation;
- explicit analyze / generate / mutate boundaries;
- business-gap taxonomy and approval gates;
- cross-repository contracts for evidence handling;
- fail-closed behavior when required evidence is missing.

> Private repository — contains internal QA workflow material.

---

### 🦖 Archaeopteryx
**Provider-based binary evidence bridge**

Uses GitHub Actions as an on-demand bridge to retrieve authenticated binary evidence from Jira, Confluence, and ClickUp when connectors can expose metadata but not the actual file bytes.

Key ideas:
- provider-neutral `evidence-bridge/v1` contract;
- credentials isolated in GitHub Actions Secrets;
- authenticated binary download;
- SHA-256 + manifest validation;
- reproducible GitHub Actions Artifacts;
- batch visual evidence retrieval.

> Private repository — used for authenticated/internal evidence transport.

---

### 🎭 Playwright Visual Bridge
**Private browser execution & evidence for AI**

A TypeScript + Playwright bridge for cases where AI can write tests but cannot directly access an application behind VPN, internal credentials, or a private network.

Key ideas:
- versioned request/evidence contracts;
- self-hosted Playwright execution;
- sanitized DOM/UI/locator evidence;
- private credentials stay on the runner;
- AI-agnostic handoff;
- evidence collection separated from test reasoning.

> Private repository — private-environment execution layer.

---

### 🔌 [Atlassian Visual Bridge](https://github.com/dungntk309/Atlassian-Visual-Bridge)
**Public reference implementation**

A lightweight GitHub Actions bridge that retrieves authenticated Jira and Confluence attachments for AI vision/file analysis when the connector only exposes metadata.

It demonstrates:
- GitHub Actions as a serverless integration layer;
- Jira / Confluence REST integration;
- temporary artifact delivery;
- input validation and failure handling;
- credential isolation with GitHub Actions Secrets.

---

### 🎨 Figma QA Push
**Figma → Jira visual evidence pipeline**

A Figma plugin + local Docker relay that exports selected design nodes and pushes them to Jira as traceable QA evidence.

Key ideas:
- deterministic artifact naming;
- SHA-256 integrity manifest;
- immutable Jira attachment identity;
- local HMAC-authenticated relay;
- downstream compatibility with Archaeopteryx and TrustMeImQA.

> Private repository — currently evolving with the QA evidence toolchain.

---

## QA / Engineering stack

| Area | Tools & practices |
|---|---|
| **Quality Engineering** | Requirement analysis, risk-based testing, functional, integration, regression, negative & E2E testing |
| **API / Web / Mobile** | REST Assured, Postman, Newman, Selenium, Appium, Playwright |
| **Performance / Data** | k6, Gatling, SQL, database validation, network & server logs |
| **Delivery** | Jira, Xray, Confluence, Agile/Scrum, release validation |
| **AI-assisted QA** | Test design, edge-case analysis, requirement-gap analysis, defect/log investigation, automation generation & review |
| **Tooling** | TypeScript, Python, GitHub Actions, Docker, Bash |

---

## How I approach AI-assisted QA

I am interested in QA systems where AI is a **reasoning client**, not the source of truth.

That usually means:

- requirements come from authoritative sources;
- visual evidence is retrieved as real binary data;
- private credentials stay outside the chat;
- contracts are versioned and validated;
- missing evidence blocks conclusions instead of being silently guessed;
- generated testcases remain traceable back to requirements and evidence;
- the AI client can be replaced without redesigning the execution/evidence layer.

---

## Background

I have **5+ years of QA/QC experience** across fintech/payment, ERP, and e-commerce products, covering requirement analysis, API/web/mobile testing, automation, performance testing, production defect investigation, and release validation.

My current focus is the intersection of **Quality Engineering, developer tooling, and AI-assisted workflows**.

---

## Contact

- **LinkedIn:** [linkedin.com/in/dung-nguyen-kim](https://linkedin.com/in/dung-nguyen-kim)
- **Email:** [dungntk309@gmail.com](mailto:dungntk309@gmail.com)

---

<p align="center">
  <i>Quality is easier to trust when the evidence is reproducible.</i>
</p>
