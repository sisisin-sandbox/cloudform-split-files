# cloudform split multiple files

# reproduce the phenomenon

```bash
$ npm install
$ npx cloudform ./template.ts

module.js:545
    throw err;
    ^

Error: Cannot find module './setting'
    at Function.Module._resolveFilename (module.js:543:15)
    at Function.Module._load (module.js:470:25)
    at Module.require (module.js:593:17)
    at require (internal/module.js:11:18)
    at eval (eval at compile (/Users/sisisin-mbp/dev/sandbox/cloudform-split-files/node_modules/cloudform/dist/cli/cloudform.js:42:21), <anonymous>:4:19)
    at compile (/Users/sisisin-mbp/dev/sandbox/cloudform-split-files/node_modules/cloudform/dist/cli/cloudform.js:42:21)
    at Object.<anonymous> (/Users/sisisin-mbp/dev/sandbox/cloudform-split-files/node_modules/cloudform/dist/cli/cloudform.js:56:1)
    at Module._compile (module.js:649:30)
    at Object.Module._extensions..js (module.js:660:10)
    at Module.load (module.js:561:32)
```

