# Laravel
This playbook installs below packages.
* nginx
* mysql-server
* unzip
* php-fpm
* php-mysql
* php-cli
* php-mbstring
* php-xml
* php-bcmath
* php-curl
* php7.4-gd
* composer

Run command:
```ansible-playbook php.yaml --extra-vars='ansible_become_pass=<sudo_password_of_your_user> nodes=<target>'```
