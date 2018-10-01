# prettier-std-cli

Standalone CLI for [standard-prettier-eslint](https://github.com/bySabi/standard-prettier-eslint)

[![npm version](https://badge.fury.io/js/prettier-std-cli.svg)](https://badge.fury.io/js/prettier-std-cli)
[![npm downloads](https://img.shields.io/npm/dm/prettier-std-cli.svg?style=flat-square)](https://www.npmjs.com/package/prettier-std-cli)

Formats your JavaScript using [`prettier`](https://github.com/jlongster/prettier) followed by [`standard --fix`][standard]

*  [prettier](https://github.com/prettier/prettier) is a wonderful tool for code prettify.
*  [standard][standard] is `zero configuration pain` tool based on ESLint.

The two packages are great and very well designed, that can be used together with a minimum effort


## Installation
    $ npm install prettier-std-cli -g

## Usage
Ex: package.json
```json
"scripts": {
  ...
  "lint": "standard --verbose | snazzy",
  "format": "prettier-std --write '**/*.js'"
}
```

### If you prefer `semicolons` use **semistandard** version
* [prettier-semi-cli](https://github.com/bySabi/prettier-semi-cli)

## Contributing

* Documentation improvement
* Feel free to send any PR

## License

[MIT][mit-license]

[mit-license]:./LICENSE

[standard]: https://github.com/standard/standard
