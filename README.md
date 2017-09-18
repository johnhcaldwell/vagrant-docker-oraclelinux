Docker Oracle Linux Images for Vagrant
======================================

Dockerfiles and init scripts for building Oracle Linux docker images 
configured for vagrant.

To build an image:
    $ cd vagrant-docker-oraclelinux/5
    $ docker build -t image_name .

Services are started using the script located under bin/my_init. If
you add any services that you want started at container "boot", you 
can add them to this file.
