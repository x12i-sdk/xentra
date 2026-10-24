# @x12i/xentra-docs usage example

Xentra docs knowledge SDK for x12i-docify — install as a devDependency only. Work In Progress documentation covering developer preview, gaps, and GA target.

This consuming application demonstrates **list the bundled guides and read a use case** using the published npm package, pinned to `0.2.1`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

This is a documentation knowledge SDK. It is installed as a development dependency. The example lists its books and use cases, then reads the first available use-case guide from the package.

## When to use the package

- Install @x12i/xentra-docs as a development dependency so the product guides and package index are available to developers and coding assistants.
- Read the bundled xentra documentation or use-case catalog without requiring a live documentation website.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/xentra-docs)
- [Implementation monorepo](https://github.com/x12i/xentra)
- [Reviewed package source](https://github.com/x12i/xentra/tree/004372e6695509bf2e95d2e4e53d4534e81dd312/packages/xentra-docs)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
