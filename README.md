# hello-wasm

## To try-out the javascript bindings
Navigate to site folder and run `npm install`

Then run the webpack-server with `npm run serve`

Load http://localhost:8080


## To build your own WebAssembly package
First Install Rust language support for your environment https://www.rust-lang.org/tools/install

Install the Rust package `wasm-pack` with cargo. Run `cargo install wasm-pack`

Build the WebAssembly package with `wasm-pack build` or `wasm-pack build --scope mynpmusername` to make a npm package.


