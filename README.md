# .dotfiles
My personal config files for various command line utilities.

# Installing
1. Clone the repo and move all of its files into your home directory `git clone https://github.com/jake-bickle/.dotfiles.git` then `cp .dotfiles/* ~/`
1. Install [Vundle](https://github.com/VundleVim/Vundle.vim) to utilize the various vim plugins with `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`
1. Open vim, enter :PluginInstall and wait for all of the plugins to install.

# Notable VIM Keybinds
* `jj` or `JJ` to exit insert mode
* `m` scrolls page down, `,` scrolls page up
* `-n` toggles [nerdtree](https://github.com/scrooloose/nerdtree)
* `gt` goes forward tabs, while `tg` goes back 
* `_` to go to beginning of line, `+` to go to end of line
* `-ev` opens up .vimrc for quickly creating new keybinds. Save them, then `-sv' to update your vim session with the new keybinds.
* `ctrl + s` to save (for anyone hoping over from other editors out there!)