# Razzle Polka Example

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
node_modules/.bin/create-razzle-app --example file:examples/with-polka with-polka --no-install

cd with-polka
yarn link ../ --all
yarn start
```
<!-- END install generated instructions please keep comment here to allow auto update -->

## Idea behind the example

An example of how to use a custom, express middleware-compatible server like [polka](https://github.com/lukeed/polka) with razzle. It satisfies the entry points
`src/index.js` for the server and and `src/client.js` for the browser. HMR works for server-side changes too by creating new instances of the polka server handler.
