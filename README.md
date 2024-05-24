# rustc ICE repro

To trigger the ICE:

```bash
rustup toolchain install nightly-2024-05-24
cargo +nightly-2024-05-24 build --package crashy-macro
```

Example ICE log: [rustc-ice-2024-05-24T04_46_00-92305.txt](./rustc-ice-2024-05-24T04_46_00-92305.txt)
