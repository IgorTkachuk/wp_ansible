# This is Ansible Playbook for provisioning fully functionaly Wordpress web site

## What it's do?

1. Install Apache, MySQL RDBMS, PHP and appropriate Apache moules
2. Creates MySQL wp user and db.
3. Create Apache virtual host config file and enables it.
4. Download latest WordPress distribution and extract archive contens to virtual host root directory
5. Updates WP config file with given DSN and credentials
6. Restart Apache server if need.
