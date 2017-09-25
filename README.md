# `@wizardsoftheweb/nyc-config-typescript`

TypeScript `nyc` config, based on [`@istanbuljs/nyc-config-babel`](https://www.npmjs.com/package/@istanbuljs/nyc-config-babel).

## Install

```bash
npm install --save-dev typescript ts-node nyc cross-env @wizardsoftheweb/nyc-config-typescript
```

## Usage

Start `.nycrc` with this:

```json
{
  "extends": "@wizardsoftheweb/nyc-config-typescript"
}
```

## Suggested `lifecycle` Script

```json
{
    "scripts": {
        "test": "cross-env NODE_ENV=test nyc mocha"
    }
}
```
