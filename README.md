# Open Tech Academy Documentation

Welcome to the open-source documentation repository for **Open Tech Academy** (hosted live at [docs.opentechacademy.org](https://docs.opentechacademy.org)).

This repository contains the user-facing documentation for all of our public programs, initiatives, organizational mission, and transparency statements.

---

## Directory Structure

Our documentation is powered by **Mintlify** and organized logically:

- `docs.json`: The global configuration file, including theme styling and sidebar navigation.
- `index.mdx`: The documentation homepage.
- `organization/`: Mission statements, community objectives, and transparency pages.
- `programs/`: Public-facing initiatives including:
  - `learning-center.mdx`: Learning portal overview and navigation guides.
  - `courses.mdx`: Catalog details of published courses.
  - `certificates.mdx`: Certificate tiers and verification details.
  - `workshops.mdx`: Build-to-own programs.
  - `open-tech-tools.mdx`: Open-source developer tools.

---

## Local Development

You can preview edits locally using the Mintlify CLI.

### Prerequisites

You need Node.js installed on your system.

### Running the Dev Server

Run the dev server directly from the root of this repository:

```bash
npx mintlify dev
```

The preview will be available at `http://localhost:3000`.

---

## Contributing

We welcome contributions from the community! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to propose changes, write user-facing articles, and validate your code before submitting a Pull Request.

---

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
