### Introduce

wasmrc, just wasmrc.


### JSAPI

nonono, waiting for the future plan —— `<script type='module'>`


### Advannced Tools

__Guide__

so, the wasm toolchain can compile C/C++ code to `.wasm` file and the browser will run the code through JS API.

```shell

emcc hello.c -s WASM=1 -o hello.html

emrun --no_browser --port 8080 .

```


__Get a `.wasm` file__

compiled from a `C/C++` program or assembled directly from `s-exprs`.


__Advanced Tools__

+ Binaryen — Compiler and toolchain infrastructure

+ WABT - The WebAssembly Binary Toolkit



