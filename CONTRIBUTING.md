# Contributing to Hello-Agents

Thank you for considering contributing to Hello-Agents! This document outlines how to get involved and make meaningful contributions.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Ways to Contribute](#ways-to-contribute)
- [Getting Started](#getting-started)
- [Pull Request Process](#pull-request-process)
- [Writing Style Guide](#writing-style-guide)
- [Extra Chapter Guidelines](#extra-chapter-guidelines)

---

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before contributing.

---

## Ways to Contribute

| Contribution Type | How |
|---|---|
| 🐛 Report a bug or error | [Open a bug report issue](https://github.com/Reyzowter/Hello-Agents/issues/new?template=bug_report.md) |
| 💡 Suggest a new feature or chapter | [Open a feature request](https://github.com/Reyzowter/Hello-Agents/issues/new?template=feature_request.md) |
| 📝 Fix typos or improve existing content | Submit a Pull Request |
| ✍️ Write an Extra Chapter | Follow the Extra Chapter guidelines below |
| 🌍 Translate content to another language | Open an issue to coordinate first |
| 🧪 Submit code examples | Add to the `/code` folder with a README |
| ⭐ Star & share | Help others discover Hello-Agents |

---

## Getting Started

### 1. Fork the Repository

Click the **Fork** button at the top of [github.com/Reyzowter/Hello-Agents](https://github.com/Reyzowter/Hello-Agents).

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/Hello-Agents.git
cd Hello-Agents
```

### 3. Create a Branch

```bash
git checkout -b feat/your-contribution-name
# or for bug fixes:
git checkout -b fix/description-of-fix
```

### 4. Make Your Changes

- For **content**: edit files in `/docs/`
- For **code examples**: edit files in `/code/`
- For **Extra Chapters**: add to `/Extra-Chapter/`

### 5. Commit Your Changes

Use clear, descriptive commit messages:

```bash
git commit -m "feat: add chapter on multi-agent coordination patterns"
git commit -m "fix: correct ReAct algorithm pseudocode in Chapter 4"
git commit -m "docs: add code example for RAG with ChromaDB"
```

### 6. Push and Open a PR

```bash
git push origin feat/your-contribution-name
```

Then open a Pull Request on GitHub. Fill out the PR template completely.

---

## Pull Request Process

1. **One PR per change** — keep PRs focused and atomic
2. **Link related issues** — use `Closes #123` in your PR description
3. **Add a clear description** — explain what changed and why
4. **Self-review your changes** before requesting review
5. **Be responsive** — maintainers may request changes; please respond within 7 days

PRs that pass review are merged into `main` and credited in the changelog.

---

## Writing Style Guide

All tutorial content should follow these guidelines:

### Tone
- **Clear and direct** — avoid jargon where plain English works
- **Pedagogical** — explain *why*, not just *what*
- **Practical** — every concept should connect to code or a real use case

### Formatting
- Use **Markdown** for all documentation
- Code blocks must specify the language: ` ```python `, ` ```bash `
- Use headers hierarchically: `##` for sections, `###` for subsections
- Tables for structured comparisons; numbered lists for sequential steps

### Code Examples
- All code must be runnable and tested
- Include comments explaining non-obvious lines
- Add a `requirements.txt` for any new dependencies
- Python 3.9+ compatibility required

---

## Extra Chapter Guidelines

Extra Chapters are community contributions that extend the main curriculum. They live in `/Extra-Chapter/`.

### What Makes a Good Extra Chapter?
- Covers a topic not already in the main curriculum
- Has practical value (runnable code, real-world application)
- Is self-contained (readers shouldn't need other Extra Chapters)
- Minimum 1,000 words; maximum 10,000 words

### Naming Convention

```
Extra{NN}-Short-Title.md
```

Example: `Extra14-Agent-Security-Best-Practices.md`

### Required Sections

1. **Overview** — what the reader will learn
2. **Prerequisites** — what to know before reading
3. **Main Content** — the tutorial itself
4. **Code Examples** — working, commented code
5. **Further Reading** — 3–5 curated resources

---

## Questions?

If you're unsure about anything, open an issue and ask — we're friendly! 😊

[Open a Discussion →](https://github.com/Reyzowter/Hello-Agents/discussions)
