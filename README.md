# eslint-config-binden-js ![CI Status](https://github.com/binden-js/eslint-config/workflows/CI/badge.svg) [![version](https://img.shields.io/github/package-json/v/binden-js/eslint-config?style=plastic)](https://github.com/binden-js/eslint-config) [![Known Vulnerabilities](https://snyk.io/test/github/binden-js/eslint-config/badge.svg)](https://snyk.io/test/github/binden-js/eslint-config) [![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md) [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release) [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org) ![GitHub top language](https://img.shields.io/github/languages/top/binden-js/eslint-config) ![Node.js version](https://img.shields.io/node/v/eslint-config-binden-js) ![npm downloads](https://img.shields.io/npm/dt/eslint-config-binden-js) ![License](https://img.shields.io/github/license/binden-js/eslint-config)

Shareable [ESLint](https://github.com/eslint/eslint) config.

## Installation

```sh
npm i --save-dev eslint-config-binden-js
```

## Usage

- Add it to your configuration file

```js
// eslint.config.js
export { default } from "eslint-config-binden-js";
```

- One can add additional configuration objects

```js
// eslint.config.js
import config from "eslint-config-binden-js";
export default [...config, { rules: { "no-unused-vars": "off" } }];
```
