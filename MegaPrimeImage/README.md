Click the binder badge to try it live without installing anything.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/LiaoWenyun/my_tutorial/master)

A development environment for MegaPrimeImage can be created:

1.Install docker
2.Git clone this repository
3.Cd into MegaPrimImage directory
4.$docker build -t mega-prime-image -f Dockerfile .
5.$docker run --rm -d -p 8888:8888 --name [name] mega-prime-image
6.Browse to http://localhost:8888


