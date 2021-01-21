this package build to gen the diversify address from viewing key:

1. install rust:
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

2. clone repo:
git clone https://github.com/hoangphuongcs/librustzcash/

3. cd to the repo:
cd librustzcash/cash_client_backend/
cargo build --example diversify-address --release

4. copy builded file here:
librustzcash/target/release/examples/diversify-address
