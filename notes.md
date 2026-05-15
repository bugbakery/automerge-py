brew install zig
rustup target add x86_64-unknown-linux-gnu
rustup target add aarch64-unknown-linux-gnu
rustup target add x86_64-apple-darwin
rustup target add aarch64-apple-darwin
uvx maturin build --release --target x86_64-apple-darwin --zig -i 3.12

rustup target add x86_64-pc-windows-msvc
