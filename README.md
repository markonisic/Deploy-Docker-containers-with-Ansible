# Docker deployments with Ansible

This repo contains various Ansible playbooks to deploy Docker containers automatically(services that have a Docker container, such as web servers and etc) on Linux servers(Servers can be Virtual machines, Cloud servers or bare metal machines).

## Requirements for deployment to be succesfull

- Python
- Python Docker module(installed by pip3)
- pip3 can be installed with python3-pip package

## Docker Containers added so far

- [Install Docker on a remote host](https://github.com/markonisic/Deploy-Docker-containers-with-Ansible/tree/main/install-docker-with-ansible)
Simple playbook that downloads and runs the official automated Docker install script in order to install Docker on a remote host.
- [Install Nextcloud Docker container](https://github.com/markonisic/Deploy-Docker-containers-with-Ansible/tree/main/install-nextcloud-with-ansible)
