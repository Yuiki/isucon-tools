# isucon-tools

## List

- Add Netdata (docker)
- Add commands
  - pt-query-digest
  - alp
  - nvm
  - unzip
  - dstat
- Create ~/.ssh/id_rsa & .pub
- Set git config user.name & email

## Usage

```sh
# prepare connecting via ssh to myself
cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys

# install ansible collections
ansible-galaxy collection install community.crypto community.general

# install tools
ansible-playbook -i <IP Address>, common.yml
# eg: ansible-playbook -i localhost, common.yml
```
