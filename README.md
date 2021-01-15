<!-- ix-docs-ignore -->

![imgix logo](https://assets.imgix.net/sdk-imgix-logo.svg)

A [shareable config](https://github.com/browserslist/browserslist#shareable-configs) for Browserslist used by the [imgix SDK](https://docs.imgix.com/libraries).

[![NPM Version](https://img.shields.io/npm/v/@imgix/browserslist-config)](https://www.npmjs.com/package/@imgix/browserslist-config)
[![License](https://img.shields.io/github/license/imgix/browserslist-config)](https://github.com/imgix/browserslist-config/blob/main/LICENSE.md)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fimgix%2Fbrowserslist-config.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fimgix%2Fbrowserslist-config?ref=badge_shield)

---

<!-- /ix-docs-ignore -->

## Installation

```
npm install browserslist @imgix/browserslist-config --save-dev
```

## Usage

Add this to your `package.json` file:

```json
"browserslist": [
    "extends @imgix/browserslist-config"
]
```

Alternatively, add this to your `.browserslistrc` file:

```
extends @imgix/browserslist-config
```

When imported, this package returns an array of supported browsers. For more configuration examples, see the [Browserslist examples](https://github.com/browserslist/browserslist-example#browserslist-example) repo.


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fimgix%2Fbrowserslist-config.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fimgix%2Fbrowserslist-config?ref=badge_large)