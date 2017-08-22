==============
docker-install
==============

Install Docker of specific version (default 17.03)

Usage::

    Centos:
	export ELEMENTS_PATH=$(pwd)
	DIB_DOCKER_INSTALL_VERSION=1.13.1 disk-image-create centos7 vm docker-install
    Ubuntu:
	export ELEMENTS_PATH=$(pwd)
	DIB_DOCKER_INSTALL_VERSION=1.13.1 disk-image-create ubuntu vm docker-install