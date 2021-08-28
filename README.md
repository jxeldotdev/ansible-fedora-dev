## ansible-fedora-dev

Ansible role to install a basic development environment on a fresh installation of Fedora 34 on my personal laptop.

The role uses two variables:

|Variable Name|Description|
--------------| ---------- 
|personal_user| Name of user on remote host. 
|hostname | Hostname that will be set on remote host.


It installs the following, among other things:
* Git
* AWS CLI
* Terraform
* Packer
* Ansible
* ZSH
* Podman-Compose
* Visual Studio Code

Copy your SSH key to the host, create a inventory file and you're good to go. 
