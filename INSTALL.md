# How to install ucspi-tcp

Like any other piece of software (and information generally), ucspi-tcp comes with NO WARRANTY. 

## System requirements

ucspi-tcp works only under UNIX. 

## Installation

Download the ucspi-tcp package.

Unpack the ucspi-tcp package:

```shell
gunzip ucspi-tcp-0.88.tar
tar -xf ucspi-tcp-0.88.tar
cd ucspi-tcp-0.88
```

Compile the ucspi-tcp programs:

```shell
make
```

As root, install the ucspi-tcp programs under `/usr/local`:

```shell
make setup check
```

To report success:

```shell
( echo 'First M. Last'; cat `cat SYSDEPS` ) \
| mail djb-sysdeps@cr.yp.to
```

Replace `First M. Last` with your name. 

