# Ansible Commands

Basic ansible snippets for deploying Django Application

For Web:
```
ansible-playbook -i hosts web/web.yml
```

For DB:
```
ansible-playbook -i hosts db/db.yml
```

For App:
```
ansible-playbook -i hosts app/app.yml
```
