Run

```
yarn webpack
```

---

```
asset my-first-webpack.bundle.js 3.05 KiB [compared for emit] (name: main)
runtime modules 668 bytes 3 modules
./src/main.js 95 bytes [built] [code generated]

ERROR in ./src/main.js 1:0-48
Module not found: Error: Can't resolve 'react/jsx-runtime' in '/home/nicolo/Documenti/dev/test-react-webpack-5/src'
Did you mean 'jsx-runtime.js'?
BREAKING CHANGE: The request 'react/jsx-runtime' failed to resolve only because it was resolved as fully specified
(probably because the origin is a '*.mjs' file or a '*.js' file where the package.json contains '"type": "module"').
The extension in the request is mandatory for it to be fully specified.
Add the extension to the request.

webpack 5.1.3 compiled with 1 error in 210 ms
```