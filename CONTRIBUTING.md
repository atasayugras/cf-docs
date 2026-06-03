# Contributing to CyberFabric Documentation

Thank you for helping improve the CyberFabric docs! This guide covers everything you need to get started.

## Setup

1. Fork this repository
2. Clone your fork:
   ```sh
   git clone https://github.com/<your-username>/cf-docs.git
   cd cf-docs
   ```
3. Install dependencies:
   ```sh
   bun install
   ```
4. Start the dev server:
   ```sh
   bun run docs:dev
   ```

## Writing Documentation

All documentation lives in `docs/`. Pages are written in Markdown with VitePress extensions.

### Structure

```
docs/
├── intro/          # Getting started and architecture guides
│   ├── core/       # Core concepts (modules, SDK, database, OData)
│   └── tutorials/  # Step-by-step tutorials
├── reference/      # API and library reference
│   ├── modkit/     # ModKit library docs
│   └── system-sdks/
└── assets/         # Diagrams and images
```

### Style Guidelines

- Use active voice and present tense
- Keep sentences short and direct
- Include code examples wherever possible
- Use VitePress custom containers for callouts:

  ```md
  ::: tip
  This is a helpful tip.
  :::

  ::: warning
  This is a warning.
  :::

  ::: danger
  This is a danger notice.
  :::
  ```

## Submitting a Pull Request

1. Create a branch with a descriptive name:
   ```sh
   git checkout -b docs/your-topic
   ```
2. Make your changes
3. Verify the site builds without errors:
   ```sh
   bun run docs:build
   ```
4. Commit and push your branch
5. Open a pull request against `main` with a clear description of what you added or changed

## License

By contributing, you agree that your contributions will be licensed under the [Apache-2.0 License](./LICENSE).
