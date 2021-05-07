# fleet

## Bootstrapping Secrets

```bash
pip3 install -r ansible/requirements.txt
ansible-galaxy install -r ansible/requirements.yml
ansible-playbook -i ansible/inventories/dev.yml ansible/deploy-secrets.yml
```

Upload the following files into the JumpCloud SAML SSO application

- ansible/secrets/saml_authentication_idp.key
- ansible/secrets/saml_authentication_idp.crt

Download JumpCloud Metadata to

- ansible/secrets/saml_authentication_idp_metadata.xml