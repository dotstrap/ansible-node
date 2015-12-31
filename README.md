ansible-npm
===========
[![Build Status](https://travis-ci.org/mkwmms/ansible-npm.svg)](https://travis-ci.org/mkwmms/ansible-npm)

Install & configure npm.

Requirements
------------

A package manager.

Role Variables
--------------

See [default variables].

Dependencies
------------

None.

Example Playbook
----------------

Using all the [default variables]:

```
    - hosts: servers
      roles:
         - role: mkwmms.npm
```

License
-------

GPLv3

Author Information
------------------

[@mkwmms]

[@mkwmms]: https://github.com/mkwmms
[aura]: https://github.com/aurapm/aura
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mkwmms/dotstrap
[fasd]: https://github.com/clvv/fasd
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[pacaur]: https://github.com/rmarquis/pacaur
[pacman]: https://www.archlinux.org/pacman/
[variables]: vars/
[yaourt]: https://github.com/archlinuxfr/yaourt
[zsh]: http://zsh.sourceforge.net
