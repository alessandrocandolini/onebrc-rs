[![Rust CI](https://github.com/alessandrocandolini/onebrc-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/alessandrocandolini/onebrc-rs/actions/workflows/rust.yml)
[![codecov](https://codecov.io/gh/alessandrocandolini/onebrc-rs/graph/badge.svg?token=LWnCnh8vxT)](https://codecov.io/gh/alessandrocandolini/onebrc-rs)
# onebrc-rs

## Run

Run tests:
```sh
cargo test
```

Run via cargo:
```sh
cargo run
```

Build and run executable in release mode
```sh
cargo build --release
./target/release/onebrc-rs
```

Run formatter:
```
cargo fmt
```
Use
```
cargo fmt -- --check
```
to check formatting without changing files.

Run linter:
```
cargo clippy --all-targets -- -D warnings
```

