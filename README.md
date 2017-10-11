Easy OpenShift 
==============================


This will provide a simple way to deploy and use openshift docker container. This project is based on openshift api and beego framwork which can be more easy to ordinary users.

INSTALL:
  os:
     This project should run on Centos 7.2-1611
  you need to install go and mysql/mariadb


  1) Get code:

        $ go get github.com/hjimmy/easy-openshift
	$ cd webcron
	$ cd  conf/app.conf
         Modify  your  config

  2) Init database:
	$ mysql -u $username -p$password
        $ create database webcron
        $ mysql -u $username -p$password -D webcron < install.sql

  3) Run:
        $ ./webcron
        or
        $ nohup ./webcron 2>&1 > error.log &

                                                       
