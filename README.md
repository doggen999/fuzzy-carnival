# Fuzzy carnival

POC/ Prototype of a simple Todo application written in React with support of Storybook.

Project is built upon (my own) boiler plate [doggen999/dev-environment-with-storybook@2.1](https://github.com/doggen999/dev-environment-with-storybook/releases/tag/2.1)

## tl;dr

`npm i && npm start`

## Development and bundling

How to develop, bundle and build

### Development w HMR

`npm start` to build with HMR, **N.B.** as a developmer you have to explicitly load/open the `dist/index.html` (e.g. with Live Server).

### Development w Storybook

`npm run storybook` to build and start Storybook server.

### Bundle

`npm run build:dev` builds and bundles with development settings.

`npm run build` builds and bundles w production settings.

## Dependencies and prerequisites

Having Node installed is a prerequisite.

**No support** for anything but OSX as dev environment (atm).
