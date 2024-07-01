# vue-cli-plugin-eslint-flat

ESLint flat config compatible version of @vue/cli-plugin-eslint, supports ESLint v8.50.0+ and @vue/cli v5.0.0+ .

## Usage

Replace `@vue/cli-plugin-eslint` with `vue-cli-plugin-eslint-flat`.

Read [@vue/cli-plugin-eslint](https://github.com/vuejs/vue-cli/blob/dev/packages/%40vue/cli-plugin-eslint/README.md) for more details.

```js
// use @vue/cli
vue add eslint-flat
// use npm
npm install -D vue-cli-plugin-eslint-flat
```

## What's difference?

 - Change the dependencies version:
   - `eslint-webpack-plugin` from `"^3.1.0"` to `"^4.2.0"`
   - `eslint` from `>=7.5.0` to `>=8.50.0`
   - `@vue/cli-service` from `^3.0.0 || ^4.0.0 || ^5.0.0-0` to `^5.0.0-0`.
 - Add `configType: 'flat'` to `eslint-webpack-plugin` option.
