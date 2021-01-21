# Mojito Client

![codeql workflow](https://github.com/bsladewski/mojito-client/workflows/CodeQL/badge.svg)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/b30db1d5a92346d3963b1271eee23de3)](https://www.codacy.com/gh/bsladewski/mojito-client/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=bsladewski/mojito-client&amp;utm_campaign=Badge_Grade)

The frontend for the Mojito web application. Mojito is a tool for analyzing cryptocurrency prices and configuring bots to automate or assist with trading strategies.

## Dependencies

This project uses [Node.js](https://nodejs.org/en/docs/guides/getting-started-guide/).

Additional dependencies are managed through [Yarn](https://yarnpkg.com/getting-started).

## Usage

### Installation

To get started, clone the repository:

```sh
git clone https://github.com/bsladewski/mojito-client
```

Use `yarn` to install or update project dependencies:

```sh
yarn install
```

```sh
yarn upgrade
```

### Running For Development

To compile and run the application for development use the following command:

```sh
npm run serve
```

### Compiling For Production

To compile and minify project for deployment to production use the following command:

```sh
yarn build
```

## Contributing

1.  [Fork it!](https://github.com/bsladewski/mojito-client/fork)
2.  Create your feature branch: `git checkout -b feature/my-new-feature`
3.  Commit your changes: `git commit -am 'Implemented my cool new feature'`
4.  Push to the branch: `git push origin feature/my-new-feature`
5.  Submit a new Pull Request

## License

The MIT License (MIT)

Copyright (c) 2021 Benjamin Sladewski

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
