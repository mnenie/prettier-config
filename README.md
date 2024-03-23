# Prettier config (@mnenie/prettier) 🔧

[![npm version](https://badge.fury.io/js/@mnenie%2Fprettier.svg)](https://www.npmjs.com/package/@mnenie/prettier)


## Installing

1. Use one of these following commands for adding package to your project.

```
// npm
npm install -D @mnenie/prettier 

// yarn
yarn install --dev @mnenie/prettier
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
