if HAVE_SHARED_GLAPI
AM_CPPFLAGS = \
	-I$(top_builddir)/src/gtest/include \
	-I$(top_builddir)/src/mapi \
	-I$(top_builddir)/include

TESTS = shared-glapi-test
check_PROGRAMS = shared-glapi-test

shared_glapi_test_SOURCES =			\
	check_table.cpp

shared_glapi_test_LDADD = \
	$(top_builddir)/src/mapi/shared-glapi/libglapi.la \
	$(top_builddir)/src/gtest/libgtest.la \
	-lpthread
endif
