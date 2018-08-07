# ESLint Example


Installation

```
$ npm i @zlatjs/eslint-config
```

Usage

package.json

```
"scripts": {
  ... , 
  "lint": "eslint src --ext .jsx",
}
```


.eslintrc

```
  {
    "extends": "eslint-config-zlatjs2",
    "settings": {
      "import/resolver": {
        "node": {
          "paths": "./src"
        }
      }
    }
  }
```
