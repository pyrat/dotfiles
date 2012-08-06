# Dotfiles

Forked from Holman's excellent starter repo.

Ripping most stuff out and aiming for a shell environment which can not only be installed on development machines but also servers. This allows for a nice fast commandline
setup to be configured across many servers.

Designed to be run with ZSH and OH-MY-ZSH. This differs from holman's attempt which has a custom ZSH config.


## Install

    git clone git@github.com:pyrat/dotfiles.git
    script/bootstrap

## TODO

Need to add some install code which alters the .zshrc to load another rc file?

    # source every .zsh file in .dotfiles
    for config_file (~/.dotfiles/**/*.zsh) source $config_file
    
    
    # load every completion after autocomplete loads
    for config_file (~/.dotfiles/**/completion.sh) source $config_file
    