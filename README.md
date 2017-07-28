# Savvy CSS Spacing Utilities

[![Latest NPM release][npm-badge]][npm-badge-url]
[![License][license-badge]][license-badge-url]
[![Dependencies][dependencies-badge]][dependencies-badge-url]
[![Dev Dependencies][devDependencies-badge]][devDependencies-badge-url]

_Spacing utilities for Savvy CSS._

## Installation

You can install this package using [yarn](https://yarnpkg.com/en/docs/install):

```shell
yarn add --dev @savvy-css/spacing-utilities
```

... or using [NPM](https://docs.npmjs.com/getting-started/installing-node):

```shell
npm install --save-dev @savvy-css/spacing-utilities
```

## Usage

### Importing

Within a project that's capable of importing CSS, simply import
the module by its package name within your own CSS:

```css
@import "@savvy-css/spacing-utilities";
```

Importing this module will add [its properties](/lib/spacing-utilities.css) to your project. To override them, simply define them in any portion of your CSS that's imported/processed later.

See the comments in the [main CSS file](/lib/index.css) for detailed usage and implementation details.



[npm-badge]: https://img.shields.io/npm/v/@savvy-css/spacing-utilities.svg
[npm-badge-url]: https://www.npmjs.com/package/@savvy-css/spacing-utilities
[license-badge]: https://img.shields.io/npm/l/@savvy-css/spacing-utilities.svg
[license-badge-url]: LICENSE
[dependencies-badge]: https://img.shields.io/david/savvy-css/spacing-utilities.svg
[dependencies-badge-url]: https://david-dm.org/savvy-css/spacing-utilities
[devDependencies-badge]: https://img.shields.io/david/dev/savvy-css/spacing-utilities.svg
[devDependencies-badge-url]: https://david-dm.org/savvy-css/spacing-utilities#info=devDependencies

