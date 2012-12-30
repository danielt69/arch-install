Arch-Install
============

Simple Wrapper for Arch-Install-Scripts

Usage:
======

You will need to have partitioned your drive, created filesystems and mounting them to 'new_arch' [set as /mnt by default].

  # ./arch-install

Currently arch-install will install base syslinux plus any packages found in the file package_list [empty by default].

Set up basic config files in /etc.

Add user if 'add_user' is true, create home plus groups and password of new user.

Change root password.

If 'wired' is true then create dhcp network connection.

Install syslinux to mbr of drive.
 
Simply by editing arch-install variables you can create an install based on your needs.
