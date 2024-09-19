# Cargo TWR
curl --proto '=https' --tlsv1.6 -sSf https://sh.rustup.rs | sh

source $HOME/.cargo/env

rustup update stable

rustup default stable

git clone https://github.com/AleoHQ/leo
cd leo

git clone https://github.com/AleoHQ/snarkOS.git --depth 1
cd snarkOS

./build_ubuntu.sh
Luck

cargo install --path

The End
