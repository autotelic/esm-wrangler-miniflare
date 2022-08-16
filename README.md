# esm-wrangler-miniflare

Minimal repo to show miniflare / wrangler configuration inconsistency with module worker with esbuild

```
$ npm i
```

to install dependencies

then

```
$ npm run wrangler
```

to run module worker using wrangler v2.0.26, runs without error

```
$ npm run miniflare
```

to run module worker using miniflare v2.6.0, throws error: `SyntaxError: Unexpected token 'export'`
