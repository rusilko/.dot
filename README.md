.dotfiles aka config files
==========================

These are config files to set up a system the way I like it.

Installation
------------

```bash
git clone git@github.com:rusilko/.dot.git ~/.dot
ln -s ~/.dot/zsh ~/.zsh
ln -s ~/.dot/zsh/zshrc ~/.zshrc
ln -s ~/.dot/gitignore ~/.gitignore
ln -s ~/.dot/tmux.conf ~/.tmux.conf
ln -s ~/.dot/vim/vimrc ~/.vimrc
ln -s ~/.dot/vim ~/.vim
ln -s ~/.dot/dircolors.256dark ~/.dircolors
git config --global core.excludesfile ~/.gitignore_global
```

Environment
-----------

I am running on Mac OS X Terminal with zsh shell. If you like to switch
from old bash, use the following command.

```bash
chsh -s /bin/zsh
```
