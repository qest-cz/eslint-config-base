# @qest/eslint-config-base

This aims to provide easy and consistent settings for all our react projects.

Package should take into cosideration tsconfig as well as prettier and enforce their rules trough eslint.

## instalation

``` bash
yarn add -D eslint @qest/eslint-config-base
```

``` js
// .eslintrc.js
module.exports = {
  extends: ["@qest/base"],
  rules: [
      //...any overrides
  ]
};
```

``` js
// .prettierrc.js
module.exports = {
  ...require('@qest/eslint-config-base/.prettierrc'),
  //...any overrides
};
```
