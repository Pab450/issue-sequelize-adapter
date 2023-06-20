
## How to reproduce the error

```
npm i
```

```
npm run dev
```

## Console error

```
node:internal/errors:496
    ErrorCaptureStackTrace(err);
    ^

Error [ERR_MODULE_NOT_FOUND]: Cannot find module '/Users/pablo/Documents/issue-sequelize-adapter/node_modules/@auth/sequelize-adapter/models' imported from /Users/pablo/Documents/issue-sequelize-adapter/node_modules/@auth/sequelize-adapter/index.js
    at new NodeError (node:internal/errors:405:5)
    at finalizeResolution (node:internal/modules/esm/resolve:224:11)
    at moduleResolve (node:internal/modules/esm/resolve:837:10)
    at defaultResolve (node:internal/modules/esm/resolve:1035:11)
    at DefaultModuleLoader.resolve (node:internal/modules/esm/loader:269:12)
    at DefaultModuleLoader.getModuleJob (node:internal/modules/esm/loader:153:32)
    at ModuleWrap.<anonymous> (node:internal/modules/esm/module_job:76:33)
    at link (node:internal/modules/esm/module_job:75:36) {
  code: 'ERR_MODULE_NOT_FOUND'
}
```

## Package used to reproduce this error

@auth/sequelize-adapter, 1.0.0
