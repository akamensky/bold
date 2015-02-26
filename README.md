# Toy compilable language
Just a little toy project of compilable language built using LLVM as compiler infrastructure

## How-to

* Install Vagrant
* Start and provision VM - `$ vagrant up`
* Login to VM - `$ vagrant ssh`
* Build compiler - `$ cd /vagrant/ && make`
* Test v1 - `$ make test` or v2 - `$ ./parser < example.txt`

