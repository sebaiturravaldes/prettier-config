# Personal Prettier config

> My personal [Prettier](https://prettier.io) config.

## Usage

### Install

using npm

```cli
npm install --save-dev @siturra/prettier-config
```

or yarn

```cli
yarn add --dev @siturra/prettier-config
```

### Add prettier

add in package.json

```json
"prettier": "@siturra/prettier-config"
```

OR

Create a `.prettierrc` , `.prettierrc.yaml` , `.prettierrc.yml` or `.prettierrc.json` file and export a string.

```json
"@siturra/prettier-config"
```

OR

> Note: This method does not offer a way to extend the configuration to overwrite some properties from the shared configuration. If you need to do that, import the file in a `prettier.config.js` or `.prettierrc.js` file and export the modifications, e.g:
>
> ```js
> module.exports = {
>   ...require('@siturra/prettier-config'),
>   semi: false
> }
> ```

## References

- https://prettier.io/docs/en/configuration.html
- Prettier share example https://github.com/azz/prettier-config
- https://www.codereadability.com/automated-code-formatting-with-prettier
- https://medium.com/@sebastianiturra/reutiliza-prettier-2d9747b967fd
