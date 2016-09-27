# Ansible PostgreSQL
An [Ansible](http://www.ansible.com/) role to install a PostgreSQL server on Ubuntu or Debian systems

## Requirements
This role requires Ansible 2.0+

## Variables
 * pg_install_packages: Flag to decide if the role has to install the packages or not. The default is **yes**
 * pg_packages_state: State of the packages. The default is **present**
 * pg_setup: Ensure database is created, user can access the database and does not have unnecessary privileges. The default is **yes**
 * pg_drop_db: Drop existing db cluster. The default is **no**
 * pg_locale: Locale value. The default is **en_US**
 * pg_encoding: Character encoding. The default is **UTF-8**
 * pg_db_name: db name
 * pg_user: username
 * pg_password: password
