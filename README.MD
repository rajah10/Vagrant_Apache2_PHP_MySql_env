Setup Apache server, PHP and MySql in Vagrant 

## Git Clone

`cd folder` and run `mkdir files` and keep you files in the folder.

Open terminal and run 
`vagrant up`

Check Vagrant file to uncomment the provisoiner path, run `vagrant provision` if needed

## Setup the MySql environment 

Run `vagrant ssh` and run
`mysql_secure_installation` to setup MySql; follow the instructions
 <a href="https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-in-ubuntu-16-04#step-2-install-mysql-to-manage-site-data">Read more </a>

## Setup vhost

<a href="https://github.com/rajah10/Vagrant_vhost"> How to set up vhost </a>