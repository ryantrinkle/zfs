pkgdatadir = $(datadir)/@PACKAGE@/zfs-tests/tests/functional/acl
dist_pkgdata_DATA = \
	acl.cfg \
	acl_common.kshlib

# XXX - when I add these subdirs, there's no Makefile generated in them
#       by autoconf, but make tries to build in them and craps out?
# SUBDIRS = nontrivial posix trivial
SUBDIRS = posix
