### This is neovim config is inspired by [ThePrimeagen](https://github.com/ThePrimeagen) along with some custom configs.

#### Pre-requisites `Node >= 14`, `ripgrep`, `packer` and `nvim > 0.7` .

### Steps to configure neovim

- Clone this repo `git clone https://github.com/AbhishekGMV/.dotfiles.git`
- Move all the files to `~/.config/nvim`
- Source the `packer.lua` file in `lua/noobmaster69` folder in normal mode using `:so` command. (Packer has to be intalled before this step) 
- Run `PackerSync` <br>
(You might see some errors related to Tresitter and Mason, which should eventually be solved as they download parsers when it's required)
