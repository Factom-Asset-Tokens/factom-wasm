# factom-wasm

This is a simple demo application to explore building a Wasm runtime and
toolchain.

## Build and run
```
cd src/c/api
make
cd ../../..
make
factom-wasm -wasm src/c/api/api.wasm -call run_all
```

