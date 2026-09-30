# Gemini Bridge

### Energy connects AI.

[![Beta](https://img.shields.io/badge/status-public_beta-6c63ff)](https://github.com/AlphaStudioDE/gemini-bridge/releases)
[![Windows](https://img.shields.io/badge/platform-Windows_x64-1484ff)](https://github.com/AlphaStudioDE/gemini-bridge/releases)
[![Release](https://img.shields.io/badge/release-0.9.99-38c8ff)](https://github.com/AlphaStudioDE/gemini-bridge/releases)

**Gemini Bridge is a Windows desktop assistant that connects Codex with Gemini and turns separate AI tools into one practical workflow.**

Instead of asking Codex to spend its entire context and token budget reading a large project, exploring many files, or preparing a long analysis, Gemini Bridge can delegate substantial work to Gemini. Codex can then focus on what it does best: supervising the task, reviewing the result, checking changes, and integrating the final answer.

The goal is simple: **use the right intelligence for the right part of the job.**

> Gemini Bridge is currently available as a public beta. The source code is not published at this stage.

## Why Gemini Bridge?

Complex project work often requires much more than one prompt and one answer. A model may need to inspect many files, understand architecture, compare approaches, implement changes, run tests, and independently review the result.

Gemini Bridge makes this collaboration easier:

1. You describe the goal once.
2. The bridge selects or follows the workflow you choose.
3. Gemini performs delegated analysis or project work.
4. Codex can verify the result, review the changes, and continue from a more focused context.

For suitable tasks, this can reduce the amount of project material Codex must process directly and help preserve its token budget for decisions, verification, and final integration. Actual savings depend on the task, selected strategy, models, and amount of verification required.

## Highlights

### Intelligent delegation

- Delegate long-context analysis, project exploration, implementation, testing, or independent review.
- Choose fast, project-oriented, expert, manual, or hybrid strategies.
- Keep lightweight tasks lightweight while reserving stronger models for work that genuinely benefits from them.

### Hybrid AI workflows

Gemini Bridge can coordinate workflows in which one model prepares an architecture, another implements it, and Codex verifies the final result. It can also use independent approaches for difficult decisions and combine the strongest parts of both.

### A more token-conscious Codex workflow

- Let Gemini perform expensive project reading or broad analysis.
- Return a focused result instead of repeating the entire project context.
- Use Codex for supervision, diff review, tests, and integration.
- Avoid delegating trivial work when the coordination overhead would cost more than it saves.

### Voice control

Work with the assistant through several voice options:

- Gemini Live for natural real-time conversation;
- Gemini REST voice workflow;
- local Whisper + Piper;
- Windows system speech.

Gemini Bridge supports push-to-talk, continuous conversation, hands-free activation, spoken summaries, and configurable response voices.

### Mini Panel for Windows

Turn Gemini Bridge into a compact Windows workspace:

- an animated assistant bar at the top of the desktop;
- a task and result panel on the left or right edge;
- remembered panel placement;
- manual and automatic hiding;
- edge handles for quick restoration;
- adjustable colour and background transparency.

### Guided setup

The first-run wizard helps prepare the required connection, authentication, optional Codex integration, voice components, and final connection test. It is designed so that a new user does not need to understand the underlying tools before starting.

### Seven interface languages

The application currently supports:

- English;
- German;
- French;
- Polish;
- Spanish;
- Brazilian Portuguese;
- Italian.

Gemini Bridge follows the main Windows language when supported and falls back to English when necessary.

### Local control and transparent permissions

- Choose restricted access to the selected project or full computer access for tasks that require it.
- Writable delegation can create recovery points before project changes.
- Credentials remain handled by the official authentication flow or by an API key explicitly supplied by the user.
- Problem reports are never sent silently: the user sees and approves the report content first.

## Download the public beta

Download the newest installer from **[GitHub Releases](https://github.com/AlphaStudioDE/gemini-bridge/releases)**.

Current beta:

```text
Gemini Bridge 0.9.99
Windows x64
```

The beta installer is not yet signed with a commercial Authenticode certificate. Windows SmartScreen may therefore display an **Unknown publisher** warning. Verify the SHA-256 checksum shown in the release notes before running the installer.

## Getting started

1. Download the installer from the latest release.
2. Run the installer and open Gemini Bridge.
3. Start the guided configuration wizard.
4. Connect the supported Google authentication method.
5. Optionally install the Codex plugin and voice components.
6. Run the final connection test.
7. Describe a task, select a strategy, and start your first delegation.

## Beta feedback

This release is intended for early testers. Reports about setup, reliability, accessibility, translations, voice behaviour, Mini Panel layout, and real-world project workflows are especially valuable.

- Use the repository's **Issues** section for public, non-sensitive reports.
- Use **synqlet.apps@gmail.com** when a report should not be public.
- Never include passwords, API keys, OAuth codes, private source files, or other secrets in a report.

## Support the project

If Gemini Bridge helps your work and you would like to support its continued development:

- [PayPal](https://paypal.me/damianbor)
- [Buy Me a Coffee](https://buymeacoffee.com/damianborkh)

## Polish summary / Podsumowanie po polsku

**Gemini Bridge łączy Codex z Gemini i pozwala dzielić pracę pomiędzy różne modele AI.** Gemini może wykonywać obszerne analizy, czytać większe projekty lub realizować oddelegowane zadania, a Codex może skupić się na nadzorze, sprawdzaniu zmian, testach i integracji wyniku. W odpowiednich zadaniach pomaga to oszczędzać kontekst oraz tokeny Codexa, bez rezygnowania z końcowej kontroli jakości.

Aplikacja oferuje sterowanie głosowe, kreator konfiguracji, siedem języków interfejsu, strategie automatyczne i hybrydowe oraz kompaktowy Mini Panel zintegrowany z pulpitem Windows.

## Author

Created by **Damian Borkowski**.

---

Gemini, Google, Codex, OpenAI, Windows, and other product names are trademarks of their respective owners. Gemini Bridge is an independent project and is not endorsed by those companies.
