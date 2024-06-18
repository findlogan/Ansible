# Ansible

I'm working on learning Ansible, so I have also decided to open-source my playbooks, etc. for your projects as well.

MIT license, use it for your own projects, etc. If you feel compelled to give me money, I have a sponsorship page on GitHub where you can buy me a coffee to continue developing these in my afternoons. Otherwise, it's free. Enjoy.

If you are new to ansible, you can find a installation guide [here](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#control-node-requirements)

## Documentation

Included below will be a documented list of what all is currently included inside of this repository. It may not be the most optimal way to do things, but it should work in Debian based environments currently. As time goes on, I will eventually support more environments. Your mileage may vary.

> Note: Currently all of these scripts will run on all hosts in the inventory reguardless of grouping.

`/playbooks/harden-server.yml` - This playbook will disable password login, copy a basic config for SSH, remove some defaults, and only allow SSH key authentication. This assumes you are using your ansible user's SSH keys.
