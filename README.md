# 🐣 TypeScript Starter

A basic TypeScript starter project.

### Uses

- [Yarn](https://yarnpkg.com/getting-started) for package management
- [Jest](https://jestjs.io/docs/getting-started) for testing
- [ESLint](https://eslint.org/docs/latest/use/getting-started) and [Prettier](https://prettier.io/docs/en/) for linting and formatting
- [Husky](https://github.com/typicode/husky) for Git pre-commit hooks
- [nodemon](https://github.com/remy/nodemon) for running the app in local development with automatic restart

### Scripts

#### `yarn start:dev`

Starts the application in development using `nodemon` and hot-reloads using `ts-node`.

#### `yarn start`

Starts the application in production by building the project with `yarn build` and executing the compiled JavaScript at `./build/index.js`.

#### `yarn build`

Cleans build folder and builds the app out to `./build` directory.

#### `yarn test`

Runs the `jest` tests.
