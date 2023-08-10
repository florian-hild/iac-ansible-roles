# Ansible Role: setup_bash_lib
---

Clone GitHub repo bash-lib to /usr/local/bin

## Role Variables

Available variables are listed below, along with their default values (see `defaults/main.yml`):

Default:
 ```yaml
github_api_token: null
#bash_lib_repo: "https://{{ github_api_token }}@github.com/florian-hild/bash-lib.git"
bash_lib_repo: "https://github.com/florian-hild/bash-lib.git"
bash_lib_dst: /usr/local/bin
bash_lib_repo_branch: main
 ```

