
# Bastion inventory repository

This is a configuration management database (CMDB)
for tracking configuration items (CIs) specific to
an operational instance of an online managed service.

See: [Service infrastructure configuration repository][1]
[1]: https://github.com/sakaal/service_infra_ansible

## Current implementation

This Git repository contains Ansible inventory variables
for controlling administrative access to bastion hosts
under the following management domain:

    example.com

## Deployment procedure

1. Copy this sample repository to use it as a template
   to start a new repository dedicated to your service instance.
    * Name the new repository according to your management domain name.
