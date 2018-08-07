# @zlatjs/style-config

## Installation

```
$ npm i @zlatjs/stylelint-config
```

## Usage

package.json

```
"script": {
  ... ,
  "stylelint": "style '${url}'"
}
```


.stylelintrc.json

```
{
  "extends": "@zlatjs/stylelint-config",
  "settings": {
    "import/resolver": {
      "node": {
        "paths": "./src"
      }
    }
  }
}
```