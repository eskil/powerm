## Process this file with automake to produce Makefile.in

NULL=

INCLUDES = 							\
	-I$(top_srcdir)/intl 					\
	$(GNOME_INCLUDEDIR)					\
	$(NULL)

lib_LTLIBRARIES = libpowerm.la
noinst_PROGRAMS = test-libpowerm

libpowermincludedir = $(includedir)/powerm/

libpowerminclude_HEADERS     =       \
        powerm.h            \
        $(NULL)

libpowerm_la_LDFLAGS =		\
	$(NULL)

libpowerm_la_SOURCES =		\
	powerm.c		\
	powerm.h		\
	$(NULL)

libpowerm_la_LDFLAGS =		\
	-version-info 0:0:0	\
	$(NULL)

test_libpowerm_SOURCES =	\
	test-libpowerm.c	\
	$(NULL)

test_libpowerm_LDADD = 		\
	libpowerm.la		\
	$(NULL)

