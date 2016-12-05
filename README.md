# Ansible Dymanic Vagrant Inventory

Start VMs:

```
$ vagrant up
```

Test ping:

```
$ ansible all -m ping -o -vv
debian-test-1 | SUCCESS => {"changed": false, "ping": "pong"}
debian-test-2 | SUCCESS => {"changed": false, "ping": "pong"}
```

The Ansible Dynamic Vagrant Inventory script is here: [hosts/vagrant.py](hosts/vagrant.py)

To delete the cache:

```
$ rm hosts/.cache -rf
```
