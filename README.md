# Config 2024

## Vim
Vim is in its own repo on the vim branch.

## ZSH
1. Install OMZSH `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
2. Copy zshrc to home directory `cp zshrc $HOME/.zshrc`
3. Install autocomplete 

## Misc
1. Install homebrew `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
2. Install `fd ripgrep bat lsd fzf tldr cheat lazygit python3 gomono-nerd-font`
3. Install jedi-language-server from pip `pip install -U jedi-language-server`

## TODO
* Add gopls language server for upcoming class
* Upgrade to vim-lsp
* Add gdscript language support for vim-lsp
* Remove nvim setup and make vim the main branch again. I'm going to stick with vim.
* Find out if there is a way to bring treesitter to vim
* Set up alacritty config
* Set up GNU stow
