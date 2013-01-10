Arch-Install
============

Simple bash Arch install script

Usage:
======

You will need to have partitioned your drive, created filesystems and mounting them to 'new_arch' [set as /mnt by default]. Edited fstab_file to reflect your 
system set up. 

Currently archinstall will install by default base, syslinux, X server, Openbox and packer.

Configures:
===========

Enable wired network connection [dhcp].

Set up basic config files in /etc.

Create a new user, new home directory set password.

Change root passowrd

Simply by editing archinstall, fstab and adding packages to package_list file you can create an install based on your needs.

To use run the following:

  # ./archinstall
