# ansible-plays-elementary

Ansible playbook to install personal tools required for my workspace, and setup my development environment on Elementary OS.

The playbook has been broken up into four individual role groups:

#### Common

* Install nano (terminal text editor).
* Install curl (cli http tool).
* Install httpie (cli http tool).
* Install gedit (gui text editor).
* Install vlc media player (media management).
* Install gyazo screen capture.
* Install zsh shell.
* Install libreoffice suite.
* Install redshift.
* Install snapd.
* Install elinks.
* Install i3 environment (with i3blocks).
* Install tmux.
* Install nitrogen.
* Install elementary tweaks.
* Install fileroller archive manager.
* Install nautilus file explorer.
* Install xfce4 settings manager.

#### Development

* Install aws-cli.
* Install docker.
* Install docker-compose.
* Install vscode.
* Install atom.
* Install pylint.
* Install pip2/pip3.
* Install python development tools.
* Install httpie.
* Install node.js stable (using n tool).
* Install coffeescript.
* Install webpack.
* Install ruby.
* Install travis-cli.
* Install datagrip.
* Install insomnia rest tool.

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
Copyright (c) 2018 John Nolette Licensed under the MIT license.
