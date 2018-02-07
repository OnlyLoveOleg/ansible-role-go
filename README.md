go
=========

Role to install (download) Go on remote.


Role Variables
--------------

defaults/main.yml:

```
go_inst:
 src_file_url: https://dl.google.com/go/go1.9.3.linux-amd64.tar.gz
 src_file_sha256: a4da5f4c07dfda8194c4621611aeb7ceaab98af0b38bfb29e1be2ebb04c3556c
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
