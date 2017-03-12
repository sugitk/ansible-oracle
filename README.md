# Prepare to install Oracle for Ansible

These roles configure Oracle Database prerequisites for CentOS/RHEL/OEL 6.

## Requirements

- Oracle Database 11gR2, Grid Infrastructure 11gR2
  - CentOS 6.4+
  - Ansible 2.0+
- Oracle Database 12cR1 Enterprise Edition
  - Oracle Enterprise Linux 6.5
  - Ansible 2.2+

## To use a response file to install database software

[oracle@ora11gr2 ~]$ cd database
[oracle@ora11gr2 database]$ ./runInstaller -silent -responseFile /home/oracle/db_install.rsp

## Thanks

- Original scripts are written by ellotheth https://github.com/ellotheth/ansible-oracle
