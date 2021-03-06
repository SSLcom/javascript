# eslint-config-sslcom

This package provides SSL.com's .eslintrc as an extensible shared config.

## Usage

We export three ESLint configurations for your usage.

### eslint-config-sslcom

Our default export contains all of our ESLint rules, including ECMAScript 6+ and React. It requires `eslint`, `eslint-plugin-import`, and `eslint-plugin-react`.

1. `npm install --save-dev eslint-config-sslcom eslint-plugin-import eslint-plugin-react eslint`
2. add `"extends": "sslcom"` to your .eslintrc

### eslint-config-sslcom/base

This entry point is deprecated. See [eslint-config-sslcom-base](https://npmjs.com/eslint-config-sslcom-base).

### eslint-config-sslcom/legacy

This entry point is deprecated. See [eslint-config-sslcom-base](https://npmjs.com/eslint-config-sslcom-base).

See [SSL.com's Javascript styleguide](https://github.com/sslcom/javascript) and
the [ESlint config docs](http://eslint.org/docs/user-guide/configuring#extending-configuration-files)
for more information.

## Improving this config

Consider adding test cases if you're making complicated rules changes, like anything involving regexes. Perhaps in a distant future, we could use literate programming to structure our README as test cases for our .eslintrc?

You can run tests with `npm test`.

You can make sure this module lints with itself using `npm run lint`.
