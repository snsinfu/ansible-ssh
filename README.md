# ansible-ssh scripts

## ansible-ssh-config

Generates ssh\_config from Ansible inventory.

```
$ ansible-ssh-config
Host host1.example.com
  HostName 10.10.10.1
  Port 22
  User deploy
  IdentityFile ~/.ssh/id_rsa
  IdentitiesOnly yes
  PasswordAuthentication no
Host host2.example.com
  HostName 10.10.10.2
  Port 22
  User deploy
  IdentityFile ~/.ssh/id_rsa
  IdentitiesOnly yes
  PasswordAuthentication no
```
