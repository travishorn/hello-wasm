# Hello WASM

A simple hello world app using Rust and WebAssembly. Simply displays an alert
saying "Hello WebAssembly!" when a user visits the page. Uses
[wasm-pack](https://github.com/rustwasm/wasm-pack) to bind Rust/JavaScript code.
Based on
[Compiling Rust to WebAssembly on MDN](https://developer.mozilla.org/en-US/docs/WebAssembly/Rust_to_wasm).

## Installing

Go to https://www.rust-lang.org/tools/install and follow the instructions to
install Rust.

Then, go to https://rustwasm.github.io/wasm-pack/installer and follow the
instructions to install wasm-pack

Clone this repository

```sh
git clone https://github.com/travishorn/hello-wasm
```

Change into the directory

```sh
cd hello-wasm
```

Build the package

```sh
wasm-pack build --target web
```

## Deployment

Serve the root directory of the project with a local web server (e.g. `python3
-m http.server`)

Load `index.html` from the web server. If you used the Python3 example:
http://localhost:8000

## License

MIT/Apache-2.0
