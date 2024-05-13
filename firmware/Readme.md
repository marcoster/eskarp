# Setup
```
rustup target add thumbv6m-none-eabi
cargo install elf2uf2-rs
```

# Build / Run
```
cargo build --release --target thumbv6m-none-eabi
# or
cargo run --release --target thumbv6m-none-eabi
```

