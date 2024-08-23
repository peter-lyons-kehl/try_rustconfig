# Purpose

This shows that `RustConfig` file is not used by Rust itself. [`RustConfig`](./RustConfig) indicates
`nightly`, but if you select `stable` as the default toolchain (as per below), then `RustConfig`
file has no effect.

Try:

- `rustup default stable`
- `cargo check`

   It fails.
