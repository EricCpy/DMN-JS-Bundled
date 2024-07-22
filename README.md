# dmn-js bundling example

This example showcases how add [dmn-js](https://github.com/bpmn-io/dmn-js)
into a node-style application and bundle it for the browser using
[Webpack](https://webpack.js.org).

## Building the Example

Initialize the project dependencies via

```
npm install
```

To create the sample distribution in the `public` folder run

```
export NODE_OPTIONS=--openssl-legacy-provider
npm run all
```