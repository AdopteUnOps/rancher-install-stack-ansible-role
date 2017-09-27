# rancher-install-stack-ansible-role

Install or upgrade rancher stacks in an existing rancher environment.

This role assume that you have an apikey file in {{ inventory_dir }}/group_vars/{{ rancher_project_name }}/apikey.yml containing the following variables :
* rancher_api_key_project_token
* rancher_api_key_project_secret
* rancher_project_id

Role Variables
--------------

```
rancher_cli_stack_opts: "--pull --upgrade"
rancher_master_url: "http://localhost:8080"
rancher_project_name: "default"
```
License
-------

Apache License 2
