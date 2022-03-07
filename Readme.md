# Internal Eslint Config

Supports
- Typescript
- React
- Eslint
- Prettier
- Automatic Import Sorting
- Recommend to use with Prettier + Eslint Plugin on Vscode


## Install

```
yarn add -D @modfy/eslint eslint prettier prettier-config-standard

pnpm add -D @modfy/eslint eslint prettier prettier-config-standard
```


## Usage

```
touch .eslintrc.js .prettierrc
echo "module.exports = require('@modfy/eslint').default" >> .eslintrc.js
echo "\"prettier-config-standard\"" >> .prettierrc
```

