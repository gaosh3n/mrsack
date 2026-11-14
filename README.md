# Development

## Prerequisites

- Node.js 22.22.2 or newer in the 22.x series, or 24.15.0 or newer
- pnpm

## Commands

Run these commands from the repository root:

```sh
pnpm install --frozen-lockfile                 # Install dependencies from the lockfile

pnpm run lint       # Run ESLint
pnpm exec oxlint .  # Run Oxlint
pnpm run lint:fix   # Run ESLint and apply fixes

pnpm exec prek install . --hook-type pre-commit # Install the pre-commit hook (ESLint auto-fixes matching files)
```

