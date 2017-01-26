# eslint-config-meowyo

An [eslint shareable config](http://eslint.org/docs/developer-guide/shareable-configs) for me.

## Usage

Install via:
```
$ yarn add git+https://github.com/mayognaise/eslint-config-meowyo.git -D
```

.eslintrc:
```
{
  "extends": "eslint-config-eBay"
}
```

`scripts` in package.json:
```
{
  "eslint": "eslint . --ignore-pattern .marko.js"
}
```
