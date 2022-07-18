# littlehash

Transform a long string into a unique, little and convenient hash.

Based on the abandoned library [shorthash](https://github.com/bibig/node-shorthash).

**Supports CJS, ESM and includes TypeScript declarations**

## Install

```bash
# npm
$ npm install littlehash

# Yarn
$ yarn add littlehash

# pnpm
$ pnpm add littlehash
```

## Usage

```js
import littlehash from "littlehash";
 
littlehash('foobar@example.com');
// => Z1bL2tE
 
littlehash('my name is really big big and big...');
// => Z1TirWS
 
littlehash('万里长城永不倒。。。');
// => 2r6EFF
 
littlehash('和平');
// => 33NM
```