# ESLint Example

프로젝트 내부에 `.eslintrc` 파일 생성 후 아래 코드를 추가

```
  {
    "extends": "eslint-config-zlatjs2",
    "settings": {
      "import/resolver": {
        node: { paths: [path.resolve('./src')] }
      }
    }
  }
```
