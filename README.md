Installation Instructions
=========================

VIM
---

 1. Backup your existing .vimrc file and .vim directory::

    mv ~/.vimrc ~/old.vimrc
    mv ~/.vim ~/old.vim

 1. Link to vim dotfiles::

    ln -s ~/dotfiles/rc.vim ~/.vimrc
    ln -s ~/dotfiles/vim ~/.vim

1. Install rope Python module::

    pip install rope

1. Fetch vim-addons-manager submodule

    cd ~/dotfiles
    git submodule init

