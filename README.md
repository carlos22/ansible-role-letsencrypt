Role Name
=========

Enables HTTPS on your website

Role Variables
--------------

- certbot_vhost is VirtualHost certbot should use
- letsencrypt_email should be admin email

Example Playbook
----------------

How to use role:

    - hosts: foo
      roles:
         - { role: ysz.letsencrypt, certbot_vhost: foo.com, letsencrypt_email: admin@foo.com }

License
-------

BSD

