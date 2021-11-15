# Prettier config

[![npm][npm-img]][npm-url]
![downloads][downloads-img]
![prettier][prettier-img]

## Installation

```bash
npm install @qvant/prettier-config prettier --save-dev

# or with yarn:
yarn add @qvant/prettier-config prettier --dev
```

## Set prettier config

```json
// package.json
{
  // ...
  "prettier": "@qvant/prettier-config"
  // ...
}
```

or <https://prettier.io/docs/en/configuration.html#sharing-configurations>

## Add scripts

```json
// package.json
{
  // ...
  "scripts": {
    // ...
    "prettier": "prettier --check --ignore-unknown '**/*'",
    "prettier:fix": "prettier --write --ignore-unknown '**/*'"
  }
  // ...
}
```

[npm-url]: https://npmjs.com/package/@qvant/prettier-config
[npm-img]: https://img.shields.io/npm/v/@qvant/prettier-config.svg
[downloads-img]: https://img.shields.io/npm/dm/@qvant/prettier-config
[prettier-img]: https://img.shields.io/badge/prettier-2.x-brightgreen
