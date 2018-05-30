# GMPVPC-3000 deployment repo

## Vagrant commands

- Create your test VM
```sh
        vagrant up
```

- Run ansible playbook on your test VM
```sh
        vagrant provision
```
- Halt your test VM
```sh
        vagrant halt
```
- Destroy your test VM
```sh
        vagrant destroy
```
## Ansible commands

- Run playbook on Production Environment
```sh
        ansible-playbook gmpvpc.yml -i inventories/raspberry/
```