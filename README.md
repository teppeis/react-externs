react-externs
=============

Google Closure Compiler externs for Facebook React.js

## How to use it with Bower

```console
$ bower install react-externs
```

## How to use it with NPM

```console
$ npm install react-externs
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


