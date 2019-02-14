# eslint-config-fix-all
A eslint preset with all the fixable rules

# Installation

```sh
npm install -save-dev eslint-config-fix-all
```


# Usage

```sh
eslint --fix
```

There are a number of rules that are es6-specific, so you may also want to consider using babel-eslint as your parser

```json
{
    "extends": "eslint-config-fixable",
    "parser": "babel-eslint"
}
```