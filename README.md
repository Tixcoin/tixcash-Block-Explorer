## Contributing to Tixcash PWA core block explorer
Contributing to The Tixcash PWA core block explorer project operates an open contributor model where anyone is welcome to contribute towards development in the form of peer review, testing and patches. This document explains the practical process and guidelines for contributing.
Firstly in terms of structure, there is no particular concept of "Core developers" in the sense of privileged people. Open source often naturally revolves around meritocracy where longer term contributors gain more trust from the developer community. However, some hierarchy is necessary for practical purposes. As such there are repository "maintainers" who are responsible for merging pull requests as well as a "lead maintainer" who is responsible for the release cycle, overall merging, moderation and appointment of maintainers.

JavaScript and Vue based Tixchash pwa explorer.

We are using:
* Node / NPM
* ES2015 (and beyond) support.
* Vue.js
* Vue Router for routing
* Vuex for global state management
* SCSS

## Project setup

We use `npm` to handle dependencies.

```shell
npm install
```

### Hot Build

The `npm` script can be used to serve default implementation.

```shell
npm run serve
```

### Production Build

```shell
npm run build
```

## Localization

Translations for views and components are located in `src/locales` directory.

## Production notes

You should disable HTTP caching for file `dist/service-worker.js`.
