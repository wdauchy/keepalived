# Makefile.am
#
# Keepalived OpenSource project.
#
# Copyright (C) 2001-2020 Alexandre Cassen, <acassen@gmail.com>

AM_CPPFLAGS		= $(KA_CPPFLAGS) $(DEBUG_CPPFLAGS)
AM_CFLAGS		= $(KA_CFLAGS) $(DEBUG_CFLAGS)
AM_LDFLAGS		= $(KA_LDFLAGS) $(DEBUG_LDFLAGS)
# AM_LIBS		= $(KA_LIBS)
# AM_LIBTOOLFLAGS	= $(KA_LIBTOOLFLAGS)

AM_CPPFLAGS		+= -I$(srcdir)/../include -I$(srcdir)/../../lib

noinst_LIBRARIES	= libtracker.a

libtracker_a_SOURCES	= \
	track_file.c

libtracker_a_LIBADD	=
EXTRA_libtracker_a_SOURCES	=

MAINTAINERCLEANFILES	= @MAINTAINERCLEANFILES@
