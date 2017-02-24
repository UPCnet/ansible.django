
### Before running

Copy `django_deploy_var.yaml.in` into `django_deploy_var.yaml` and fill with sensible values

### Run with
```
<ansible_path>/bin/ansible-playbook django_deploy.yaml --extra-vars="hosts=<hostname>"
```
