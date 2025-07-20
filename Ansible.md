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
host file :

```bash
vim /etc/ansible/hosts
```
for installing with ```root``` user :

```bash
ansible -m apt -a 'name=apache2 state=present' 192.168.1.1 --user reza -b -K
```

