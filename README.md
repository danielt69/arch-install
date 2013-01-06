Arch-Install
============

Simple bash Arch install script

Usage:
======

You will need to have partitioned your drive, created filesystems and mounting them to 'new_arch' [set as /mnt by default].

  # ./archinstall

Currently archinstall will install by default base, syslinux, X server, Openbox, packer and enable wired network connection [dhcp].

Set up basic config files in /etc.

Create a new user, new home directory set password.

Change root passowrd

Simply by editing archinstall and adding required applications to file package_list you can create an install based on your needs.

