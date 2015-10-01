# Vagrant Setup for Laraval 5.1
This is Vagrant box for the laraval configurations. This laraval application is runing on top of Apache application server

#Components 
1) Composer - INSTALLED
2) MySql 5.6  - INSTALLED
3) bower - INSTALLED
4) PhP 5.6 - INSTALLED
5) Ubuntu 14.4 - INSTALLED




#Seteps

Before vagrant up
------------------
Once you clone / download  this repository do the following changes before you start the server
1) Change vb.name = "Laraval5.1" to your project Name
2) Change vhosts according to the project configurations
3) Past all create DB queries to the migrations/schema.sql
4) Past all default insert values to migrations/insert_default.sql
5) Change host file in your working PC

To setup vagrant box navigate to the provission folder through your command line. While you are in this folder run following command
* $ vagrant up

Let command to do the installations

After vagrant up
----------------
After installing vagrant login to the vagrant box through ssh. While you are in provission folder run following command

* $ vagrant ssh


navigate to /web/application and check all the dependencies are installed correctly.

Thats it .....

You can code your application it will sync to ubuntu ubuntu server.

