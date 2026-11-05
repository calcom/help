# Contributing to Cal.com Help Center Documentation

Thank you for your interest in contributing to Cal.com's official documentation (`cal.com/help`).

This repository is built using [Mintlify](https://mintlify.com) and contains all user-facing articles, API integration guides, and embed tutorials.

---

## Development & Documentation Standards

1. **MDX Syntax**: All pages are written in MDX (`.mdx`). Ensure all components (e.g. `<Note>`, `<Tip>`, `<Warning>`, `<Accordion>`, `<CodeGroup>`) conform to Mintlify standards.
2. **Navigation (`docs.json`)**: Whenever you add, rename, or move a documentation page, ensure the corresponding path is properly updated in `docs.json`.
3. **Internal Links**: Use site-relative paths (e.g. `[Embed Events](/embedding/embed-events)`) rather than hardcoded URLs.
4. **Code Quality**: Ensure all code snippets are syntactically valid and reflect the latest Cal.com APIs and Embed SDK methods.

---

## Pull Request & Attribution Guidelines

To maintain a clean and respectful communication environment on GitHub, please adhere to the following rules when creating pull requests or writing automated descriptions:

### User Mentions & CCs
- **Always use exact GitHub usernames**: When attributing commits or requesting review, specify the contributor's valid GitHub handle prefixed by `@` (e.g. `cc @Udit-takkar`).
- **Never use full names with `@` prefixes**: Writing `cc @First Last` causes GitHub to parse `@First` as a mention of an unrelated third-party user. If a GitHub handle is unknown or unverified, write their full name in plain text or format it as code (e.g. `First Last` or `` `First Last` ``).
- **PR Titles**: Follow conventional commit guidelines:
  - `docs: update embed events documentation`
  - `docs(routing): add headless routing embed mode`
  - `fix: correct typo in analytics documentation`

---

## Linking Issues

Always reference open issues in your pull request summary to ensure proper tracking and automated closure:
- `Fixes #1`
- `Fixes #2`
- `Closes #126`
