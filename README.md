# Open Air Interface EPC Playbook

This Playbook will automatically compile [OAI EPC](https://gitlab.eurecom.fr/oai/openair-cn) on target machine.

## Usage

```shell
export HOST_IP=192.168.1.100
export ANSIBLE_USER=ubuntu
export ANSIBLE_PASSWORD=ubuntu
ansible-playbook playbook.yml -i "$HOST_IP," -e "ansible_user=$ANSIBLE_USER ansible_ssh_pass=$ANSIBLE_PASSWORD ansible_sudo_pass=$ANSIBLE_PASSWORD"
```

## Maintainers

Project developed by [Yih-Jye Chiu (Jason Chiu)](https://github.com/jason1122g).  
Maintained by [Wei-Yu Chen (aweimeow)](https://github.com/aweimeow).

Initialized by [National Chiao Tung University, Department of Computer Science](https://www.cs.nctu.edu.tw/cswebsite/).

## LICENSE

Apache License 2.0
