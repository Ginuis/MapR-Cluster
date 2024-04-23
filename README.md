# MapR-Cluster
MapR ezmeralda 6.1 three-node cluster

MapR Ansible

Build Status

This is a Ansible scripts which help you to setup a MapR-cluster.

Maintainer: Splendeurs - Big Data Administrator/Data Engineer 

Changes, bugs and feature requests can be requested by using the Github issue tracker. If you want to contribute to the project, open pull requests via Github.

The scripts support:

Install MapR-Cluster including Ecosystem Components (only one playbook to execute)
Modify an existing installation
Adding and removing components
Adding and decomissioning nodes
The script also support dry-run on an installed cluster
Aborted scripts can always re-run.
Building Zeppelin
Install MapR-Client
Setting up Kerberos and generate Keytabs (only Redhat)
Ansible modules to manage state of:
MapR volumes
MapR schedules
MapR Accountable Entities
