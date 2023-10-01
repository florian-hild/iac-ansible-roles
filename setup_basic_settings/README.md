# Ansible Role: setup_basic_settings
## Role Description:
Things I like to set up on my servers.

Tasks:
  - Setup hostname
  - Setup system locales
  - Setup timezone
  - Setup hosts
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
   - ansible_virtualization_type
   - ansible_hostname
   - ansible_nodename
   - ansible_default_ipv4.address

## License
See repository license file.
