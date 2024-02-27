# rust-yew-frontend


## Description
Building a frontend with Rust has become so easy with yew.


## Installation and Running

Make sure you have Rust and Cargo installed. You can find installation instructions on the Rust website `https://www.rust-lang.org/tools/install`.

To run it, make sure you have trunk installed:
```
cargo install trunk
```
This installs trunk globally on your system
What is Trunk? Trunk is a development server for WASM applications which is used to develop and serve the application.

also make sure you can compile to wasm32
```
rustup target add wasm32-unknown-unknown
```

once you have both these done, clone this repo, cd into it, and just run
```
git clone https://github.com/Yadav106/rust-yew-frontend.git
cd rust-yew-frontend
trunk serve
```
