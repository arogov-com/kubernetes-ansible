# kubernetes-ansible
Playbook that installs a Kubernetes cluster

## Prerequisites
* Ansible and Python3 installed on the local machine
* Archlinux or Alpine libux distribution on the cluster members
* Python3 and sudo installed on the cluster members
* Local machine's SSH-key exported onto cluster members

## Prepare config files
Change number of masters and nodes machines in the inventory/sample/hosts file

## Run playbook
ansible-playbook -i inventory/sample/hosts kubernetes.yml
