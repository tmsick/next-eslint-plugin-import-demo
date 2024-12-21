# About

This is a demonstration repo for reproduce the issue of eslint-plugin-import.

> Config (unnamed): Key "plugins": Cannot redefine plugin "import".

# Prerequisite

- Node.js v22
- Pnpm v9.15

# Issue reproduction

1. `$ pnpm install --frozen-lockfile`
1. `$ pnpm lint`
