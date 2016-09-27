### Key Concepts and Terms with Vagrant 

* `vagrant up`
	* The simple command needed to bring up the full development environment
* `Vagrantfile`
	* The configuration file used by Vagrant to describe the development environment needed
	* When you `vagrant up`, vagrant will look for a file called `Vagrantfile` in the working directory.  You can use a differnet name, but you'll need to specify it
* A **box**
	* Vagrant refers to the source images or templates it uses to provision new development environments as **boxes**
	* You can build your own boxes, but there is a very large assortment of available ones maintained by the community 
	* Each **box** is for a particular provider, but most underlying OS's or platforms have boxes available for all common providers.  


