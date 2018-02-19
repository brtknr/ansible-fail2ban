# ansible-fail2ban


After cloning this repository, ensure you have a VM running in the background (created using Vagrant). 
```
vagrant up
```

Check vagrant ssh-config and ensure that it matches the credentials listed inside host_vars/



```
virtualenv venv
pip install -r requirements.txt
source venv/bin/activate
ansible-playbook -i hosts.yml -vv playbook.yml
```