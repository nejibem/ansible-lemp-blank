# ansible-lemp-blank
Ansible repo to create a blank Lemp VM with Vagrant

## Setup

### 1. Edit Config
```vim _ansible/vars/dev.yml```

### 2. Edit /etc/hosts file on host system
Setup host for default ip address
```192.168.56.140 test.local```

### 3. Start VM
```vagrant up```

### 4. SSH into VM
```vagrant ssh```