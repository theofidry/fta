# v0.2.0

- Potentially breaking: changed linux target platforms: we now target `musl` linux on `x86_64`, `arm` and `aarch64`
  - This change should result in a more portable and widely compatible `fta-cli` on Linux systems
- Refactored Github Actions workflow so that the publishing of the npm packages is automatic and coupled with releasing the Rust crate

# v0.1.11

- Improved language detection, add retry mechanism ([#31](https://github.com/sgb-io/fta/pull/31))

# v0.1.10

- Fix binaries for Ubuntu

# v0.1.9

- Set +x permissions on macOS + linux binaries during build

# v0.1.8

- Added WASM npm module
- Refactored internals

# v0.1.7

- Internal fixes for the NPM module

# v0.1.4

- Added `--json` option

# v0.1.3

- Added npm package

# v0.1.2

- Initial release
