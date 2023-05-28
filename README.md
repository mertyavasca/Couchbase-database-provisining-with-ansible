# Couchbase-database-provisining-with-ansible
Ansible role for install and configure couchbase database on multiple server. Including bucket and cluster settings.

  ## Points you should consider 

    1. This role is configured for non root installation
    
    2. all servers must have /couchbase directory
    
    3. Related couchbase rpm and installer must be exist on Ansible source machine or you can download directly from official website if you have internet access from your database server.
    
    4. Satellite server can be used for deployment.


