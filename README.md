# tree-sitter

This repository uses GitHub Actions to build the [tree-sitter](https://github.com/tree-sitter/tree-sitter) tool.

This repository builds the musl version of the binaries to avoid the [GLIBC issues](https://github.com/tree-sitter/tree-sitter/issues/2272).

Specifically, this repository builds the following architectures:

- aarch64-unknown-linux-gnu
- aarch64-unknown-linux-musl
- aarch64-apple-darwin
- x86_64-unknown-linux-gnu
- x86_64-unknown-linux-musl
- x86_64-apple-darwin
