# ansible-plays-workspace

Ansible plays for bootstrapping my personal workspace on Elementary OS.

This playbook has been broken up into four individual role groups:

#### Common

* Install nano (terminal text editor).
* Install curl (cli http tool).
* Install httpie (cli http tool).
* Install gedit (gui text editor).
* Install vlc media player (media management).
* Install gyazo screen capture.
* Install zsh shell.
* Install bash/zsh completion.
* Install libreoffice suite.
* Install redshift.
* Install snapd.
* Install elinks.
* Install i3 environment (with i3blocks).
* Install tmux.
* Install nitrogen.
* Install fileroller archive manager.
* Install nautilus file explorer.
* Install xfce4 settings manager.
* Install xfce4 terminal.
* Install xterm.
* Install xbacklight.
* Install jq.

#### Development

* Install cmake.
* Install gcc7.
* Install aws-cli.
* Install docker.
* Install docker-compose.
* Install vscode.
* Install pylint.
* Install pip2/pip3.
* Install Python 3.6/3.7.
* Install python development tools.
* Install httpie.
* Install node.js stable (using n tool).
* Install coffeescript.
* Install webpack.
* Install ruby.
* Install travis-cli.
* Install datagrip.
* Install insomnia rest tool.
* Install vim and gvim.
* Install mycli and pgcli.
* Install php7 with composer/laravel.

#### Aesthetics

* Install Oranchelo icon theme.
* Install numix gtk theme.

#### Social

* Install skype client.
* Install hipchat desktop client.
* Install slack desktop client.
* Install gitter desktop client.
* Install teamviewer.

## Variables

Playbook inventory variables can be found in `group_vars/all.yml`.

    git_ssh_key_user: Label of ssh key generated for git.

## Use

```sh
git clone https://github.com/neetjn/ansible-plays-elementary.git

cd ansible-plays-elementary

ansible-playbook playbook.yml
```

---

Copyright (c) 2019 John Nolette Licensed under the MIT license.
