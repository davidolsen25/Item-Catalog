# Item-Catalog

Virtual Vending Machine application by David Olsen

This application is a catalog of vending machine items which can be viewed by 
category. The items can be created, edited and deleted by their creator who 
has logged in as such and been authenticated and authorized. The program was 
created using Python with a Flask framework for doing database operations. It 
also provides JSON endpoints for JSON queries.

To run the application:

	1. Install a Linux virtual machine, such as Oracle's VirtualBox and 
	Vagrant to communicate with the host machine.
	2. Download the folder "/Catalog"
	3. From the "Catalog" file, start a virtual machine in the shell with the 
	command: "vagrant up".
	4. From the next prompt, type "vagrant ssh"
	5. When the virtual machine starts, navigate to "/vagrant/catalog"
	6. From there run the command in the shell: "python application.py"
	7. Access the application in a browser at "http://localhost:8000"

The author used VirtualBox 4.3.0 , and Vagrant 1.7.4 . Which are older builds 
of these two programs. If you cannot load these programs, it may be useful to 
load older builds.

Happy Vending!
