# Express API template

by: https://www.smashingmagazine.com/2020/04/express-api-backend-project-postgresql/

[![Build Status](https://app.travis-ci.com/elisabethmarie/express-api-template.svg?branch=main)](https://app.travis-ci.com/elisabethmarie/express-api-template)

[![Coverage Status](https://coveralls.io/repos/github/elisabethmarie/express-api-template/badge.svg?branch=main)](https://coveralls.io/github/elisabethmarie/express-api-template?branch=main)

`@babel/cli` - A required install for using `babel`. It allows the use of Babel from the terminal and is available as `./node_modules/.bin/babel`.

`@babel/core` - Core Babel functionality. This is a required installation.

`@babel/node` - This works exactly like the Node.js CLI, with the added benefit of compiling with `babel` presets and plugins. This is required for use with `nodemon`.

`@babel/plugin-transform-runtime` - This helps to avoid duplication in the compiled output.

`@babel/preset-env` - A collection of plugins that are responsible for carrying out code transformations.

`@babel/register` - This compiles files on the fly and is specified as a requirement during tests.

`@babel/runtime` - This works in conjunction with `@babel/plugin-transform-runtime`.

### Testing

`mocha` - test runner

`chai` - used to make assertions

`nyc` - collect test coverage report

`sinon-chai` - extends chai’s assertions

`supertest` - used to make HTTP calls to our API endpoints

`coveralls` - for uploading test coverage to coveralls.io
