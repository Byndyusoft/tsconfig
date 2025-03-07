# tsconfig

[![npm@latest](https://img.shields.io/npm/v/@byndyusoft/tsconfig/latest.svg)](https://www.npmjs.com/package/@byndyusoft/tsconfig)
[![test](https://github.com/Byndyusoft/tsconfig/actions/workflows/test.yaml/badge.svg?branch=master)](https://github.com/Byndyusoft/tsconfig/actions/workflows/test.yaml)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

TSConfig for Byndyusoft projects

## Requirements

- Node.js v16 LTS or later
- TypeScript v4.7 or later
- Yarn

## Install

```bash
yarn add -D @byndyusoft/tsconfig
```

## Usage

Add to your `tsconfig.json`:

### Node 16

```json
{
  "extends": "@byndyusoft/tsconfig/tsconfig.node16.json"
}
```

or

```json
{
  "extends": "@byndyusoft/tsconfig/tsconfig.app.node16.json"
}
```

### Node 18

```json
{
  "extends": "@byndyusoft/tsconfig/tsconfig.node18.json"
}
```

or

```json
{
  "extends": "@byndyusoft/tsconfig/tsconfig.app.node18.json"
}
```

### Node 20

```json
{
  "extends": "@byndyusoft/tsconfig/tsconfig.node20.json"
}
```

or

```json
{
  "extends": "@byndyusoft/tsconfig/tsconfig.app.node20.json"
}
```

### Node 22

```json
{
  "extends": "@byndyusoft/tsconfig/tsconfig.node22.json"
}
```

or

```json
{
  "extends": "@byndyusoft/tsconfig/tsconfig.app.node22.json"
}
```

## Maintainers

- [@Byndyusoft/owners](https://github.com/orgs/Byndyusoft/teams/owners) <<github.maintain@byndyusoft.com>>
- [@Byndyusoft/team](https://github.com/orgs/Byndyusoft/teams/team)
- [@KillWolfVlad](https://github.com/KillWolfVlad)

## License

This repository is released under version 2.0 of the
[Apache License](https://www.apache.org/licenses/LICENSE-2.0).
