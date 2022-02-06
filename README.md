# My Linux Setup

## NVIM IDE Setup

Inspired by: https://www.youtube.com/watch?v=FW2X1CXrU1w
Check out this absolute legend's blog for extended information about setting this up: https://blog.inkdrop.app/how-to-set-up-neovim-0-5-modern-plugins-lsp-treesitter-etc-542c3d9c9887

Getting started:

1. `Download Zip` or `git clone https://github.com/DenoSaurabh/setup.git`
2. Extract the files if zipped, and paste it in `$HOME/.config`
3. Install required dependencies using, `brew install --HEAD tree-sitter luajit neovim`:
  INSTALLING BREW, skip this if you have already installed:
   - `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
   - Updating brew path: `eval $(/home/linuxbrew/.linuxbrew/bin/brew shellenv)` 
   - `echo "eval \$($(brew --prefix)/bin/brew shellenv)" >> ~/.zshrc` - note here I am ending with `.zshrc`, change it to whatever you use 
4. `cd .config/nvim`
5. `vim init.vim`, I am hoping from now you alreay know a bit of vim
6. `:PlugInstall` -  This will installing all the necessary plugins, like intellisense, autocomplete, file explorer.
7. `:q` to quit VIM
8. now open any of your code files like `nvim main.ts` and try out this setup
9. DONE!

Happy coding!

