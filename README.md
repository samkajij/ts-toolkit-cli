# ts-toolkit-cli

Learning TypeScript by building tiny CLIs

## Getting started

```bash
npm install
npm run build
```

## How to use

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Features

- Strict tsconfig, no any
- Ships as an ESM binary
- npm link friendly
- commander-based subcommands

## Project structure

```text
├── .github/
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── src/
│   └── index.ts
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
npm test
```

## License

MIT licensed, see LICENSE.
