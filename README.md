# ansible-ultrasnips

Project init
```
git clone https://github.com/htesgaard/ansible-ultrasnips.git
ansible-galaxy init ultrasnips
```

Ansible notes
```
ansible localhost -m setup |grep ansible_system
```

Playbook
```
---
- hosts: localhost
  remote_user: <username>
  roles:
    - ultrasnips
```



Resources
https://github.com/cmprescott/ansible-role-common/blob/master/tasks/main.yml