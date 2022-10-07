# @hibanka/ts-config

[![NPM Version](https://badgen.net/npm/v/@hibanka/ts-config)](https://npmjs.com/package/@hibanka/ts-config)
[![Minimum Node.js Version](https://badgen.net/npm/node/@hibanka/ts-config)](https://npmjs.com/package/@hibanka/ts-config)

Node.js shared config for TypeScript

## Installation

```bash
npm install --save-dev @hibanka/ts-config
```

## Usage

You can use config by extending it in your `tsconfig.json`:

```json
{
  "extends": "@hibanka/ts-config",
  "compilerOptions": {
    "outDir": "dist"
  }
}
```
