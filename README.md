# Transmute dApp

[![Build Status](https://travis-ci.org/transmute-industries/dapp.svg?branch=master)](https://travis-ci.org/transmute-industries/dapp)
[![Coverage Status](https://coveralls.io/repos/github/transmute-industries/dapp/badge.svg?branch=master)](https://coveralls.io/github/transmute-industries/dapp?branch=master)

Create an issue if you want a feature or need help!

Please fork and submit PRs, together we can make dApp dev transcendent!

You will need to install NodeJS - https://nodejs.org/en/

### Run with docker

```
$ npm run docker:build
$ npm run docker:run
```

If you already had ipfs installed, you may need to `npm run ipfs:allow` this will add localhost:3000 to ipfs access control allow origin.

- http://localhost:3000/dapp

## Get Started Instructions

- http://bit.ly/2uzpxVJ

### Run without docker
```
$ git clone https://github.com/transmute-industries/dapp.git
$ cd dapp
$ npm install
$ npm run ipfs
$ npm run testrpc
$ npm run test
$ npm run migrate
$ npm run start
```

### Features

- Docker with React Hot Module Reload!
- Jest and Truffle Tests
- TypeScript
- Redux + Transmute Framework (Redux for Smart Contracts)
