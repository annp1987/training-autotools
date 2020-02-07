if DEBUG
  AM_CFLAGS =-I$(top_srcdir)/src/bin -I$(top_srcdir)/src/lib -Wall -g -O3
else
  AM_CFLAGS =-I$(top_srcdir)/src/bin -I$(top_srcdir)/src/lib -Wall -O3
endif

AM_CFLAGS += $(GLIB_CFLAGS)
AM_CFLAGS += $(SQLITE3_CFLAGS)
bin_PROGRAMS = hell
hell_SOURCES = main.c

hell_LDADD = $(top_builddir)/src/lib/libhell.a $(AM_LDFLAGS)
hell_LDADD += $(GLIB_LIBS)
hell_LDADD += $(SQLITE3_LIBS)
