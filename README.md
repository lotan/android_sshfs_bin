android_sshfs_bin
=================

The aim of this project is solely to provide binaries of sshfs.

All credit for doing the hard work goes to l3iggs.

His instructions along with the sources can be found here:

   https://github.com/l3iggs/android_external_sshfs

I simply followed those instructions using

   Cyanogenmod 10.2 for pyramid

I recently acquired a new phone and tried out those old binaries on it.
They worked.
That's when I figured they might work for other people as well who might be put off by the lengthy build process.

What's needed?
- a rooted Android phone

Instructions:
Using your favourite method...
- remount /system rw
- copy sshfs to either /system/bin or /system/xbin
- chmod 755 to /system/bin/sshfs
- copy all four *.so files to /system/lib

l3iggs has instructions on how to mount a remote file system via sshfs.
