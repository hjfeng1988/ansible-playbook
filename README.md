# ansible-playbook

### 
```
系统初始化首次需要密码
ansible-playbook init.yml -k
ansible-playbook init.yml

ansible-playbook playbook/useradd.yml -e "user=super password=superpass sudo=yes"
ansible-playbook playbook/useradd.yml -e "user=super password=superpass sudo=no"

ansible-playbook install_sftp.yml -e "user=yourname password=yourpass"
```
