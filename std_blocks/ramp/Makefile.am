ubxmoddir = $(UBX_MODDIR)

AM_CFLAGS = -I$(top_srcdir)/libubx $(UBX_CFLAGS) -fvisibility=hidden
AM_LDFLAGS = -module -avoid-version -shared -export-dynamic

ubxmod_LTLIBRARIES = ramp_float.la \
			ramp_double.la \
			ramp_uint8.la \
			ramp_uint16.la \
			ramp_uint32.la \
			ramp_uint64.la \
			ramp_int8.la \
			ramp_int16.la \
			ramp_int32.la \
			ramp_int64.la

ramp_float_la_SOURCES = ramp.c
ramp_float_la_LIBADD = $(top_builddir)/libubx/libubx.la
ramp_float_la_CFLAGS = $(AM_CFLAGS) -DRAMP_T=float

ramp_double_la_SOURCES = ramp.c
ramp_double_la_LIBADD = $(top_builddir)/libubx/libubx.la
ramp_double_la_CFLAGS = $(AM_CFLAGS) -DRAMP_T=double

ramp_uint8_la_SOURCES = ramp.c
ramp_uint8_la_LIBADD = $(top_builddir)/libubx/libubx.la
ramp_uint8_la_CFLAGS = $(AM_CFLAGS) -DRAMP_T=uint8_t -DBLOCK_NAME=uint8

ramp_uint16_la_SOURCES = ramp.c
ramp_uint16_la_LIBADD = $(top_builddir)/libubx/libubx.la
ramp_uint16_la_CFLAGS = $(AM_CFLAGS) -DRAMP_T=uint16_t -DBLOCK_NAME=uint16

ramp_uint32_la_SOURCES = ramp.c
ramp_uint32_la_LIBADD = $(top_builddir)/libubx/libubx.la
ramp_uint32_la_CFLAGS = $(AM_CFLAGS) -DRAMP_T=uint32_t -DBLOCK_NAME=uint32

ramp_uint64_la_SOURCES = ramp.c
ramp_uint64_la_LIBADD = $(top_builddir)/libubx/libubx.la
ramp_uint64_la_CFLAGS = $(AM_CFLAGS) -DRAMP_T=uint64_t -DBLOCK_NAME=uint64

ramp_int8_la_SOURCES = ramp.c
ramp_int8_la_LIBADD = $(top_builddir)/libubx/libubx.la
ramp_int8_la_CFLAGS = $(AM_CFLAGS) -DRAMP_T=int8_t -DBLOCK_NAME=int8

ramp_int16_la_SOURCES = ramp.c
ramp_int16_la_LIBADD = $(top_builddir)/libubx/libubx.la
ramp_int16_la_CFLAGS = $(AM_CFLAGS) -DRAMP_T=int16_t -DBLOCK_NAME=int16

ramp_int32_la_SOURCES = ramp.c
ramp_int32_la_LIBADD = $(top_builddir)/libubx/libubx.la
ramp_int32_la_CFLAGS = $(AM_CFLAGS) -DRAMP_T=int32_t -DBLOCK_NAME=int32

ramp_int64_la_SOURCES = ramp.c
ramp_int64_la_LIBADD = $(top_builddir)/libubx/libubx.la
ramp_int64_la_CFLAGS = $(AM_CFLAGS) -DRAMP_T=int64_t -DBLOCK_NAME=int64
