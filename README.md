# executable-from-scratch

From the article [Writing a Linux executable from scratch with x86_64-unknown-none and Rust](https://vulns.xyz/2023/03/linux-executable-from-scratch-with-x86_64-unknown-none-rust/).

## Build and run

Add the target architecture:
```sh
$ rustup target add x86_64-unknown-none
```

Build the binary:
```sh
$ cargo build --release --target x86_64-unknown-none
```

Run:
```sh
$ target/x86_64-unknown-none/release/executable-from-scratch
Hello world
```
