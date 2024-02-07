# How to Install
Configure the `requirements.yml` file.
```
- name: hashicorp
  src: https://github.com/nilsonvieira/ansible-role-hashicorp
  version: main
```
In the Roles include:
```
  roles:
    - hashicorp
```
Execute the command to install role.

```bash
ansible-galaxy role install -r requirements.yml