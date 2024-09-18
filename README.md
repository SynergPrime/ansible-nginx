# Install venv (once)

```bash
sudo apt install python3-venv
```

# Create virtual environment (once)

```bash
python3 -m venv env
```

# Activate virtual environment

```bash
. ./env/bin/activate
```

```bash
pip3 install -U  ansible
```

# Run playbooks

```bash
ansible-playbook -i inventory/server.yml nginx.yml 
```


