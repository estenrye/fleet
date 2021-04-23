# fleet

## Bootstrapping Secrets

```bash
pip3 install -r ansible/requirements.txt
ansible-galaxy install -r ansible/requirements.yml
ansible-playbook -i ansible/inventories/dev.yml ansible/deploy-secrets.yml
```