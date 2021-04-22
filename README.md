# @ev-fns/string-fns

String functions

- camelToSnake `(str: string) => string`
- snakeToCamel `(str: string) => string`

## Install

```sh
yarn add @ev-fns/string-fns
```

## Usage

```js
const { camelToSnake, snakeToCamel } = require("@ev-fns/string-fns");

console.log(camelToSnake("camelCaseValue"));
// camel_case_value

console.log(snakeToCamel("snake_to_camel"));
// snakeToCamel
```
