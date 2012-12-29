In this repo I store some common terminal configuration files which I want to share between my private and company computer. To make it work, checkout repo into ~/bin.
In ~/.bash_profile add:

    if [ -f ~/.bashrc ];
    then
        source ~/.bashrc
    fi

In ~/.bashrc add:

    . ~/bin/dotfiles/bashrc
