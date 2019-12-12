# eslint-config-mina

## Installation

```
yarn add -D eslint-config-mina
```

_Note: We're using `yarn` to install deps. Feel free to change commands to use `npm` 3+ and `npx` if you like_

## Usage

Add to your eslint config (`.eslintrc.js`, or `eslintConfig` field in `package.json`):

```js
module.exports = {
  root: true,
  extends: ['mina', 'plugin:prettier/recommended']
};
```

为了支持可选链，需要为 VS Code 安装 JavaScript and TypeScript Nightly 插件
