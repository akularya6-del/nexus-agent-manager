<div align="center">

# nexus-agent-manager

**A multi-model AI debate orchestration engine and dashboard. Coordinates Claude, ChatGPT, Gemini, Perplexity, DeepSeek, Groq, and Mistral in parallel structured rounds.**

![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-Browser_Automation-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

</div>

---

## 📌 Overview

**nexus-agent-manager** is an orchestration workspace that runs multiple leading AI foundation models in parallel structured debate sessions to surface deep insights, cross-validate hypotheses, and synthesize objective consensus.

Rather than relying on restricted API quotas or differing API model behaviors, Nexus utilizes headless/headful browser session coordination (Playwright) to interact directly with native model interfaces using your active browser sessions.

---

## 🔄 The Debate Lifecycle

```
User Prompt
     │
     ▼
[Round 1: Fan-Out] ──► Broadcast question to all active models concurrently
     │
     ▼
[Round 2: Cross-Critique] ──► Feed Model A's response into Model B for rigorous challenge
     │
     ▼
[Round 3: Go Deep] ──► Target core contentions, assumptions, and edge cases
     │
     ▼
[Round 4: Synthesis] ──► Head model generates a balanced, evidence-backed final report
```

---

## ✨ Features

- **Multi-Model Support**: Integrated adapters for ChatGPT, Claude, Gemini, Perplexity, DeepSeek, Grok, and Mistral.
- **Structured Multi-Round Protocols**: Fan-Out, Cross-Examination, Red Teaming, and Final Synthesis.
- **Zero API Key Overhead**: Uses persistent local browser profiles so logins and subscriptions are preserved without per-token billing.
- **Interactive Dashboard**: Modern Next.js interface with real-time streaming, debate transcript logs, and exportable reports.

---

## 🚀 Quickstart

### Prerequisites

- Node.js 18+
- Chromium for Playwright (`npx playwright install chromium`)

### Installation & Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/akularya6-del/nexus-agent-manager.git
   cd nexus-agent-manager
   ```

2. **Install dependencies**:
   ```bash
   npm install
   npx playwright install chromium
   ```

3. **Start development server**:
   ```bash
   npm run dev
   ```

4. **Access the application**:
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📄 License

Distributed under the [MIT License](LICENSE).
