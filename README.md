
# deployment of WordPress using Ansible  


# Usage environment

PHP8.3  
Nginx(latest)  
MySQL8

URL：http://dev.menta.me 

# Checking the connection

```
ansible -i ./hosts myhosts -m ping
```

# run

```
ansible-playbook playbook.yml
```

