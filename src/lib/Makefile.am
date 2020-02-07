noinst_LIBRARIES = libhell.a
libhell_a_SOURCES = hell.h hell.c

if DEBUG
  AM_CFLAGS =-I$(top_srcdir)/src/lib -Wall -g -O3
else
  AM_CFLAGS =-I$(top_srcdir)/src/lib -Wall
endif
