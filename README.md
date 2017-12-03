# Crust---C-to-Rust

Simple example of how to call functions written in Rust from C code. Literally the "Hello World!".

This code is part of [my blog post](http://spejss.com/index.php/2017/12/03/extending-c-with-rust-101/).

## Running

```
cargo build --release

gcc -o crust ./src/crust.c -Isrc  -L. -l:target/release/libcrust.so

./crust
```
