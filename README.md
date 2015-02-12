# Start-Reacting
This is a very basic template to building React applications taking advantage of [browserify](http://browserify.org/), [reactify](https://github.com/andreypopp/reactify), and [http-server](https://www.npmjs.com/package/http-server). Browserify is a common build tool that uses ```require``` to compile commonjs modules. Reactify is just a transform for browserify that allows us to take advantage of [JSX](http://facebook.github.io/react/docs/jsx-in-depth.html). http-server is just a simple server that hosts a directory on your local machine.

npm scripts provide shortcuts to using this repo.

First, ```npm install``` to resolve all dependencies.

From there:
* ```npm run bundle``` - run browserify and build code
* ```npm run server``` - runs bundle then serves your code on ```:8080```
