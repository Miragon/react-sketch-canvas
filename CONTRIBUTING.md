## External contributions

We're currently not accepting pull requests from outside the team. We don't have the resources to fully review and validate external contributions, so we can't guarantee that a merged change keeps the project free of bugs, free of security vulnerabilities or malicious code, and consistent with requirements that make sense for it. Pull requests opened by external contributors will be closed.

If you've found a bug or have an idea, please [open an issue](https://github.com/Miragon/react-sketch-canvas/issues/new) instead. We read every one, and it's the best way to get something onto our radar.

## Prerequisites

[Node.js](http://nodejs.org/) >= v14.17.0 must be installed.

## Installation

- Running `yarn install` in the component's root directory will install everything you need for development.

## Demo Development Server

- Running `yarn install:example` will install the documentation site.

- `yarn watch:example` will run a documentation server with the component's demo app at [http://localhost:3000](http://localhost:3000) with hot module reloading.

## Running Tests

- Install the documentation site using `yarn install:example
- `yarn e2e:ci` will run the tests once. `yarn e2e` will start the cypress test server.

## Building

- `yarn build:prod` will build the component for publishing to npm.
