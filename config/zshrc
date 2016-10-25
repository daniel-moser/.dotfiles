
# Lines configured by zsh-newuser-install
HISTFILE=~/.histfile
HISTSIZE=1000
SAVEHIST=1000
setopt beep extendedglob
setopt autocd

# End of lines configured by zsh-newuser-install

complete -cf sudo

autoload -Uz promptinit
promptinit
prompt adam2

# User configuration
# ---
export EDITOR="emacs"
export TERM="screen-256color"

#export PATH="$PATH:$HOME/.gem/ruby/2.2.0/bin"

# Aliases
alias ls='ls -l --color=always'
alias la='ls -al'
alias cl='clear'

alias eamcs='emacs'
alias emcas='emacs'
alias emasc='emacs'
alias eamcas='emacs'

alias mkdircd='mkdir $0; cd $1'
# screenfetch
#cl;
if
    [ -f /usr/bin/screenfetch ]; then  neofetch;
fi

