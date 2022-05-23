# `react-native-nx-monorepo`

- [Getting started with Nx](./docs/nx.md)
- [FAQ](./docs/faq.md)

## Tooling

- Monorepo generated using [Nx](https://nx.dev/getting-started/intro)
- UI design with [NativeBase](https://docs.nativebase.io/)
- Design system with [Storybook](https://nx.dev/storybook/overview-react#storybook)

## Getting Started

```console
yarn
nx run-ios mobile
nx run-android mobile
nx serve web
nx run mobile:storybook
nx run web:storybook
```

## Apps

- [`/web`](./apps/web/) with [https://nx.dev/packages/react](https://nx.dev/packages/react)
- [`/mobile`](./apps/mobile) with [https://nx.dev/packages/react-native](https://nx.dev/packages/react-native)
