# A Virtual Machine for Development

## Requirements

* [VirtualBox](https://www.virtualbox.org)
* [Vagrant](http://vagrantup.com)

## How To Build The Virtual Machine

Building the virtual machine is this easy:

```sh
host $ git clone https://github.com/huytbt/php56-node-yeoman-dev-box.git
host $ cd php56-node-yeoman-dev-box
host $ vagrant up
```

That's it.

After the installation has finished, you can access the virtual machine with

```sh
host $ vagrant ssh
```

## What's In The Box

* Git
* PHP 5.6
* Composer
* Apache 2
* SQLite3, MySql
* Nodejs, NPM
* Webmin
* [Yeoman](http://yeoman.io/)
