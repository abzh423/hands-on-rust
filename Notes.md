### Cargo

Rust has its own formatter called with command:
cargo fmt
Also we have linter:
cargo clippy


You can add a few qualifiers to provide fine-grained control over what crate
version you use:

• =0.8.0 will only use version 0.8.0 - nothing lower or higher.
• ^0.8.0 will use any version equal to or greater than 0.8.0, but only within
the 0.x version range.
• ~0.8.0 will use any minor version greater than 0.8.0. Updates will automatically be applied, even if they break the crate’s API.