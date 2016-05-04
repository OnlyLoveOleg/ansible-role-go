go
=========

Role to install (download) Go on remote.


Role Variables
--------------

defaults/main.yml:

```
---
go_inst:
 src_file_url: "https://storage.googleapis.com/golang/go1.6.2.linux-amd64.tar.gz"
 src_file_sha256: e40c36ae71756198478624ed1bb4ce17597b3c19d243f3f0899bb5740d56212a
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

tal@pjili.org
