# `react-native-nx-monorepo`

This project was generated using [Nx](https://nx.dev).

## Getting Started

```console
yarn
nx run-ios mobile
nx run-android mobile
nx serve web
```

## Apps

- [`/web`](./apps/web/) with [https://nx.dev/packages/react](https://nx.dev/packages/react)
- [`/mobile`](./apps/mobile) with [https://nx.dev/packages/react-native](https://nx.dev/packages/react-native)

## Tooling

- [NativeBase](https://docs.nativebase.io/)

## Adding capabilities to your workspace

Nx supports many plugins which add capabilities for developing different types of applications and different tools.

Below are our core plugins:

- [React](https://reactjs.org): `npm install --save-dev @nrwl/react`
- [Express](https://expressjs.com): `npm install --save-dev @nrwl/express`

There are also many [community plugins](https://nx.dev/community) you could add.

## Generate an application

Run `nx g @nrwl/react:app my-app` to generate an application.

> You can use any of the plugins above to generate applications as well.

When using Nx, you can create multiple applications and libraries in the same workspace.

## Generate a library

Run `nx g @nrwl/react:lib my-lib` to generate a library.

> You can also use any of the plugins above to generate libraries as well.

Libraries are shareable across libraries and applications. They can be imported from `@react-native-nx-monorepo/mylib`.

## Development server

Run `nx serve my-app` for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `nx g @nrwl/react:component my-component --project=my-app` to generate a new component.

## Build

Run `nx build my-app` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `nx test my-app` to execute the unit tests via [Jest](https://jestjs.io).

Run `nx affected:test` to execute the unit tests affected by a change.

## Running end-to-end tests

Run `nx e2e my-app` to execute the end-to-end tests via [Cypress](https://www.cypress.io).

Run `nx affected:e2e` to execute the end-to-end tests affected by a change.

## Understand your workspace

Run `nx graph` to see a diagram of the dependencies of your projects.
