check_PROGRAMS = \
	test_thread \
	test_event \
	test_msgq

TESTS = $(check_PROGRAMS)

AM_CFLAGS =\
	-I$(top_srcdir)/include/sphinxbase \
	-I$(top_srcdir)/include \
	-I$(top_builddir)/include \
	-DTESTDATADIR=\"$(top_srcdir)/test/regression\"

LDADD = ${top_builddir}/src/libsphinxbase/libsphinxbase.la

noinst_HEADERS = test_macros.h

CLEANFILES = *.log
