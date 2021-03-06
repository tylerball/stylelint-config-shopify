# stylelint-config-shopify
[![Circle CI](https://circleci.com/gh/Shopify/stylelint-config-shopify.svg?style=svg)](https://circleci.com/gh/Shopify/stylelint-config-shopify)
[![David-DM](https://david-dm.org/shopify/stylelint-config-shopify.svg)](https://david-dm.org/Shopify/stylelint-config-shopify)

Shopify's stylelint rules and config

## Installation

Install [stylelint](https://stylelint.io/) and `stylelint-config-shopify`:

**With Yarn**
```
yarn add --dev stylelint stylelint-config-shopify
```

**With npm**
```
npm install stylelint stylelint-config-shopify --save-dev
```


## Usage
Shopify’s stylelint rules come bundled in `stylelint-config-shopify`. To enable these rules, add a `stylelint` property in your `package.json`. See the [stylelint configuration docs](https://stylelint.io/user-guide/configuration/) for more details.
```
"stylelint": {
  "extends": ["stylelint-config-shopify"]
}
```

Now you can run stylelint by adding the following linting script to your `package.json`. See the [stylelint CLI docs](https://stylelint.io/user-guide/cli/) for more details.
```
"scripts": {
  "stylelint": "stylelint 'src/**/*.scss'"
}
```
Run it:

**With Yarn**
```
yarn run stylelint
```

**With npm**
```
npm run stylelint
```
