# SigmaOS-linux-slackware

> **Slackware integration** — Linux distribution persona for SigmaOS.

Part of the [SigmaOS](https://github.com/AaryanSinghChauhan09/SigmaOS) ecosystem.  
[Slackware Linux (traditional, manual package mgmt)](https://slackware.com)

## Quickstart

```bash
cargo test    # run deterministic AAA unit tests
cargo check   # verify compilation
```

## Component Role

This crate implements the `slackware` subsystem for SigmaOS:
- Fully real Rust implementation (no stubs)
- Fail-fast validation with typed errors
- Deterministic unit tests (Arrange-Act-Assert pattern)
- Single Responsibility, Modular, Zero-Copy where applicable

## API

```rust
use sigmaos_linux_slackware::*;
// See src/lib.rs for full public API
```

## Documentation

Full documentation is in the [SigmaOS GitHub Wiki → Linux-Distro-Personas](https://github.com/AaryanSinghChauhan09/SigmaOS/wiki/Linux-Distro-Personas).

## License

GPL-2.0
