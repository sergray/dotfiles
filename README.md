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

1. Install needed Python modules::

    pip install rope pyflakes pep8

1. Fetch vim-addons-manager submodule

    cd ~/dotfiles
    git submodule init

