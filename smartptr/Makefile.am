# -*- makefile -*-
#------------------------------------------------------------------------------
#                              src/Makefile.am
#
#------------------------------------------------------------------------------

#bin_PROGRAMS = YOUR-APPLICATION-NAME

#your_application_name_SOURCES = \
#  list your files here

noinst_HEADERS = \
	smartptr
#  list your headers here

INCLUDES = \
	-g \
	@CXXFLAGS@

LDFLAGS= -g @LDFLAGS@ 

libsmartptr_includedir = $(includedir)/smartptr
libsmartptr_include_HEADERS = $(noinst_HEADERS)

clean-local:
	-rm -f log *.log *.log.old *~ *.dat *.gwm

# Disable autoheader.
AUTOHEADER=echo 

CLEANFILES = *~ 

MAINTAINERCLEANFILES= \
config.h.in \
Makefile.in
