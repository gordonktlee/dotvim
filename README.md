# dotvim

### Clone Repo
    git clone https://github.com/gordonktlee/dotvim.git ~/.vim

### Create Symbolic Links
    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

### Pull & Update vim bundles
    git submodule init
    git submodule update
or 
    git submodule update --init.
    
### Install plugins as submodules
    cd ~/.vim
    mkdir ~/.vim/bundle
    git submodule add http://github.com/tpope/vim-fugitive.git bundle/fugitive
    git add .
    git commit -m "Install Fugitive.vim bundle as a submodule."
