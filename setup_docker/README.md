# Ansible Role: setup_docker
Setup Docker on server

Tasks:
  - Setup timezone
  - Install Docker from official repo
  - Setup Docker daemon.json
  - Install docker-compose binary from GitHub

Supported OS:
  - Debian / Ubuntu

## Role Variables
Available variables are listed in the defaults file (see `defaults/main.yml`).

Ansible facts used:
   - ansible_distribution
   - ansible_system
   - ansible_architecture

## License
See repository license file.
