# babel-preset-chrome

> Babel preset for chrome for version 46+.

## Install

```sh
$ npm install --save-dev babel-preset-chrome
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["babel-preset-chrome"]
}
```

### Via CLI

```sh
$ babel script.js --presets babel-preset-chrome
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["babel-preset-chrome"]
});
```
