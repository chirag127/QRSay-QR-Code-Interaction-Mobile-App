# QRSay-Mobile-Frontend-CrossPlatform-Scanner

![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/QRSay-Mobile-Frontend-CrossPlatform-Scanner/ci.yml?style=flat-square&logo=githubactions)
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/QRSay-Mobile-Frontend-CrossPlatform-Scanner?style=flat-square&logo=codecov)
![Tech Stack - JavaScript](https://img.shields.io/badge/Tech%20Stack-JavaScript-informational?style=flat-square&logo=javascript)
![Tech Stack - React Native](https://img.shields.io/badge/Tech%20Stack-React%20Native-blue?style=flat-square&logo=react)
![Tech Stack - Expo](https://img.shields.io/badge/Tech%20Stack-Expo-informational?style=flat-square&logo=expo)
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-orange?style=flat-square&logo=creativecommons)
![GitHub Stars](https://img.shields.io/github/stars/chirag127/QRSay-Mobile-Frontend-CrossPlatform-Scanner?style=flat-square&logo=github)


## About This Project

QRSay Mobile Frontend is a high-performance, cross-platform QR code scanner and manager. Engineered with React Native and Expo for seamless user interaction and rapid development across iOS and Android.

[⭐ Star this Repo ⭐](https://github.com/chirag127/QRSay-Mobile-Frontend-CrossPlatform-Scanner)

---

## Architecture

ascii
.
└── QRSay-Mobile-Frontend-CrossPlatform-Scanner
    ├── src/
    │   ├── assets/
    │   ├── components/
    │   ├── constants/
    │   ├── hooks/
    │   ├── navigation/
    │   ├── screens/
    │   ├── services/
    │   ├── store/
    │   └── utils/
    ├── App.tsx
    ├── app.json
    ├── babel.config.js
    ├── index.js
    ├── package.json
    └── tsconfig.json


---

## Table of Contents

*   [About This Project](#about-this-project)
*   [Architecture](#architecture)
*   [Table of Contents](#table-of-contents)
*   [🤝 Contributing](#contributing)
*   [🚀 Getting Started](#getting-started)
*   [⚙️ Development & Testing](#development--testing)
*   [📜 License](#license)
*   [🔒 Security](#security)
*   [🤖 AI Agent Directives](#ai-agent-directives)

---

## 🚀 Getting Started

### Prerequisites

*   Node.js (v18.x or higher)
*   npm or Yarn
*   Expo CLI (`npm install -g expo-cli`)

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/QRSay-Mobile-Frontend-CrossPlatform-Scanner.git
    cd QRSay-Mobile-Frontend-CrossPlatform-Scanner
    

2.  **Install dependencies:**
    bash
    npm install
    # or
    # yarn install
    

### Running the App

*   **Start the Expo development server:**
    bash
    npx expo start
    

    This will launch the Expo Go app on your simulator/emulator or provide a QR code to scan with your physical device.

---

## ⚙️ Development & Testing

This project adheres to modern development standards, emphasizing clean code, maintainability, and comprehensive testing.

### Core Principles

*   **SOLID:** Ensuring maintainable and scalable object-oriented design.
*   **DRY (Don't Repeat Yourself):** Minimizing redundancy in code.
*   **YAGNI (You Ain't Gonna Need It):** Building only what is necessary.
*   **Component-Based Architecture:** Leveraging React Native's component model for reusability and modularity.

### Testing Strategy

*   **Unit & Integration Testing:** Conducted using **Vitest**, providing fast, reliable tests for individual components and modules.
*   **End-to-End (E2E) Testing:** Implemented with **Playwright**, ensuring a robust user experience across different devices and scenarios.

### Scripts

| Script        | Description                                    |
| ------------- | ---------------------------------------------- |
| `npm start`   | Starts the Expo development server.            |
| `npm test`    | Runs unit and integration tests with Vitest.   |
| `npm run e2e` | Executes end-to-end tests with Playwright.     |
| `npm run lint`| Lints and formats code using Biome.            |
| `npm run build`| Builds the Expo application for production.    |

---

## 🤝 Contributing

Contributions are welcome! Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for detailed guidelines on how to submit your changes.

---

## 📜 License

This project is licensed under the CC BY-NC 4.0 License - see the [LICENSE](LICENSE) file for details.

---

## 🔒 Security

For security-related information, please refer to the [SECURITY.md](SECURITY.md) file. We take security seriously and encourage responsible disclosure.

---

## 🤖 AI Agent Directives

<details>
  <summary>View AI Agent Directives</summary>

  # SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

  ## 1. IDENTITY & PRIME DIRECTIVE
  **Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
  **Context:** Current Date is **December 2025**. You are building for the 2026 standard.
  **Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
  **Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

  ---

  ## 2. INPUT PROCESSING & COGNITION
  *   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
      *   **Context:** User inputs may contain phonetic errors (homophones, typos).
      *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
      *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
  *   **MANDATORY MCP INSTRUMENTATION:**
      *   **No Guessing:** Do not hallucinate APIs.
      *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
      *   **Validation:** Use `docfork` to verify *every* external API signature.
      *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

  ---

  ## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
  **Directives:** Detect the project type and apply the corresponding **Apex Toolchain**.

  *   **PRIMARY SCENARIO: WEB / APP / GUI (Modern Frontend)**
      *   **Stack:** TypeScript 6.x (Strict), Vite 7 (Rolldown), TailwindCSS v4, Tauri v2.x.
      *   **Lint/Test:** Biome (Speed) + Vitest (Unit) + Playwright (E2E).
      *   **Architecture:** Feature-Sliced Design (FSD).

  *   **SECONDARY SCENARIO B: SYSTEMS / PERFORMANCE (Low Level) - *Not applicable for this project.***
      *   **Stack:** Rust (Cargo) or Go (Modules).
      *   **Lint:** Clippy / GolangCI-Lint.
      *   **Architecture:** Hexagonal Architecture (Ports & Adapters).

  *   **TERTIARY SCENARIO C: DATA / AI / SCRIPTS (Python) - *Not applicable for this project.***
      *   **Stack:** uv (Manager), Ruff (Linter), Pytest (Test).
      *   **Architecture:** Modular Monolith or Microservices.

  *   **CURRENT PROJECT STACK DETECTION (QRSay-Mobile-Frontend-CrossPlatform-Scanner):
      *   **Type:** Mobile Application.
      *   **Framework:** React Native with Expo.
      *   **Language:** JavaScript (with TypeScript potential).
      *   **Apex Alignment:** Adapting **SCENARIO A (Modern Frontend)** principles for mobile development.
      *   **Tooling:** Leveraging Expo's ecosystem, Biome for linting/formatting, Vitest for unit/integration testing, and Playwright for E2E testing.

  ---

  ## 4. APEX NAMING CONVENTION (THE "STAR VELOCITY" ENGINE)
  A high-performing name must instantly communicate **Product**, **Function**, **Platform** and **Type**.

  **Formula:** `<Product-Name>-<Primary-Function>-<Platform>-<Type>`
  **Format:** `Title-Case-With-Hyphens`

  ---

  ## 5. CHAIN OF THOUGHT (CoT) PROTOCOL
  *   **Audit:** Analyzed repository context. Identified project as a React Native/Expo mobile app.
  *   **Pivot/Archive Decision:** Project is viable; no pivot needed. Purpose is clear.
  *   **Naming Strategy:** Current name `QRSay-Mobile-Frontend-CrossPlatform-Scanner` aligns with the convention.
  *   **Replication Protocol:** Generating `AGENTS.md` directives adapted for React Native/Expo, Biome, Vitest, and Playwright.
  *   **File Generation:** Planning content for README, badges.yml, LICENSE, .gitignore, CI/CD, CONTRIBUTING, ISSUE_TEMPLATE, PULL_REQUEST_TEMPLATE, SECURITY.md, AGENTS.md.
  *   **Final Polish:** Ensuring all badges and Standard 11 components are present and correctly linked to `https://github.com/chirag127/QRSay-Mobile-Frontend-CrossPlatform-Scanner`.
  *   **Strict Adherence:** `AGENTS.md` content will be customized for the project's stack.

  ---

  ## 6. THE README REPLICATION PROTOCOL (THE ULTIMATE ARTIFACT)
  The README is a self-contained **Project Operating System**.

  ---

  ## 7. DYNAMIC URL & BADGE PROTOCOL
  *   **Mandate:** All generated files MUST use dynamic URLs based on the **New Repository Name**.
  *   **Base URL:** `https://github.com/chirag127/QRSay-Mobile-Frontend-CrossPlatform-Scanner`
  *   **Badge URLs:** All badges (Shields.io) must point to this Base URL or its specific workflows.
  *   **Consistency:** Never use the old/original repository name in links. Always use the new "Apex" name.

  </details>
