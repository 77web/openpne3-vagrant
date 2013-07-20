[日本語版はこちら](https://github.com/77web/openpne3-vagrant/blob/master/README-ja.md)

OpenPNE3 Vagrant environment
=================================

OpenPNE is a social network platform.
With this vagrant environment, you can easiliy try OpenPNE3 in your own pc.

Usage
--------

0. Install git for your OS.
1. Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. Install [Vagrant](http://downloads.vagrantup.com/)
3. clone this repository: git clone git://github.com/77web/openpne3-vagrant
4. init & update submodules: git submodule init, git submodule update
5. (Optional) Configure. * If you are just trying out OpenPNE3, nothing to do here.
6. Execute vagrant up
7. Visit http://192.168.33.10 with your browser. Your own OpenPNE3 is already there! :)

Settings
----------

see [openpne3-cookbook](https://github.com/77web/openpne3-cookbook/blob/master/README.md)

Supported OS
--------------

* presice64

phpmatsuri
-------------

I made up openpne3-vagrant and openpne3-cookbook during phpmatsuri 2013, a hackathon event in Japan. This is an annual event, why don't you join us next year? For details: http://phpmatsuri.net
