# New Relic Deployments support for Node.js

Command-line utility and library for [New Relic]() deployments.

## Using as CLI

Install package globally,

```bash
$ npm install -g newrelic-deployments
```

Right after application deployment, inside sources folder,

```bash
$ newrelic-deployments .
```

For convince, it's recommended to use it as `git-push` hook.

### Options

TDB.

## Using as Library

Install package locally,

```bash
$ npm install --save newrelic-deployments
```

In your main module, at the top (or right after `require('newrelic')`),

```js
require('newrelic-deployments')
```

### Options

TDB.

# License

MIT 
