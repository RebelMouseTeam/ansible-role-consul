# Consul Client/Server

Installing role:
```
ansible-galaxy install --force RebelMouseTeam.consul
```

Using role:
```
---
- hosts: localhost
  connection: local
  gather_facts: yes
  become: yes
  roles:
    - { role: RebelMouseTeam.consul, consul_mode: 'client' }
```
