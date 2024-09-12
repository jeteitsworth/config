# Config 2024

## Vim
Vim is in its own repo on the vim branch.

## ZSH
1. Install OMZSH `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
2. Copy zshrc to home directory `cp zshrc $HOME/.zshrc`
3. Install autosuggestions `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`

## Misc
1. Install homebrew (Mac, Debian, and Ubuntu-derivitives only) `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
2. Install `fd ripgrep bat lsd fzf tldr cheat lazygit python gomono-nerd-font gh`
3. Install pipx `brew install pipx` then run `pipx ensurepath` and `pipx ensurepath --global`
4. Install jedi language server with pip (preferably pipx)  

## Todo
- [ ] Migrate to vim-lsp
- [ ] Remove nvim config and bring vim back to main branch
- [ ] Set up alacritty with config
- [ ] Set up GNU Stow
- [ ] Check on getting treesitter in vim
- [ ] Automate with ansible or a script
