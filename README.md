brewery
=======

This script helps a user to install Hombrew packages


Requirement
-----------

* OS X Yosemite


Usage
-----

### Create Brewfile

Examples:

    # tmux
    install tmux
    install reattach-to-user-namespace

    # Zsh
    install zsh --disable-etcdir
    install zsh-completions

    # tap
    tap peco/peco
    tap motemen/ghq

    # Cask
    cask dropbox
    cask virtualbox
    cask vagrant
    cask chefdk

### Execute brewery

    $ ls
    Brewfile
    $ brewery


Install
-------

### Clone the repository

    $ curl -L -o /usr/local/bin/brewery https://raw.githubusercontent.com/ganta/brewery/master/brewery
    $ chmod +x /usr/local/bin/brewery


Licence
-------

[MIT](https://github.com/ganta/brewery/blob/master/LICENSE)


Author
------

[Hideki IGARASHI](https://github.com/ganta)
