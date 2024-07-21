# eslint-config-barney

Barney Parker's base ESLint configuration.

## Usage

1. `npm install --save-dev eslint-config-barney`
2. In your `eslintrc.config.js` file, add the following:

```js
import barneyConfig from 'eslint-config-barney'

export default [
  ...barneyConfig,

  // anything from here will override barneyConfig
  {
    rukles: {
      'no-unused-vars': 'warn',
    },
  },
]
```
