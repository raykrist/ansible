## Ansible

Small set of playbooks and roles to manage libvirt controller nodes and
possible other tasks.

### Install

``` bash
virtualenv -p /usr/bin/python3 .
source bin/activate
pip install pip --upgrade
pip install -r requirements.txt
ansible-galaxy collection install requirements.yaml
```
