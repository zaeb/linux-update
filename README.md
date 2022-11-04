# Linux Update

## Check updates

```bash
ansible-playbook --ask-become-pass -i inventory/demo.yaml linux-update.yaml
```

## Update packages

```bash
ansible-playbook --ask-become-pass -i inventory/demo.yaml linux-update.yaml --extra-vars "update_allowed=true"
```
