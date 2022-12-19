# Initial setup

This directory contains instructions and resources necessary to perform initial setup of the Neovim environment.

## Required packages

The following packages are required to make the environment function as intended.

- A terminal or terminal emulator. For MacOS, kitty works nicely.
- Python and pip.
- Node, required for some packages.
- Ripgrep, required for fuzzy-finding
- Neovim, obviously.

## Setup

After the required packages are installed, clone the repository into `~/.config/nvim`.
Run `bash ~/.config/nvim/initial-setup/install-node.sh`.
Then, from the python environment you want to use, run `pip install -r ~/.config/nvim/initial-setup/pip-requirements.txt` to install the necessary python packages.

Open Neovim and run `:PackerSync` to install and set up Neovim plugins.

