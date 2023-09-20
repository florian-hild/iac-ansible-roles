# Ansible Role: setup_basic_settings
## Role Description:
Things I like to set up on my servers.

Tasks:
  - Setup system locales
  - Setup timezone
  - Setup nameserver config in resolv.conf
  - Install basic packages

Supported OS:
  - Debian / Ubuntu
  - RHEL based systems

## Role Variables
Available variables are listed in the defaults file (see `defaults/main.yml`).

Ansible facts used:
   - ansible_os_family
   - ansible_distribution
   - ansible_domain

## License
See repository license file.
