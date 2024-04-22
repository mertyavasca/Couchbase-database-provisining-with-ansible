# Couchbase-database-provisining-with-ansible
Ansible role for install and configure couchbase database on multiple server. Including bucket and cluster settings.

  ## Points you should consider 

    1. This role is configured for non root installation
    
    2. all servers must have /couchbase directory, it is hardcoded you can change it directly.
    
    3. Related couchbase rpm and installer must be exist on Ansible source machine or you can download directly from official website if you have internet access from your database server.
    
    4. Satellite server can be used for deployment.


![image](https://github.com/LexusNeira/Couchbase-database-provisining-with-ansible/assets/62284827/09f0f364-94d1-4043-9936-ec496927b181)
