# Ship-rs

*ship-rs* is a set of scripts written to provide easy-to-configure and ready-to-use compiler actions.
The aim is to allow new delevopers of rust packages, to deploy their applications without much effort.

## Bundle packages

- `rpm`: precompiled rpm to ship
  uses `cargo-generate-rpm`
- `deb`: precompiled dep to ship
  uses `cargo-deb`

### Arquitectures

- x86_64-unknown-linux-gnu
- aarch64-unknown-linux-gnu
- armv7-unknown-linux-gnueabihf
