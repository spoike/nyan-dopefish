# Nyan Dopefish CLI

Nyan Dopefish rendered in your terminal. Forked from [klange/nyancat](http://github.com/klange/nyancat).

[![Dopefish Lives!](http://www.dopefish.com/images/swimfish2.gif)](http://www.dopefish.com/images/swimfish2.gif)

## Setup

First build the C application:

    make && cd src

You can run the C application standalone.

    ./nyancat

To use the telnet server, you need to add a configuration that runs:

    nyancat -t

We recommend `openbsd-inetd`, but both `xinetd` and `systemd` work as well. You
should be able to use any other compatible `inetd` flavor too.

## Licenses, References, etc.

The original source of the Nyancat animation is
[prguitarman](http://www.prguitarman.com/index.php?id=348).

The code provided here is provided under the terms of the
[NCSA license](http://en.wikipedia.org/wiki/University_of_Illinois/NCSA_Open_Source_License).
