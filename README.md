# RIDE - Rust IDE

A minimal, fast IDE for Rust developers, written entirely in Rust.

## Vision

An open-source, Rust-native IDE focused on:

- **Rust-first**: Optimized for Rust development (with HTML/CSS/JS support)
- **Performance**: No Java, no Electron - pure Rust
- **Simplicity**: Only essential features, no bloat
- **Nushell integration**: Modern shell as built-in terminal

## Why?

- Existing Rust IDEs (RustRover) are Java-based and slow
- Existing Rust IDEs are proprietary/paid for commercial use
- No IDE is written in Rust, for Rust developers

## Planned Features

### Core Editor
- [ ] Syntax highlighting (tree-sitter)
- [ ] Mouse-based navigation and selection
- [ ] File explorer
- [ ] Multi-tab editing
- [ ] Search & replace

### Rust Integration
- [ ] rust-analyzer LSP
- [ ] `cargo check` / `cargo build` / `cargo run` / `cargo clippy`
- [ ] Inline error display
- [ ] Autocomplete

### Terminal
- [ ] Integrated nushell terminal
- [ ] Command output capture

### Supported Languages
- Rust (primary)
- HTML
- CSS
- JavaScript

## Tech Stack (Planned)

| Component | Library |
|-----------|---------|
| GUI | egui or iced |
| Syntax Parsing | tree-sitter |
| Terminal | portable-pty |
| File Watching | notify |

## Alternatives

If you need a working solution today:

| Editor | Description |
|--------|-------------|
| [Zed](https://zed.dev) | Fast, Rust-based, AI integration |
| [Lapce](https://lapce.dev) | Rust-based, VSCode-like |
| [Helix](https://helix-editor.com) | Terminal-based, modal editing |

## License

MIT

## Status

**Early concept phase** - contributions and ideas welcome.
