# [React ES6 ComponentModule](https://gokulkrishh.github.io/create-react-component/) [![Build Status](https://travis-ci.org/gokulkrishh/create-react-component.svg?branch=master)](https://travis-ci.org/gokulkrishh/create-react-component)

*Empty ES6 npm component module for react.  Starter for your own npm module deployment.*



### Intro
I've been developing applications for create-react-app, but I could not use that to build a component that I want to publish as an NPM module.
There are many tutorials about how to do this, but I wanted a simpler, "let's just do it" repo to pull from.
This repo is based off of the pre-ES6 work here: https://gokulkrishh.github.io/create-react-component


##### 1. Clone the repository

```bash
git clone https://github.com/gokulkrishh/create-react-component newCompName
```

##### 2. Make it as your own repository

```bash 
rm -rf .git
git init
```

##### 3. Install dependencies

```bash
npm install
```

### Folder Structure

```
.
├── test/
├── dist/
├── demo/
├── src/
│   └── index.js
│   └── styles.css
└── package.json
└── webpack.build.config.js
└── webpack.config.js
```

### Features

- [`Webpack v2`](https://webpack.js.org/) for bundling the dependencies.

- `ES6` support.

- `ESLint` support.

- [`Jest`](https://facebook.github.io/jest/docs/tutorial-react.html) for test cases.

- `Travis CI` support.

- Deploy demo page to `gh-pages`.

### Make it as your own component

- In package.json file change the name from `create-react-component` to `your-component-name`.

- Search for `HelloWorld` and replace it with `your component name`.

### [Available scripts](https://github.com/gokulkrishh/create-react-component/blob/master/package.json#L28)

- `npm run start`  - To start webpack dev-server.

- `npm run watch`  - To watch a file change and build the component.

- `npm run build`  - To produce the build file.

- `npm run deploy` - To deploy the demo folder to gh-pages.

- `npm run test`   - To run test cases.


### [Publish as node module](https://docs.npmjs.com/getting-started/creating-node-modules)

```bash 
npm publish
```

*Make sure your package name, version and other information in `package.json` is correct.*

## License

MIT © [Jason Henriksen](https://github.com/jason-henriksen)
