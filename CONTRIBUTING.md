# Contributing to Open Tech Academy Documentation

Thank you for your interest in contributing to Open Tech Academy! We want our public documentation to be clear, welcoming, and accurate.

---

## Contribution Guidelines

### 1. Scope: User-Facing Only
Our documentation is strictly meant for students, sponsors, and community members. 
- **Do NOT** write articles about internal backend databases, infrastructure architectures, deployment workflows, security keys, or developer setup internals.
- Focus purely on what a user sees, how they navigate our portals, and how they benefit from our programs.

### 2. Tone and Style
- **Clarity First**: Write in plain, straightforward English. Avoid unnecessary jargon, acronyms, or complex sentences.
- **Tone**: Keep it supportive, educational, and professional. We are building a learning platform for all skill levels.
- **Markdown Formatting**: Use standard Markdown and Mintlify components (like `<CardGroup>`, `<Card>`, `<Info>`, etc.) where appropriate to keep pages visually engaging.

---

## Project Structure

When adding or editing pages, place them in the correct directory and update `docs.json` navigation configuration:

- `organization/`: Mission, transparency, values, and community impact.
- `programs/`: Public-facing initiatives, workshops, courses, and tools.

---

## Testing Your Changes

Before submitting a Pull Request, verify that your changes build and compile correctly with Mintlify:

1. Run the local dev server to review your pages visually:
   ```bash
   npx mintlify dev
   ```
2. Validate your configuration and MDX layout syntax to ensure there are no broken links or format errors:
   ```bash
   npx mintlify validate
   ```

All Pull Requests must pass the build validation check before being merged.
