# CyberFabric Documentation

Documentation, tutorials, and how-to guides for the [CyberFabric](https://github.com/constructorfabric) platform.

## Prerequisites

- [Bun](https://bun.sh/) >= 1.0
- [Git](https://git-scm.com/)

## Local Development

Install dependencies:

```sh
bun install
```

Start the development server:

```sh
bun run docs:dev
```

The site will be available at `http://localhost:5173`.

## Build

```sh
bun run docs:build
```

Built files will be in `docs/.vitepress/dist/`.

## Preview Production Build

```sh
bun run docs:preview
```

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines on writing and submitting documentation.

## License

Apache-2.0 - see [LICENSE](./LICENSE) for details.
