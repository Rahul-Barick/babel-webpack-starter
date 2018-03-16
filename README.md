# babel-webpack-starter
1. Webpack in it's simple form is module bundler and Babel is a transpiler.

2. Webpack takes modules with dependencies and generates static assets representing those modules

3. It understands ``css`` and ``images`` are also dependencies

4. Webpack ``-w/watch`` or ``watch:true`` in config file for watching continous changes in file and automatically it will do the bundling process

5. Webpack only knows how to read and understand js files

6. Loaders teach webpack how to load files for bundling

7. We are using 3rd Party transpiler like babel to convert our es6/es7 code to old Javascript syntax (es5).

# Development Server

For live reload,webpack creates a dev server to easily check our code

Just type ``webpack-dev-server`` in project root directory

Browse http://localhost:8080
