This repository contains Vagrantfiles and the configuration Vagrant need to deploy different playground and development machine for Open Source products developed by [it-novum](http://www.it-novum.com/)

# Requirements
You need to install [Vagrant](https://www.vagrantup.com/downloads.html) and [VirtualBox](https://www.virtualbox.org/wiki/Downloads) on your machine

Ubuntu/Debian based systems:
````
apt-get install vagrant virtualbox
````

Please check the README inside of the different folders for more information

# Important Vagrant commands
* vagrant up
* vagrant halt
* vagrant destroy
* vagrant ssh

* vagrant --help

# Quick start guide (openITCOCKPIT)
This example shows you how you can run the openITCOCKPIT vagrant box.
````
apt-get install vagrant virtualbox
mkdir openITCOCKPIT_V3-dev
cd openITCOCKPIT_V3-dev
wget https://raw.githubusercontent.com/it-novum/vagrantboxes/master/openITCOCKPIT_V3-dev/Vagrantfile
vagrant up
````

# Have a problem or ideas to improve?
Please don't hesitate to create a Issue or Pull Request

# License
MIT-License