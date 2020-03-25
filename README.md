# Documentation

This README is managed in 

* [README.md](https://github.com/cloudmesh/cloudmesh-pi-cluster/blob/master/README.md)
* <https://github.com/cloudmesh/cloudmesh-pi-cluster>

## Prerequisite

Set up cloudmesh on the master 

```bash
$ sudo apt-get update
$ sudo apt-get full-upgrade
$ sudo apt-get install emacs
$ ssh-keygen
$ echo 'alias python="/usr/bin/python3"' >> ~/.bashrc
$ source .bashrc
$ python --version
$ python -m venv ~/ENV3
$ source ~/ENV3/bin/activate
$ pip install pip -U 
$ pip install cloudmesh-installer 
$ cloudmesh-installer get pi
```

## Setting LEDS

``` bash
$ cms pi led green on
$ cms pi led green off
$ cms pi led red on
$ cms pi led red off
```
