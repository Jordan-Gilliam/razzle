# Razzle With LESS Example

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
node_modules/.bin/create-razzle-app --example file:examples/with-less with-less --no-install

cd with-less
yarn link ../ --all
yarn start
```
<!-- END install generated instructions please keep comment here to allow auto update -->

## Idea behind the example

This is a basic, bare-bones example of how to use razzle. It satisfies the entry points and use less as styling language
You can import anything from node_modules or other less files, like Ant Design, etc.
`src/index.js` for the server, `src/client.js` for the browser, and `src/App.less` for LESS style.
