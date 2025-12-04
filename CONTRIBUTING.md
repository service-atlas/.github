# Contributing to Service Atlas

Thank you for considering contributing to **Service Atlas**!  
We welcome improvements, ideas, and feedback across all repositories in the organization.

This guide outlines how to get started, coding conventions, and how to submit great issues and pull requests.

---

## 🧭 Overview

Service Atlas consists of multiple components, including:

- **Backend (Go)** — the main API service and data model  
- **MCP Server (Python)** — a read-only server exposing service & team data  

This contributing guide applies to all repos, unless a specific repo provides additional instructions.

---

## 📝 Ways to Contribute

- Report bugs or unexpected behavior  
- Request new features  
- Improve documentation or examples  
- Add tests or improve test coverage  
- Suggest improvements to architecture or developer experience  
- Help refine the domain model (services, teams, dependencies, metadata)  

All contributions — even small edits — make the project better.

---

# 1. 🐛 Reporting Issues

Before opening a new issue:

- Check existing issues to avoid duplicates  
- Use the **Bug Report** or **Feature Request** templates if available  
- Provide clear steps to reproduce  
- Include logs, error messages, or request/response samples when possible  
- For feature requests, describe the use case and *why* it matters  

Issues that clearly explain the problem get resolved faster.

---

# 2. 🧪 Testing Guidelines

Although implementations differ per repo, we ask that all contributions follow these general principles:

- Include tests for new functionality  
- Avoid breaking existing tests unless intentionally changing behavior  
- Keep tests focused and readable  
- Add comments when test intent isn’t obvious  
- Match the testing style used in the specific repo you're contributing to  

If you're unsure how to test something, feel free to ask in the issue or PR — we're happy to help.

---

# 3. 🧹 Code Style

Follow the conventions of the repository you’re contributing to. General expectations include:

- Use clear, descriptive names for variables, functions, and domain concepts  
- Keep functions and modules small, focused, and readable  
- Follow existing patterns in the codebase  
- Remove unused code, cleanup logs, and keep diffs clean  

Each repository may include its own formatting or linting tools (e.g., `go fmt`, `ruff`, `pre-commit`). Please run them before submitting a PR.

---

# 4. 🔁 Pull Requests

We welcome PRs of all sizes. To help us review them quickly:

### ✔ Before opening a PR:
- Ensure your branch is up to date with the default branch  
- Run all tests and formatting/linting tools locally  
- Keep changes focused — smaller PRs are easier to review  
- Link any related issues  
- Explain *why* the change is needed  

### ✔ In your PR description, include:
- What problem is being solved  
- Summary of changes  
- Any breaking changes  
- Any new configuration/setup steps  

### ✔ After opening the PR:
- Be open to feedback  
- Update your branch if reviewers request revisions  
- Engage in discussion respectfully and technically  

We typically squash-merge PRs unless otherwise discussed.

---

# 5. 🤝 Code of Conduct

Participation in all Service Atlas repositories is governed by the organization-wide **CODE_OF_CONDUCT.md**.  
Help us maintain a respectful and welcoming community.

---

# 🎉 Thank You

Whether you’re fixing a typo or designing architecture — your contributions matter.  
If you're unsure where to start, feel free to open an issue or discussion. We’re glad to have you here.
