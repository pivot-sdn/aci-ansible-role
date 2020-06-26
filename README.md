# aci-ansible-role
Cisco ACI Role for Ansible

This is based off an Ansible Role @ https://github.com/datacenter/ansible-role-aci-model.git

All the tasks have been updated to use native ACI modules instead of raw REST.
I also re-structured the inventory file a bit and made a small modification to the JINJA filter (it wouldn't accept a list as a value)
