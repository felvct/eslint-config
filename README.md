# ESLint Config felvct
felvcts' custom ESLint Config

## Getting started
### Installation
```sh
npm i -D [-E] @felvct/eslint-config
```

### How to use
In your `.eslintrc{.*}`:
```json
{
  "extends": "@felvct/eslint-config",
  "parserOptions": {
    "project": "./tsconfig.json"
  }
}
```

Run the linter: `npx eslint --ext .ts . [--fix]`
