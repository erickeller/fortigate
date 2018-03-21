# Fortigate Playground

## Prerequisites

Latest ansible version >= 2.4

```
sudo pip3 install ansible
```

install python modules

```
apt update && apt install -y python-netaddr python-pyfg
```

## Getting started

```
ansible-playbook ansible/playground.yml -c local -i localhost, -e "password=$(cat ./fortinet-secret)"
```

## References

```
sudo -H pip3 install fortiosapi
ansible-galaxy install osrour.fortios
```

https://github.com/osrour/ansible-fortios
