ansible-node
============
[![Build Status](https://travis-ci.org/mwilliammyers/ansible-node.svg)](https://travis-ci.org/mwilliammyers/ansible-node)

Install & configure [nodejs] & [npm].

Installation
------------

```
ansible-galaxy install mwilliammyers.node
```

Requirements
------------

A system package manager.

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
    - hosts: all
      roles:
         - role: mwilliammyers.node
```

License
-------

GPLv3

Author Information
------------------

[@mwilliammyers]

[@mwilliammyers]: https://github.com/mwilliammyers
[aura]: https://github.com/aurapm/aura
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mwilliammyers/dotstrap
[fasd]: https://github.com/clvv/fasd
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[pacaur]: https://github.com/rmarquis/pacaur
[pacman]: https://www.archlinux.org/pacman/
[variables]: vars/
[yaourt]: https://github.com/archlinuxfr/yaourt
[zsh]: http://zsh.sourceforge.net
[nodejs]: http://nodejs.org/
[npm]: https://www.npmjs.com/
