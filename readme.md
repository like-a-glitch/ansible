# Prerequisites

- set required variables in [vars.yml](./vars.yml)

# Run

```
sudo ansible-playbook playbook.yml
```

*or if not set in [vars.yml](./vars.yml):*

```
sudo ansible-playbook playbook.yml -e "remoteUserName=INSERT_USER_NAME"
```