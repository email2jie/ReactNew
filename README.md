ReactNew
======

Generates a React project skeleton. Inspired by `rails new`.

### Features
* Installs the following packages:
  * `babel-core`
  * `babel-loader`
  * `babel-preset-es2015`
  * `babel-preset-react`
  * `flux`
  * `react`
  * `react-dom`
  * `react-router`
  * `webpack`
* Creates `webpack.config.js` with sourcemap
* Creates `index.html` with entry point
* Creates initial `{PROJECT_NAME}.jsx` component
* Creates folders for `js` and `css`
* Runs `webpack --watch`

### Installation



```bash
Install brew if you don't have it yet. 
Run cmd: brew doctor after installation to see if you are missing any path dependencies.

brew tap email2jie/react
brew install react
```

### Usage
```bash
react new PROJECT_NAME
```
