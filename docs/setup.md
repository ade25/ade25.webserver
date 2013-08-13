Setup webserver buildout
========================

We strive to establish a general working environment and therefore provide
this "best practice" information. In order to make a webserver buildout
usable in your local development environment you only need to follow a few
simple steps:


Requirements
------------

All interaction is based on the push deployment tool Fabric. In order to 
bootstrap you local directory you need to setup a virtual environment and
install a few dependencies

``` bash
# cd ~/
# ../python/bin/virtualenv-2.7 devop
# cd ~/devop
# source bin/activate
(ws)# pip install -U setuptools
(ws)# pip install fabric
```

