Ansible Roles
=============

Collection of ansible roles to create some ec2 infra

Roles
=====

- all_hosts: some basic scaffolding and hardening
- application: the stack hosting the servers includes state persistence
- environment: bastion and vpc creation
- query_infra: some basic lookups for inventory

TODO
====

- [ ] Improve hardening on all hosts
- [ ] Deletion of application stack, fails on SG removal
- [ ] Deletion of VPC needs completion