# aleo-ansible

Create file hosts

```
[miners]
1.1.1.1 miner.aleo.orh
```

###Adding SSH Keys to a Virtual Machine

To continue, you need to add your keys to the authorized_keys of root on the virtual machine. This is not required (Ansible can use sudo and password authentication), but it will be much easier.

Ansible is perfect for this task, so we'll use it. However, I will not explain anything yet. Just trust me.

ansible-playbook -c hosts [-i names of из hosts, if required is indi] setup.yml 