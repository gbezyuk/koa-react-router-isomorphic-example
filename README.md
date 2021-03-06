# Koa-React-Router-Isomorphic-Example
(https://github.com/gbezyuk/koa-react-router-isomorphic-example)

A simple example of a isomorphic (universal) javascript application using Koa and React-Router.

## Example
http://koa-react-router-isomorphic-example.gbezyuk.ru:3030
## Development Setup
```
# npm install -g webpack
npm install
webpack
babel-node src/server.js
# and go to localhost:3000
```

## Features
* Four routes: index, about, contacts, 404
* Server-side rendering using Koa
* Asset bundling using WebPack
* ES6 with Babel

## Known Issues
* Home link is always active. IndexLink usage is causing application failure, see [Navigation.js](src/components/elements/Navigation.js)
