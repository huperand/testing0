# testing0
# testing contract on cairo


Clone this repo
git clone https://github.com/starknet-edu/deploy-cairo1-demo
cd deploy-cairo1-demo

Installing the Cairo one compiler (first time installation)
it clone https://github.com/starkware-libs/cairo/
cd cairo
git checkout 9c190561ce1e8323665857f1a77082925c817b4c
cargo build --all --release

Set up a python virtual environment
python3.9 -m venv ~/cairo_venv_v11
source ~/cairo_venv_v11/bin/activate
