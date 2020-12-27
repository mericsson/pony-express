# pony-express

## Running

Tested with node 12 only.

```
nvm use 12
```

Install and build static webpage file.

```
npm install
npm run build
```

Open static web page file.

```
open dist/index.html
```

## TODO

- [ ] Add personal userbase key.
- [ ] Deploy to Netlify.

## Deploys

[![Netlify Status](https://api.netlify.com/api/v1/badges/ef422b54-c06a-45e1-aa8d-8c324e4813f5/deploy-status)](https://app.netlify.com/sites/frosty-banach-a18f1b/deploys)

## Background

This project derives from [Ugliest Todo tutorial](../ugliest-todo) written in [TypeScript](https://www.typescriptlang.org/).

## Type Definitions

The userbase-js [type definitions](https://github.com/encrypted-dev/userbase/blob/master/src/userbase-js/types/index.d.ts) are included in the NPM package and work out of the box.
