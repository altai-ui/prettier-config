# Prettier config

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
