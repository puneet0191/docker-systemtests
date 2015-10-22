# Docker Systemtest image
[![](https://badge.imagelayers.io/yveshoppe/joomla-systemtests:latest.svg)](https://imagelayers.io/?images=yveshoppe/joomla-systemtests:latest 'Get your own badge on imagelayers.io')

Docker with LAMP setup, firefox and other tools for system tests with codeception.

Based on docker phusion/baseimage (Ubuntu 14.04) and customizations

Current iamges can also be found at dockerhub:

https://hub.docker.com/r/yveshoppe/joomla-systemtests/builds/

```docker pull yveshoppe/joomla-systemtests``

## Included software

* Apache 2.4
* MySQL 5.5
* PHP 5.3
* PHP 5.5
* PHP 5.6
* Composer (System wide)
* Robo.li (System Wide)
* Pear
* PHPUnit
* Phing
* PHP_CommandLineTools
* PHPcs 1.5.6 including Joomla coding standards
* PHPcpd

### Gui Software

* Firefox
* Fluxbox and Xvfb (to run selenium tests)
