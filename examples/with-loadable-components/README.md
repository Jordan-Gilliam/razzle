# Razzle loadable-components Example

## How to use

<!-- START install generated instructions please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN update-examples TO UPDATE -->
This is the development documentation for this example

Clone the `razzle` repository:

```bash
git clone https://github.com/jaredpalmer/razzle.git

cd razzle
yarn install --frozen-lockfile --ignore-engines --network-timeout 30000
```

Create and start the example:

```bash
node_modules/.bin/create-razzle-app --example file:examples/with-loadable-components with-loadable-components --no-install

cd with-loadable-components
yarn link ../ --all
yarn start
```
<!-- END install generated instructions please keep comment here to allow auto update -->

## Idea behind the example
This sample has the full SSR setup as described in the [loadable-components docs](https://github.com/smooth-code/loadable-components#server-side-rendering).
It demonstrates simple dynamic imports using [loadable-components](https://github.com/smooth-code/loadable-components) on top of SSR with razzle.
