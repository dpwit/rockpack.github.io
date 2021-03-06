# rockpack.github.io

## Introduction to Rockpack

Rockpack is just like Create react App (where it bundles the basic components in one, easy to run package), only better. It still simplifies setting up a React app but it also has a number of additional features already included such as Webpack, server-side rendering, bundling, linting and testing.

### Rockpack modules

One of the good things about Rockpack is the fact that it has a 'modular architecture', meaning it has different modules you can use, so you can only use the Rockpack module you need.

### Modules

- [@rockpack/compiler](#compiler)
- [@rockpack/ussr](#server-side-rendering)
- @rockpack/tester
- @rockpack/codestyle
- @rockpack/logger
- @rockpack/localazer

### compiler
#### @rockpack/compiler

This is a Webpack based React bundler that is preconfigured with all the necessary loaders and plugins, using the best practices right out of the box.

To use this module simply run the following in Terminal or Command Prompt...

```
npm install @rockpack/compiler --save-dev
```

### server side rendering
#### @rockpack/ussr

