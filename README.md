# What's thingOS?

**thingOS** is a highly customized [BuildRoot](https://buildroot.uclibc.org) that serves as a base for IoT dedicated operating systems. If you want to turn your Raspberry PI board into something that controls your lights, doors, sprinklers or other devices, by designing your own "firmware", thingOS may be a good choice.

# Philosophy

**thingOS** aims to make the development of small dedicated Linux-based OSes an easy task. Deployment, over-the-air updates and backups shouldn't be a pain in the ass. Developers should concentrate on their main goal rather than removing unused packages and services from existing OSes to lighten them up, taking care of network connection reliability or enabling the watchdog.

**thingOS** tries to boot as fast as possible. Whenever something goes wrong, we prefer to reboot the system instead of trying to run complex recovery procedures.

**thingOS** doesn't reinvent the wheel. It uses the amazing infrastructure provided by BuildRoot but comes with customized configurations and init scripts for the supported hardware platforms.

# Features

 * support for popular single-board computers (see [Supported Single-board Computers](https://github.com/ccrisan/thingos/wiki/Supported-Single-board-Computers))
 * quick boots (see [Boot Process](https://github.com/ccrisan/thingos/wiki/Boot-Process))
 * read-only partitions to minimize corruption risks (see [Partitions](https://github.com/ccrisan/thingos/wiki/Partitions))
 * simple configuration via text files (see [OS Configuration](https://github.com/ccrisan/thingos/wiki/OS-Configuration))
 * over-the-air "firmware" updates (see [Firmware Updates](https://github.com/ccrisan/thingos/wiki/Firmware-Updates))
 * out-of-the box backup and restore mechanism (see [Backup/Restore](https://github.com/ccrisan/thingos/wiki/Backup-Restore))
 * high reliability (see [Reliability](https://github.com/ccrisan/thingos/wiki/Reliability))
 * everything that [BuildRoot](https://buildroot.uclibc.org) has to offer

# Getting Started

Just follow the [Getting Started](https://github.com/ccrisan/thingos/wiki/Getting-Started) guide.

# Supported Boards

Here's a list of [Supported Single-board Computers](https://github.com/ccrisan/thingos/wiki/Supported-Single-board-Computers).

# Documentation

Feel free to browse the [wiki articles](https://github.com/ccrisan/thingos/wiki).
