# csv2json-cli

Learning TypeScript by building tiny CLIs

## Features

- npm link friendly
- Strict tsconfig, no any
- Ships as an ESM binary
- commander-based subcommands

## Install

```bash
npm install
npm run build
```

## Usage

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   └── development.md
├── src/
│   └── index.ts
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version
