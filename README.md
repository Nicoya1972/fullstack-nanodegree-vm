# Catalog Web App

This is an Udacity nanodegree full stack web development project and it provides a list of items within a variety of categories as well as provide a user authentication system.
Users will have the ability to post, edit and delete their own items. 

# Getting started

You can clone or download this project from: https://github.com/Nicoya1972/fullstack-nanodegree-vm

# Prerequisites

You will need to install these following application in order to make this code work.
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant](https://www.vagrantup.com/downloads.html)


* [VM configuration](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/59822701_fsnd-virtual-machine/fsnd-virtual-machine.zip)

# VM configuration

### Installing

* Unzip the VM configuration and you will find a vagrant folder
* Use the Terminal to get into the vagrant folder from VM configuration
run the following command
* $ vagrant up
* This will cause Vagrant to download the Linux operating system and install it.
After it finished and after the shell prompt comes back, you can run this command
* $ vagrant ssh
And this will let you login to the Linux VM.
Setting up the enviroment

* Move the folder you downloaded from GitHub and put it into the vagrant folder
use the following line to get into the vagrant VM folder
* $ cd /vagrant
Use the command line to get in to the folder you just downloaded
Then you can run this command
* $ pyhton database_setup.py
* $ python loadData.py
After it added items succesfully, you can run the following command
* $ python project.py
After finish running project.py you can use your favorite browser to visit this link
* http://localhost:8000/catalog/

# How to use

* You can browse through the website to find out the different categories of sports.
* You can also create you own items after you login.
* Only the users who created the item have the ability to post, edit, and delete it.
* You can edit or delete an item that you have created.
* You can also log out and you will lost your right to change this item.

