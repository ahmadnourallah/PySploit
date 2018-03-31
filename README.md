# PySploit Framework
Free exploit framework written use python language version 3.3
<br><br>
<img src="http://webscan.esy.es/pysploit.png">

# Features
* Easy to use
* Free and open source
* Organizer
* Easy to develop it
* Programmed using one of the most popular programming language
* Unlimited possibilities to create
* Durable updates

# Getting Started
The framework does not need many steps to install and start using just follow the next steps

## Platform

the framework designed to run on Gnu/Linux distro only 
> tell us if framework work in another platforms :)

## Prerequisites
the requirement is: 
* bs4
* python-tools
* python3.x
### Installing requirements 
#### installing bs4

Easily, you can install the whole requirements from requirement.txt file by executing this command:
```
sudo python3-pip install -r requirements.txt
```
#### installing python-tools

In Debian and her children the package names is python-examples and you can install it by the packages manager (apt) by this command:
```
sudo apt-get install python-examples
```
But in opensuse it is called python-demo and in fedora/redhat it is called python-tools > in both of them you can also use the packages manager to install the package.

#### installing python3 
The most of linux distro has python preinstalled, but if you have the old version you can install it using your packages manager or from the official website https://www.python.org/downloads/

## Install on you computer
In 1.1 version we added installer to install the framework on your device. So to start installing the tool go to tool directory and execute this command:
```
sudo python3 PySploit.py -i
```
If the installation is done, then the tool will tell you.
Now, if you need to unistall the tool, you can execute this other command:
```
sudo python3 PySploit -un
```
> Note: You should execute the both command with root privilege. I.E use "sudo" infront of your commands.

# Add your module
We designed this framework to be easy for creating your module. All what you need is to define three dictionarys and two functions. :) 
You can read simple_sample.py file in samples directory for more informations. 
> For more info, visit this topic https://github.com/ahmadnourallah/pysploit-framework/wiki/Add-your-module 

# Authors
### Ahmad Nourallah
#### Contact with me
* Facebook Account: <fb.com/ahmadnurallah>
* Github Page: <github.com/ahmadnourallah>
* Email: ahmadnurallah@gmail.com

# License
This project is licensed under the GPL-2.0 License - see the LICENSE file for details

# TODO
* Add new modules
* Make the code smarter
* Attract the developers to using the framework
* Create advanced payload (such as meterpreter in metasploit) help us in this task 
> We always welcome all of the pull requests toward this framework.
