[![Build Status](https://travis-ci.org/yurydelendik/wasmparser.svg?branch=master)](https://travis-ci.org/yurydelendik/wasmparser)

Simple streamable WebAssembly binary parser.

## Test

### Running Tests

```
npm test
```

### Creating Tests
Place a `.wasm` and an associated `.wasm.out` file in the `test` directory.
The testing harness will compare the parsing output of the `.wasm` file against the `.wasm.out` file.
You can use the `npm test update` command to automatically create a `.out` files. This is useful if you have made a change that affects the tests.
