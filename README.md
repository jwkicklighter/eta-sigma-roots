# Eta Sigma Roots

This project includes a theme based on Dazzling, a wordpress distribution based on Bedrock (for development), and a deployment/environment toolset based on Trellis.

The theme is located at `site/web/app/themes/Eta-Sigma-Theme`.

## Requirements

- PHP >= 5.4.x
- Ansible >= 1.9.2 - [Install](http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-pip) (DO NOT INSTALL ON WINDOWS)
- Virtualbox >= 4.3.10 - [Install](https://www.virtualbox.org/wiki/Downloads)
- Vagrant >= 1.5.4 - [Install](http://www.vagrantup.com/downloads.html)
- vagrant-bindfs >= 0.3.1 - [Install](https://github.com/gael-ian/vagrant-bindfs#installation)
- vagrant-hostsupdater - [Install](https://github.com/cogitatio/vagrant-hostsupdater#installation)

## Installation

1. Clone this project.
2. Run `ansible-galaxy install -r requirements.yml -p vendor/roles` inside `/trellis`. (UNLESS ON WINDOWS)

## Development
1. Run `vagrant up` inside `/trellis/` to start Virtualbox.
2. Run `vagrant suspend` or `vagrant halt` inside `/trellis` to stop or sleep Virtualbox.
