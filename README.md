# @xtech/prettier-config

xTECH's [Prettier](https://prettier.io) config.

## Installation

```bash
$ npm i -D @xtech/prettier-config
```

or

```bash
$ yarn add -D @xtech/prettier-config
```

## Usage

Reference the module in `package.json`:

```jsonc
{
  // ...
  "prettier": "@xtech/prettier-config"
}
```

Or create a prettier config file that exports a string with the module name, e.g. `.prettierrc.json`:

```json
"@xtech/prettier-config"
```
