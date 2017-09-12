# vagrant

## Getting started

### Download Software
	Download the latest [Virtualbox](https://www.virtualbox.org/)
	Download the latest [Vagrant](https://www.vagrantup.com/)

	go fast with choco (Windows users - [chocolatey](https://chocolatey.org/install)):
			
		C:\> choco install vagrant
		C:\> choco install virtualbox
		C:\> choco install git.install
		C:\> choco install cyg-get
		C:\> cyg-get openssh
		C:\> cyg-get rsync
		C:\> cyg-get ncurses
			
### First instance
	
	$ vagrant init hashicorp/precise64	
	$ vagrant up
	
## Additional commands
	$ vagrant init
	$ vagrant up
	$ vagrant ssh
	$ vagrant halt
	$ vagrant status
	$ vagrant destroy
	$ vagrant box list
	$ vboxmanage list runningvms
	$ vagrant -v
	$ vagrant reload
	$ vagrant provision
	$ vagrant share (**security)
	$ vagrant share --ssh (**security)
	$ vagrant connect -ssh <share.name>
		 

## Quick response:
	Q: So where are all my virtual boxes?
	A: Windows: C:\Users\%userprofile%\.vagrant.d\boxes
	
	Q: Where can I find additional boxes?
	A: https://app.vagrantup.com/boxes/search 
	
	
	
	