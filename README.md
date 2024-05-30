# Next.js App Router + React Server Components

Try the demo live here: [**next-rsc-hn.wasmer.app**](https://next-rsc-hn.wasmer.app).

> Note: This app is a clone of [Next.js Server Components demo](https://github.com/vercel/next-react-server-components/), [minimally adapted](https://github.com/wasmer-examples/next-server-components-wasmer-starter/commit/0b2afd3a6e633caf7e43a89f4a89cd349365b482) to run in [WinterJS](https://github.com/wasmerio/winterjs).

## Introduction

This is a demo app of the Hacker News website clone, which shows Next.js App Router with support for [React Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components).

### Running Locally

1. `npm install`
2. `npm dev`

You can run the React Server Components project using Wasmer (check out the [install guide](https://docs.wasmer.io/install)):

```bash
npm run edge:build
npm run edge:preview
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


## Deploy on Wasmer Edge

The easiest way to deploy this Next.js Server Side components app is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: https://next-rsc-hn.wasmer.app/

First, you'll need to run `npm run edge:build`, and then, to deploy to Wasmer Edge:

```bash
wasmer deploy
```
