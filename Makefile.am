#
#  $Id: Makefile.am,v 1.3 2005/06/21 00:23:41 holtmann Exp $
#

sbin_PROGRAMS = hciemu

hciemu_SOURCES = hciemu.c glib-ectomy.h glib-ectomy.c

LDADD = @BLUEZ_LIBS@

AM_CFLAGS = @BLUEZ_CFLAGS@

MAINTAINERCLEANFILES = Makefile.in \
	aclocal.m4 configure config.h.in \
	missing install-sh mkinstalldirs
