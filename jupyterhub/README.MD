# JupyterHub Ansible Playbook

Deploy

```bash
ansible-playbook main.yml -K
```

In some cases it is required to enable the jupyterhub port in the firewall.

```bash
sudo ufw allow 8000/tcp
```
