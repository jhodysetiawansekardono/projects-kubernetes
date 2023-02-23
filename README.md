Configure the variable in `playbooks/variables.yaml` and configure the `hosts.yaml`

Test pinging the nodes
```
ansible all -m ping
```

Run the playbook
```
ansible-playbook playbooks/docker-1.20.12.yaml
```

List tags
```
ansible-playbook playbooks/docker-1.20.12.yaml --list-tags
```

Use tags
```
ansible-playbook playbooks/docker-1.20.12.yaml --tags <tags_name>
```
