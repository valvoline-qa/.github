# Contributing to .github

Thank you for your interest in contributing to this repository! This guide will help you get started.

## 📋 Prerequisites

- A GitHub account with access to the organization
- Git installed on your local machine
- Familiarity with [Conventional Commits](https://www.conventionalcommits.org/)

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd .github
   ```

2. **Create a feature branch**

   Branch names must follow this format:

   ```
   <type>/<ticket-number>/<short-description>
   ```

   For example:

   ```bash
   git checkout -b feat/45010/add-profile-upload
   git checkout -b fix/90210/correct-invoice-calc
   git checkout -b docs/64989/add-contributing-md
   ```

3. **Make your changes** and commit using the conventions below.

## 📝 PR Title Convention

All Pull Request titles **must** follow the organization's standard format:

```
<type>[optional scope]: <description> <azure_ticket_id>
```

### Allowed Types

| Type       | Description                          |
| ---------- | ------------------------------------ |
| `feat`     | A new feature                        |
| `fix`      | A bug fix                            |
| `docs`     | Documentation-only changes           |
| `style`    | Formatting, missing semicolons, etc. |
| `refactor` | Code change without fix or feature   |
| `perf`     | Performance improvement              |
| `test`     | Adding or updating tests             |
| `build`    | Build system or dependencies         |
| `ci`       | CI/CD configuration changes          |
| `chore`    | Other changes (tooling, config)      |
| `revert`   | Reverting a previous commit          |

### Examples

- ✅ `feat(user): add profile picture upload 4501`
- ✅ `fix: correct calculation in invoice engine AB#9021`
- ✅ `chore(deps): upgrade react to v18 #1122`
- ❌ `add new feature` — missing type and ticket ID
- ❌ `feat: new login` — missing ticket ID
- ❌ `Fix: broken link 123` — type must be lowercase

## 🔀 Branching Strategy

- Create branches from `master`.
- Use the format `<type>/<ticket-number>/<short-description>` (e.g., `feat/45010/add-profile-upload`).
- The `<type>` should match the conventional commit types listed above.

## ✅ Pull Request Checklist

Before submitting your PR, ensure:

- [ ] PR title follows the format `<type>: <desc> <id>`.
- [ ] Changes have been tested.
- [ ] A self-review of the code has been performed.
- [ ] Relevant tickets and documentation are updated.
- [ ] Hard-to-understand code is commented.
- [ ] Changes follow repository established standards.
- [ ] No new warnings are generated.
- [ ] Reviewers have been assigned.

## 🔍 Code Review

- All PRs require at least one approving review before merging.
- Address review comments promptly.
- Keep PRs focused — avoid mixing unrelated changes.

## 📬 Questions?

If you have any questions, please reach out to the repository maintainers or open an issue.
