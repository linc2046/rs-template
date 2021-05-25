# Rust Template Project

> basic template for writing rust applications.

## debug

install `vadimcn.vscode-lldb` from https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb

```
.vscode\launch.json
.vscode\ws.code-workspace
```

## build

```
cargo build --verbose
cargo build --release
```

## test

- https://doc.rust-lang.org/book/ch11-01-writing-tests.html

```
cargo test
```

## benchmark

- https://bheisler.github.io/criterion.rs/book/cargo_criterion/configuring_cargo_criterion.html

```
cargo bench
```

## publish

- https://doc.rust-lang.org/cargo/commands/cargo-publish.html

```
cargo publish
```

## reference

- https://jondot.medium.com/my-key-learnings-after-30-000-loc-in-rust-a553e6403c19
- https://blog.ndepend.com/hexagonal-architecture/

```
Core: data, types, abstractions
Logic: algorithms (can sit with core)
Peripherals: networking, HTTP, reporting
App: entry point, uses and glues everything
```

- https://github.com/BurntSushi/ripgrep
- https://doc.rust-lang.org/book/ch14-03-cargo-workspaces.html
- https://jondot.medium.com/12-killer-rust-libraries-you-should-know-c60bab07624f