# Razzle with-styled-components Example

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
node_modules/.bin/create-razzle-app --example file:examples/with-styled-components with-styled-components --no-install

cd with-styled-components
yarn link ../ --all
yarn start
```
<!-- END install generated instructions please keep comment here to allow auto update -->

## Idea behind the example
This is a basic, bare-bones example that shows a very minimal implementation
of [StyledComponents](https://github.com/styled-components/styled-components).
It satisfies the entry points `src/index.js` for the server and`src/client.js`
for the browser.
There are comments in `src/server.js` to show how the styles are gathered and
rendered into to the DOM
