# Ansible PostgreSQL
An [Ansible](http://www.ansible.com/) role to install a PostgreSQL server on Ubuntu or Debian systems  
[![Build Status](https://travis-ci.org/gmauro/ansible-postgresql.svg?branch=master)](https://travis-ci.org/gmauro/ansible-postgresql)

## Requirements
This role requires Ansible 2.0+. See [Ansible installation](http://docs.ansible.com/ansible/intro_installation.html)

## Variables
 * _**pg_version**_: Version of postgres to install. The default is **9.5**
 * _**pg_install_packages**_: Flag to decide if the role has to install the packages or not. The default is **yes**
 * _**pg_packages_state**_: State of the packages. The default is **present**
 * _**pg_setup**_: Ensure database is created, user can access the database and does not have unnecessary privileges. The default is **yes**
 * _**pg_drop_db**_: Drop existing db cluster. The default is **no**
 * _**pg_locale**_: Locale value. The default is **en_US**
 * _**pg_encoding**_: Character encoding. The default is **UTF-8**
 * _**pg_db_name**_: db name
 * _**pg_user**_: username
 * _**pg_password**_: password
