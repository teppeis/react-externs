react-externs [![npm](https://img.shields.io/npm/v/react-externs.svg)](https://www.npmjs.com/package/react-externs) ![Bower](https://img.shields.io/bower/v/react-externs.svg)
=============

Google Closure Compiler externs for Facebook React.js

## How to use

```console
$ npm install react-externs
```

or

```console
$ bower install react-externs
```

## Development

How to release:

```console
$ npm install
$ gulp bump [OPTIONS]
```

Options: `--patch` (default), `--minor` or `--major`

This commad does:

1. Bump version of `package.json` and `bower.json`
2. `git tag x.y.z`
3. `git push origin --tags`
4. `npm publish`


