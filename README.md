# Personal vimrc

## Step
1. installation & following step by step => https://github.com/scrooloose/nerdtree
    
2. Move .vimrc ``into ~/.vimrc``
    $ vim ~/.vimrc

3. paste code below:

    ```php
    execute pathogen#infect()
    syntax on
    colorscheme blackboard

    filetype plugin indent on
    autocmd StdinReadPre * let s:std_in=1
    autocmd VimEnter * if argc() == 0 && !exists("s:std_in") | NERDTree | endif
    set number
    set tabstop=4
    set shiftwidth=4
    set expandtab
    ```
4. done. happy coding~ !!!
