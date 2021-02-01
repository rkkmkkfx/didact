# didact
Tiny React clone based on the original Didact library which can be found at: https://github.com/pomber/didact

The original Didact is a tiny React-like library used for educational purposes. The full article can be found at: https://pomb.us/build-your-own-react/. This is my copy of didact which has also been published to npm so can be used directly in my personal projects.

Note: if you're looking for the original Didact, please go to https://www.npmjs.com/package/didact

The original Didact source code has been slightly modified here as follows:
1. Conversion to TypeScript and split into multiple files for improved readability.
2. Inclusion of tests

The code has been split into a number of TypeScript modules allowing for better understanding of the library. The build process compiles to regular .js files. These files are placed in the /dist folder.

Note that the **compile** script should be used instead of the **build** script.

This is also being used as a training project for the following:
1. Test publishing packages to npm
2. Creating a full reference application for npm packages, including:
   1. Code in TypeScript
   2. use of Bundler (WebPack) in the build process
   3. Testing the package locally

## Bibliography
- https://docs.npmjs.com/cli/v6/commands/npm-link
- https://dev.to/charperbonaroo/creating-a-ts-written-npm-package-for-use-in-node-js-or-browser-5gm3
- https://medium.com/javascript-in-plain-english/how-to-develop-test-run-and-publish-an-npm-module-react-and-webpack-f436adb54bbb
- https://docs.npmjs.com/updating-your-published-package-version-number
- https://medium.com/cameron-nokes/the-30-second-guide-to-publishing-a-typescript-package-to-npm-89d93ff7bccd


