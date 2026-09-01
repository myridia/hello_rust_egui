# AGENTS.md — hello_rust_egui

## What this is
A Rust "Hello" example using the egui/eframe immediate-mode GUI framework, set up for cross-compilation.

## Stack
- Rust
- egui / eframe
- Zig (for cross-compilation)
- Cargo

## Build
```bash
cargo build       # build for the host
# cross-targets use rustup targets + Zig linker (see README)
```
Enable Zig and add your targets first (`rustup target add ...`, `export PATH=$PATH:$(pwd)/zig`).

## Run
```bash
cargo run
```

## Structure
- `src/main.rs` — egui app entry point
- `Cargo.toml` — depends on `eframe`
- `Makefile` / `install_zig.sh` — cross-compile helpers

## Conventions
- No comments in code unless asked.
- Verify: `cargo check && cargo build`
