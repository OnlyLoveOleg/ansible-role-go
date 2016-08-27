go
=========

Role to install (download) Go on remote.


Role Variables
--------------

defaults/main.yml:

```
go_inst:
 src_file_url: https://storage.googleapis.com/golang/go1.7.linux-amd64.tar.gz
 src_file_sha256: 702ad90f705365227e902b42d91dd1a40e48ca7f67a2f4b2fd052aaa4295cd95
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
