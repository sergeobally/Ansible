# play-ansible
## playground
docs.ansible.com
- Test ping all hosts
```sh
ansible -i hosts all -m ping
ansible -i hosts all -m setup
ansible -i hosts all -m copy -a "dest=/home/centos/toto.txt content='Mon premier fichier ansible a distance'"
```