# rancher-install-stack-ansible-role

Install or upgrade rancher stacks in an existing rancher environment.

Mandatory Variables
-------------------
```
rancher_api_key: "mykey"
rancher_api_secret: "mysecret"
rancher_project_name: "default"
rancher_project_id: 1234
```

Role Variables
--------------

```
stack_name: "default"
rancher_cli_stack_opts: "--pull --upgrade"
rancher_master_url: "http://localhost:8080"
```
License
-------

Apache License 2
