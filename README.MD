# @imaginary-cloud/prettier-config
Quickly format your JavaScript files with this easy to install and use Prettier configuration. This configuration is used on our ESLint React configuration, take a look at [eslint-config-react](https://github.com/imaginary-cloud/eslint-config-react)

## Purpose
[Prettier](https://prettier.io/) is an opinionated code formatter easy to configure and integrate with Code Editors. This configuration aims to quickly install and config JavaScript projects for consistent code style standards.

This package can be used as a stand-alone config or integrated with any linter. If you look to integrate with [ESLint](https://eslint.org/) for React projects take a look at our configuration [eslint-config-react](https://github.com/imaginary-cloud/eslint-config-react) using this Prettier config

## How to install
```
npm install prettier @imaginary-cloud/prettier-config
```
## How to use
In your `package.json` add:

```
"prettier": "@imaginary-cloud/prettier-config"
```
Under script objects
```
"format": "prettier --write \"{,!(node_modules)/**/}*.js\""
```

## Contributing
How to [contribute](/CONTRIBUTING.MD) to this open source library

## License

Copyright © 2010-2020 [Imaginary Cloud](https://www.imaginarycloud.com). This library is licensed under the MIT [license](./LICENCE).

## About Imaginary Cloud

![Imaginary Cloud](https://s3.eu-central-1.amazonaws.com/imaginary-images/Logo_IC_readme.svg)

At Imaginary Cloud, we build world-class web & mobile apps. Our Front-end developers and UI/UX designers are ready to create or scale your digital product. Take a look at our [website](https://www.imaginarycloud.com/) and [get in touch!](https://www.imaginarycloud.com/contacts) We'll take it from there.