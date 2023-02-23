Configure the variable in `playbooks/variables.yaml` and configure the `hosts.yaml`

Test pinging the nodes
```
ansible all -m ping
```

Run the playbook
```
ansible-playbook playbooks/containeerd-1.26.1.yaml
```

List tags
```
ansible-playbook playbooks/containeerd-1.26.1.yaml --list-tags
```

Use tags
```
ansible-playbook playbooks/containeerd-1.26.1.yaml --tags <tags_name>
```
