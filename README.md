
*Installation*

    mkdir ~/lists

    cp bin/* ~/bin/

    cp .listrc ~/

    find .vim -type f -ok cp {} ~/{} \;

    cat <<"VIMRC" >>~/.vimrc
    au BufNewFile,BufRead,BufReadPost set ft=lists syntax=lists
    VIMRC



