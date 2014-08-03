# -----------------------------------------------------
# Makefile.am example
# -----------------------------------------------------

SUBDIRS = smartptr $(DOXYGEN)
DIST_SUBDIRS = $(SUBDIRS) 

EXTRA_DIST = \
	smartptr.spec.in \
	app-docs.make

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = smartptr.pc

dist-hook: smartptr.spec
	cp smartptr.spec $(distdir)

MAINTAINERCLEANFILES= \
	aclocal.m4 \
	config.guess \
	config.sub \
	config.h.in \
	configure \
	COPYING \
	depcomp \
	INSTALL \
	install-sh \
	ltmain.sh \
	Makefile.in \
	xmldb.spec \
	xmldb.pc \
	missing

CLEANFILES = *~

