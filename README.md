go
=========

Role to install (download) Go on remote.


Role Variables
--------------

defaults/main.yml:

```
go_inst:
 src_file_url: https://dl.google.com/go/go1.12.1.linux-amd64.tar.gz
 src_file_sha256: 2a3fdabf665496a0db5f41ec6af7a9b15a49fbe71a85a50ca38b1f13a103aeec
```


Example Playbook
----------------

```
- hosts: servers
  roles:
   - go
```


Author Information
------------------

Tal Lannder

tal@tal.fyi
