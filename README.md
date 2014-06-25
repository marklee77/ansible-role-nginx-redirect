nginx-redirect
==============

The purpose of this role is to install nginx redirect sites.

Role Variables
--------------

- nginx_redirect_hostname: localhost
- nginx_redirect_http_port: 80
- nginx_redirect_https_port: 443
- nginx_redirect_enable_ssl: true

- nginx_redirect_ssl_cert_file: ""
- nginx_redirect_ssl_key_file: ""

- nginx_redirect_name: redirect
- nginx_redirect_url: http://blog.stillwell.me

Example Playbook
-------------------------

    - hosts: default
      sudo: True
      roles:
        - marklee77.nginx-redirect

Try it Out
---------------------------

Check out the github repository, vagrant up, and load http://localhost:8080 in
your web browser.

License
-------

GPLv2

Author Information
------------------

http://marklee77.github.io

