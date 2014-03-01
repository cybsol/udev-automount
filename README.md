udev - rules for automount
=============================

Description
-----

 *   Mounting into /media
 *   RW permissions for users group (gid=100)
 *   Will remove created directory after eject (__strongly recommended to use *<code>sync</code>* command before eject__)

Installation
---------

Require <code>blkid</code>, which used for label identify.

Copy rules files to the directory: <code>/etc/udev/rules.d</code>

reload udev rules

