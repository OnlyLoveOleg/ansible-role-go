go
=========

Role to install (download) Go on remote.


Role Variables
--------------

defaults/main.yml:

```
go_inst:
 src_file_url: "https://storage.googleapis.com/golang/go1.5.1.linux-amd64.tar.gz"
 src_file_sha256: 2593132ca490b9ee17509d65ee2cd078441ff544899f6afb97a03d08c25524e7
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

tallannder@gmail.com
