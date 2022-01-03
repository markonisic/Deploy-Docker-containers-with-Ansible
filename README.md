# Docker deployments with Ansible

This repo contains various Ansible playbooks to deploy Docker containers automatically(services that have a Docker container, such as web servers and etc) on Linux servers(Servers can be Virtual machines, Cloud servers or bare metal machines).

## Requirements for deployment to be succesfull

- Python
- Python Docker module(installed by pip3)
- pip3 can be installed with python3-pip package

## Docker Containers added so far

- [Install Docker on a remote host](https://github.com/markonisic/Deploy-Docker-containers-with-Ansible/tree/main/install-docker-with-ansible)
Simple playbook that downloads and runs the official automated Docker install script in order to install Docker on a remote host.
Official Docker install script can be used to install Docker on various Linux distros(Ubuntu, Debian, CentOS/Red Hat, OpenSUSE, Fedora)
- [Install Nextcloud Docker container](https://github.com/markonisic/Deploy-Docker-containers-with-Ansible/tree/main/install-nextcloud-with-ansible)
Playbook to deploy Nextcloud as a Docker container with a MariaDB Docker container. 
- [Install Wordpress Docker container](https://github.com/markonisic/Deploy-Docker-containers-with-Ansible/tree/main/install-wordpress-with-ansible)
Playbook to deploy Wordpress as a Docker container with a MariaDB Docker container.
