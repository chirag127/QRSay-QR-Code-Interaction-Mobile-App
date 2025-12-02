--- 
name: Feature / Fix / Refactor PR
about: Template for submitting code changes to QRSay-QR-Code-Interaction-Mobile-App
title: '[FEAT/FIX/CHORE]: Descriptive summary of changes'
labels: needs review
assignees: chirag127
---

# 🚀 QRSay: Pull Request - Technical Submission

Thank you for contributing to the `QRSay-QR-Code-Interaction-Mobile-App` codebase. This template ensures high-velocity, standardized review processes.

## 🎯 Primary Goal of this PR

*(In 1-2 sentences, clearly state the problem solved or the feature introduced. Link to the relevant issue if applicable, e.g., Closes #123)*

## 🛠️ Type of Change

Please select the most relevant type(s) and remove those that do not apply:

- [ ] **Feature:** New user-facing functionality (e.g., adding a new screen, integrating a new QR type).
- [ ] **Fix:** Non-breaking bug correction (e.g., fixing rendering issues, correcting navigation logic).
- [ ] **Chore:** Maintenance, configuration updates, or tooling changes (e.g., updating Expo SDK, dependency bumps, CI pipeline fix).
- [ ] **Refactor:** Code restructuring without changing external behavior (e.g., migrating component state to Zustand, applying Feature-Sliced Design principles).
- [ ] **Documentation:** Changes to `README.md`, `.github` files, or inline comments.

## 📝 Required Checklist (Self-Review Mandatory)

Ensure you have completed all mandatory checks before requesting review.

### Code Quality & Standards
- [ ] My code adheres to the **Apex Technical Standards** (SOLID, DRY, YAGNI) and **TypeScript Strict** mode.
- [ ] I have ensured component logic uses functional components and hooks appropriately.
- [ ] I have verified the changes on both **iOS (Simulator)** and **Android (Emulator/Device)**.
- [ ] All new state management logic utilizes **Zustand** hooks/stores correctly.
- [ ] Formatting and linting checks (`npx biome check --apply`) pass locally.

### Testing & Verification
- [ ] I have added **Vitest** unit tests where applicable (e.g., utility functions, store mutations).
- [ ] All existing tests pass locally.
- [ ] I have manually tested the primary user flow impacted by these changes.
- [ ] I have checked the Expo logs for any critical warnings or performance regressions.

### Documentation
- [ ] If this introduces a new environment variable or configuration, I have updated the `.env.example`.
- [ ] If this affects public API interfaces (internal components), relevant JSDocs have been updated.

## 🧩 Technical Implementation Details

1.  **Affected Modules/Files:** (e.g., `src/features/scanner/ScannerScreen.tsx`, `src/shared/store/qrStore.ts`)
2.  **Architectural Impact:** (e.g., Did you introduce a new feature slice according to FSD principles?)
3.  **Key Decisions:** (Explain any non-obvious design choices or trade-offs made.)

## 📸 Screenshots / Visual Proof (Mandatory for UI/UX Changes)

Please attach screenshots or screen recordings showing the feature working correctly on both platforms (if applicable).

| iOS Preview | Android Preview |
| :---: | :---: |
| *(Attach image/GIF here)* | *(Attach image/GIF here)* |

## 🧪 Testing Instructions for Reviewer

How can the reviewer easily reproduce and verify the successful implementation of this PR?

1.  Checkout this branch: `git checkout <branch-name>`
2.  Install dependencies: `npm install`
3.  Start Expo: `npx expo start`
4.  Navigate to `[Specific Screen/Flow]`.
5.  Expected Behavior: `[Describe what should happen]`