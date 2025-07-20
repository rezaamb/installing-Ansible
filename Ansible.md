Installing Ansible on Ubuntu (master node)

```bash
apt update
pt install software-properties-common
add-apt-repository --yes --update ppa:ansible/ansible
apt install ansible
```
for Test :

```bash
ansible -m ping 127.0.0.1
```
