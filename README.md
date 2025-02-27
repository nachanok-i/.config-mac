# My Configuration Files

This repository contains my configuration files for various applications.

## Structure

- **alacritty/**: Contains the Alacritty terminal emulator configuration.
- **nvim/**: Contains the Neovim configuration.
  - `init.vim`: Main Neovim configuration file.
  - `lua/`: Directory for Lua plugin configurations.
- **tmux/**: Contains the Tmux terminal multiplexer configuration.
- **zsh/**: Contains the Zsh shell configuration.

## Usage

1. Clone this repository to your home directory.
2. Remove .git folder and rename this folder.
   ```sh
   rm -rf ./config/.git
   mv .config-mac .config
   ```
3. Symlink the `.zshrc` file to your home directory:
   ```sh
   ln -s ~/.config/zsh/zshrc ~/.zshrc
   ```
