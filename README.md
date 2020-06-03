# eslint-config-ssk

This package provides base JS .eslintrc as an extensible shared config.

## Usage

### eslint-config-ssk

Our default export contains all of our ESLint rules, including ECMAScript 6.

First, install this package
```sh
npm install --save-dev eslint-config-ssk eslint
```
Then add following contents to your .eslintrc file
```
{
  "extends": "ssk"
}
```

### eslint-config-ssk/legacy

For some legacy project using es5.

First, install this package
```sh
npm install --save-dev eslint-config-ssk eslint
```
Then add following contents to your .eslintrc file
```
{
  "extends": "ssk/legacy"
}
```

### eslint-config-ssk/react
First, install this package and necessary plugins
```sh
npm install --save-dev eslint-config-ssk eslint babel-eslint eslint-plugin-react eslint-plugin-import eslint-plugin-jsx-a11y
```
Then add following contents to your .eslintrc file
```
{
  "extends": "ssk/react"
}
```

## License
MIT
