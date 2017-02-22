//How to change root passwd in CentOs7
//change ro to: rw init=/sysroot/bin/sh.
chroot /sysroot
passwd root
touch /.autorelabel
exit
reboot.
