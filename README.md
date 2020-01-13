## Installation

```
yarn add -D @gfez/eslint-config-wechat-miniprogram
```

_Note: We're using `yarn` to install deps. Feel free to change commands to use `npm` 3+ and `npx` if you like_

## Usage

Add to your eslint config (`.eslintrc.js`, or `eslintConfig` field in `package.json`):

```js
module.exports = {
  root: true,
  extends: ['@gfez/wechat-miniprogram', 'plugin:prettier/recommended']
};
```
