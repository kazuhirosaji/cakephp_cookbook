# Environment for cakephp application

This is environment for develop cakephp application managed by **chef-solo**.

This virtual environment is
- Vagrant 1.3.5
- Ubuntu 10.04.4

Ubuntu environment will install
- apache2
- PHP 5.X
- Mysql

And [cakephp 2.5.6] are placed in /var/www/

# Usage
- Download this repository to your local pc.
- Start terminal application.
- Go to downloaded repository's directory.
- Put command "chmod -R 777 ./app/tmp"
- Put command "vagrant up"
- Start browser and go to "http://192.168.33.10/cakephp_bbbs/"

# Repository onfo
This repository copy from
https://github.com/kazuhirosaji/bbbs_cookbook.git at 2014/12/1 version.
