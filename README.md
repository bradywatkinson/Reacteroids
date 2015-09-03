React Transform Boilerplate
=====================

A *new* Webpack boilerplate with:

* hot reloading React components;
* error handling inside component `render()` function;
* error handling for syntax errors.

The component instrumentation is implemented on top of **[babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform)**:

* **[react-transform-webpack-hmr](https://github.com/gaearon/react-transform-webpack-hmr)** handles hot reloading
* **[react-transform-catch-errors](https://github.com/gaearon/react-transform-catch-errors)** catches component errors

The syntax errors are displayed in an overlay by **[@glenjamin](https://github.com/glenjamin)**’s **[webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware)** which is used instead of Webpack Dev Server.

## Try It

```
git clone https://github.com/gaearon/react-transform-boilerplate.git
cd react-transform-boilerplate
npm install
npm start
open http://localhost:3000
```

## License

MIT
