# Ansible PostgreSQL role

This Ansible role will install the PostgreSQL database engine from the main
Ubuntu repository. The role is tested and designed for use on Ubuntu 16.04.

## Installation

```
cd roles

git clone https://github.com/hagbarddenstore/ansible-postgresql postgresql
```

If you're running in a virtual environment (virtualenv, you should!), activate
the environment and run ```pip install -r requirements.txt```.

## Usage

Include the role in your playbook:

```
- hosts: your_database_hosts
  roles:
    - name: postgresql
```
