lib_LTLIBRARIES = leagueOverSeer.la

leagueOverSeer_la_SOURCES = leagueOverSeer.cpp
leagueOverSeer_la_CXXFLAGS= -I$(top_srcdir)/include -I$(top_srcdir)/plugins/plugin_utils
leagueOverSeer_la_LDFLAGS = -module -avoid-version -shared -ljson
leagueOverSeer_la_LIBADD = $(top_builddir)/plugins/plugin_utils/libplugin_utils.la

AM_CPPFLAGS = $(CONF_CPPFLAGS)
AM_CFLAGS = $(CONF_CFLAGS)
AM_CXXFLAGS = $(CONF_CXXFLAGS)

EXTRA_DIST = \
	LICENSE.markdown \
	README.markdown \
	leagueOverSeer.cfg \
	leagueOverSeer.def

MAINTAINERCLEANFILES =	\
	Makefile.in
