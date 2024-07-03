LIBTOOL=libtool
RANLIB=ranlib

noinst_HEADERS = rms.h db.h blo.h pitchscale.h waveguide_nl.h biquad.h iir.h buffer.h ls_filter.h

noinst_LTLIBRARIES = librms.la libdb.la libblo.la libpitchscale.la libiir.la

librms_la_SOURCES = rms.c
libdb_la_SOURCES = db.c
libblo_la_SOURCES = blo.c
libblo_la_CFLAGS = -I@top_srcdir@
libpitchscale_la_SOURCES = pitchscale.c
libpitchscale_la_CFLAGS = $(FFTW_CFLAGS)
#libpitchscale_la_LIBS = $(FFTW_LIBS)
libiir_la_SOURCES = iir.c
libiir_la_CPPFLAGS = -I@top_srcdir@
#libbuffer_la_SOURCES = buffer.c
# Disable autoheader. 
AUTOHEADER=echo
