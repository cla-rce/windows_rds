# windows_rds cookbook

# Requirements

# Usage

# Attributes

* `node[:windows_rds][:certcn]`
* `node[:windows_rds][:remoteapp_hostname]`

# Recipes

default
-------
Installs RDS server roles and sets RDS SSL certificate and RemoteApp hostname, if those attributes are configured.

roles
-----
Installs RDS server roles.

# Resources/Providers

`windows_rds_remoteapp`
-----------------------

### Actions

- :create: *Default action*
- :delete:

### Attribute Parameters

- alias
- displayname
- path

# Author

Author:: Adam Mielke, (C) Regents of the University of Minnesota (<adam@umn.edu>)
