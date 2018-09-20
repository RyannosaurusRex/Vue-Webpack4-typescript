# Vue Webpack4 Typescript Example

> This is an example of a `vue init webkit ______` starter kit app that has been upgraded to use Webpack4 and typescript.  When updating to Webpack 4, the way CSS is extracted changed from a plugin to an optimizer within Webpack itself, so that update was made.  In addition, the Babel loaded was replaced with ts-loader to allow the use of typescript in your files (.vue and the main app .js files were updated to .ts). Further, the es-linter was replaced with the ts-linter to allow linting to continue.

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
