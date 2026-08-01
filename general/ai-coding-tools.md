# AI Coding Tools

## Overview

There are many AI tools for software development. Although their names are similar, they serve different purposes.

---

# ChatGPT

**Company:** OpenAI

A general-purpose AI assistant.

Common uses:

- Learn programming concepts
- Explain code
- Debug errors
- Generate code examples
- Answer technical questions
- Brainstorm solutions

Best for:

> Learning and problem solving.

---

# Codex

**Company:** OpenAI

Codex is an AI coding agent that can work on an entire software project.

Unlike ChatGPT, Codex can:

- Read an existing codebase
- Create and modify files
- Implement features
- Fix bugs
- Run tests
- Work on multiple files

Conceptually:

Developer
    ↓
Codex
    ↓
Entire Project

Best for:

> Implementing and maintaining real software projects.

---

# GitHub Copilot

**Company:** GitHub (Microsoft)

GitHub Copilot is an AI coding assistant integrated into IDEs such as:

- Visual Studio
- VS Code
- JetBrains IDEs

Common features:

- Code completion
- Generate functions
- Explain code
- Refactor code
- Generate unit tests

Conceptually:

Developer
    ↓
IDE
    ↓
GitHub Copilot
    ↓
Suggest code while typing

Best for:

> Increasing coding productivity.

---

# Microsoft Copilot

**Company:** Microsoft

Microsoft Copilot is Microsoft's AI assistant for productivity.

It is available across Microsoft products, including:

- Windows
- Word
- Excel
- PowerPoint
- Outlook
- Teams
- Azure

Common uses:

- Writing documents
- Summarizing emails
- Creating presentations
- Answering questions
- Assisting with Windows

Best for:

> Office productivity and enterprise workflows.

---

# GPT Pilot

**Company:** Pythagora (Open Source)

GPT Pilot is an AI software engineering agent.

Instead of only generating code, it attempts to build an entire application.

Typical workflow:

Understand requirements
        ↓
Plan project
        ↓
Generate project structure
        ↓
Write code
        ↓
Run application
        ↓
Fix issues

Best for:

> Automatically creating complete applications.

---

# Comparison

| Tool | Company | Primary Purpose |
|------|---------|-----------------|
| ChatGPT | OpenAI | Learning, explanations, problem solving |
| Codex | OpenAI | AI software engineering agent |
| GitHub Copilot | GitHub (Microsoft) | AI coding assistant inside IDEs |
| Microsoft Copilot | Microsoft | AI assistant for Windows and Microsoft 365 |
| GPT Pilot | Pythagora | AI project generation |

---

# Relationship

AI Development Tools

```
                    AI
                     │
      ┌──────────────┴──────────────┐
      │                             │
   OpenAI                     Microsoft
      │                             │
      ├── ChatGPT              ├── Microsoft Copilot
      ├── Codex                └── GitHub Copilot*
      │
      └── GPT Pilot (Third-party)
```

\* GitHub Copilot is developed by GitHub (owned by Microsoft) and uses OpenAI models.

---

# Which Tool Should I Use?

| Goal | Recommended Tool |
|------|------------------|
| Learn programming | ChatGPT |
| Understand code | ChatGPT |
| Write code faster | GitHub Copilot |
| Build or modify an entire project | Codex |
| Office productivity | Microsoft Copilot |
| Experiment with AI-generated projects | GPT Pilot |

---

# Key Takeaways

- **ChatGPT** → Learn and ask questions.
- **Codex** → Build and modify software projects.
- **GitHub Copilot** → Write code faster inside an IDE.
- **Microsoft Copilot** → AI assistant for Microsoft products.
- **GPT Pilot** → Open-source AI agent for generating complete applications.
