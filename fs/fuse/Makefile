#
# Makefile for the FUSE filesystem.
#

obj-$(CONFIG_FUSE_FS) += fuse.o
obj-$(CONFIG_CUSE) += cuse.o

fuse-objs := dev.o dir.o file.o inode.o control.o xattr.o acl.o
<<<<<<< HEAD
fuse-$(CONFIG_OPLUS_FEATURE_FUSE_FS_SHORTCIRCUIT) += shortcircuit.o
=======
fuse-objs += passthrough.o
>>>>>>> 4c95a0cf63723cdd988e63e0c956b74c8a1767b0
