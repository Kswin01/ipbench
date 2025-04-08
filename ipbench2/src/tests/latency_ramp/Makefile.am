AM_CPPFLAGS = $(WARNINGCFLAGS)

plugindir=$(libdir)/ipbench
plugin_LTLIBRARIES = liblatencyramp.la
liblatencyramp_la_CFLAGS = -I$(top_srcdir)/src
liblatencyramp_la_LIBADD = ../../lib/libipbench.la
liblatencyramp_la_SOURCES=latency_ramp.c ip_ramp.c raw_ramp.c latency_ramp.h
