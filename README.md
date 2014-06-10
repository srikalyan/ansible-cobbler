# Ansible Cobbler

A basic Ansible playbook to install Cobbler on Ubuntu.

## Usage

First, update the **ansible_hosts** file to include the nodes to be provisioned. A single entry has been provided by default for deployment on a Vagrant instance. You will just need to update the IP address corresponding to your Vagrant instance.

Once the nodes have been added to the hosts file, run the playbook to install Cobbler.

    $ ansible-playbook deploy.yml
