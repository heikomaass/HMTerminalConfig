In this repo I store some common terminal configuration files which I want to share between my private and company computer.
Checkout repo into ~/bin.
In ~/.bash_profile add:
<code>
f [ -f ~/.bashrc ];
then
    source ~/.bashrc
fi
</code>

In ~/.bashrc add:
<code>
. ~/bin/dotfiles/bashrc
</code>
