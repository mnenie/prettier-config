# Prettier config (@mnenie/prettier) 🔧

[![NPM Version](https://img.shields.io/npm/v/%40mnenie%2Fprettier?label=npm%20package&color=00cc44)](https://www.npmjs.com/package/@mnenie/prettier) [![NPM Downloads](https://img.shields.io/npm/dw/%40mnenie%2Fprettier?color=00cc44)](https://www.npmjs.com/package/@mnenie/prettier) [![MIT License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/mnenie/prettier-config/blob/master/LICENSE) ![Code Style Prettier](https://img.shields.io/badge/code_style-prettier-ab47bc)


## Installing

1. Use one of these following commands for adding package to your project.

```
// npm
npm install -D @mnenie/prettier 

// yarn
yarn add -D @mnenie/prettier
```

2. After installing, create/update `.prettierrc.cjs` file with content:
```js
// default 
const { prettier } = require('@mnenie/prettier');

/** @type {import('prettier').Config} */
module.exports = prettier;
```
```js
// with tailwindcss
const { prettier } = require('@mnenie/prettier');

/** @type {import('prettier').Config} */
module.exports = {
  ...prettier,
  plugins: ['prettier-plugin-tailwindcss']
};
```
