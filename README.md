Role Name
=========
gwenlei.wordpress-nginx

Requirements
------------
ubuntu16.04 xenial

Role Variables
--------------
defaults/main.yml

client_max_body_size: 64M
wp_root: /var/www/html/wordpress
site_name: example.com
host: localhost

Dependencies
------------
none

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: gwenlei.wordpress-nginx }

License
-------
MIT

Author Information
------------------
onecloud
