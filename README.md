[![Build Status](https://travis-ci.org/r-park/react-redux-seed.svg?branch=master)](https://travis-ci.org/r-park/react-redux-seed)


# React Redux Seed

- React `~0.14.3`
- React-Router `~1.0.1`
- Redux `~4.0.0`
- React-Redux
- Redux-Simple-Router
- Redux-Thunk
- Babel `~6.3`
- ES6
- Gulp `4.0.0-alpha.2`
- Jasmine
- Karma
- SASS
- Webpack
- Webpack Dev Server


## Prerequisites
Node `~5.1`


## Installing dependencies
```bash
$ npm install
```


#### Gulp v4 (optional)
```bash
$ npm install -g gulpjs/gulp-cli#4.0
```
The gulp tasks require gulp v4-alpha. If you don't wish to globally install the v4 gulp-cli, you can run the gulp tasks using the locally installed gulp under `./node_modules/.bin` — for example:
```bash
$ ./node_modules/.bin/gulp test
```


## Gulp Tasks
#### Developing
```bash
$ gulp
```
Executing the default `gulp` command will:
- Build the project
- Start the Webpack dev server at <a href="http://localhost:3000" target="_blank">localhost:3000</a>
- Watch for changes to the source files and process changes


#### Testing
```bash
$ gulp test.watch
```
Executing `gulp test.watch` will:
- Run the test suites
- Watch for changes to the source files
- Re-run the tests whenever the sources are modified

For a single test run without auto-watch, execute `gulp test` instead.
