## Vagrant learning

Install vagrant from site:
```
https://www.vagrantup.com/downloads.html
```

### Download and install Vagrant
```
wget https://releases.hashicorp.com/vagrant/2.1.1/vagrant_2.1.1_x86_64.rpm
rpm -ivh vagrant_2.1.1_x86_64.rpm
```
### Initially it should be installed Virtualbox
```
cd /etc/yum.repos.d
wget http://download.virtualbox.org/virtualbox/rpm/rhel/virtualbox.repo
yum --enablerepo=epel install dkms
yum groupinstall "Development Tools"
yum install kernel-devel
yum install VirtualBox-5.1
Source: https://wiki.centos.org/HowTos/Virtualization/VirtualBox
```
### Commands
Check version:
```
vagrant version
```
Check status:
```
vagrant status
```
Check boxes:
```
vagrant box list
```
Add box:
```
vagrant box add geerlingguy/centos7
```


