# tsconfig

[![npm@latest](https://img.shields.io/npm/v/@byndyusoft/tsconfig/latest.svg)](https://www.npmjs.com/package/@byndyusoft/tsconfig)
[![test workflow](https://github.com/Byndyusoft/tsconfig/actions/workflows/test.yaml/badge.svg?branch=master)](https://github.com/Byndyusoft/tsconfig/actions/workflows/test.yaml)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

TSConfig for Byndyusoft projects

## Requirements

- Node.js v12 LTS or later
- npm or yarn

## Install

```bash
npm install --save-dev @byndyusoft/tsconfig
```

or

```bash
yarn add -D @byndyusoft/tsconfig
```

## Usage

Add to your `tsconfig.json`:

```json
{
  "extends": "@byndyusoft/tsconfig/tsconfig.node12.json"
}
```

or

```json
{
  "extends": "@byndyusoft/tsconfig/tsconfig.node14.json"
}
```

or

```json
{
  "extends": "@byndyusoft/tsconfig/tsconfig.node16.json"
}
```

## Maintainers

- [@Byndyusoft/owners](https://github.com/orgs/Byndyusoft/teams/owners) <<github.maintain@byndyusoft.com>>
- [@Byndyusoft/team](https://github.com/orgs/Byndyusoft/teams/team)
