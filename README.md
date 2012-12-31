Arch-Install
============

Simple Wrapper for Arch-Install-Scripts

Usage:
======

You will need to have partitioned your drive, created filesystems and mounting them to 'new_arch' [set as /mnt by default].

  # ./arch-install

Currently arch-install will install base syslinux plus any packages found in the file called package_list.

Set up basic config files in /etc.

Create a new user, new home directory set password.

Change root passowrd

If 'wired' is true then create dhcp network connection.

Install syslinux to mbr of drive.

Start to set up config files needed for Openbox
 
Simply by editing arch-install and adding required applications to file package_list you can create an install based on your needs.

