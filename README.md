# vagrant_project_a

## Description:
This repository provides to you **Ubuntu Xenial Box** configured as follows:
- hostaname **bananas3**
- **nginx** installed
- static IP: **192.168.56.56**
- guest port **80** forwarded to port **8080**


## Files:
- `Vagrantfile` - Contain vagrant box configuration
- `scripts/provision.sh` - this script will install the needed software for our vagrant box durring boot time.

## Requiered software:

- In order to use Vagrant you need to have **Virtualbox** tool installed.
- In order to use the already configured **Vagrantfile** you require **Vagrant** tool installed.

## Install Section:
**Note that following instructions have been tested in Ubuntu**

### Instructions HOW to install `Virtualbox`
- Go to [Virtualbox downloads](https://www.virtualbox.org/wiki/Linux_Downloads) choose **Virtualbox** package
- Type in your terminal: `sudo apt-get install -y virtualbox `

### Instructions HOW to install `Vagrant`
- Download **Vagrant** from [here](https://www.vagrantup.com/downloads.html)
- Click on following link: [Installing vagrant](https://www.vagrantup.com/docs/installation/)

### Instructions HOW to run this project on your computer
- Download the content of **berchev/vagrant_project_a** repository: `git clone https://github.com/berchev/vagrant_project_a.git`
- Change to downloaded **vagrant_project_a** directory: `cd vagrant_project_a`
- Type `vagrant up` and wait the command to finish (Note that it can take up to 10 minutes, depending on your internet connection)
- Type `vagrant ssh` in order to connect to your Ubuntu Xenial Box via ssh
- Type `exit` in order to close the ssh connection
- Type `vagrant halt` in order to power off the Ubuntu Xenial Box
- Type `vagrant destroy` if this project is no longer needed

### TODO
