# ansible_project_k3s
Per eseguirlo:
```bash
ansible-playbook --ask-become-pass playbook/k3s_install.yaml -i inventory
```
```bash
ansible-playbook --ask-become-pass playbook/dashboard_deploy.yaml -i inventory
```
