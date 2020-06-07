# Razzle Custom Babel Configuration Example

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
node_modules/.bin/create-razzle-app --example file:examples/with-custom-babel-config with-custom-babel-config --no-install

cd with-custom-babel-config
yarn link ../ --all
yarn start
```
<!-- END install generated instructions please keep comment here to allow auto update -->


## Idea behind the example
This is an example of how to extend Razzle with a custom `.babelrc` file.
