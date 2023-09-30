# TON crypto primitives

## 🚨 Repository Deprecated and Moved! 🚨

**This repository has been deprecated and is no longer actively maintained.** We have moved our project to a new repository, which you can find here: [ton-org/ton-crypto-primitives](https://github.com/ton-org/ton-crypto-primitives). The new NPM package is available here: [@ton/crypto-primitives](https://www.npmjs.com/package/@ton/crypto-primitives)

Please make sure to update your bookmarks and star the new repository to stay up-to-date with the latest developments and updates. This repository will be archived and eventually removed.

**Thank you for your continued support!**
___________

Cross-platform crypto primitives for building apps for TON blockchain. For internal imlementation of `ton-crypto`.

[![Version npm](https://img.shields.io/npm/v/ton-crypto-primitives.svg?logo=npm)](https://www.npmjs.com/package/ton-crypto-primitives)

## Features

- 🦺 Crypto primitives: SHA-256, SHA-512, PBKDF2-SHA-256, HMAC-SHA-512
- 🚀 Promise-based API
- 🏎 Built on top of Buffer (polifil required in browsers)
- 🍰 No reimplemented crypto

## Install

```bash
yarn add ton-crypto-primitives buffer
```

#### Browser polifil

```js
// Add before using library
require("buffer");
```

## React Native
To make it work on react native `expo-random` module is required:
`
yarn install expo-random
`

# License

MIT
