#
# Copyright 2017, Juniper Networks, Inc.
# All rights reserved.
# This SOFTWARE is licensed under the LICENSE provided in the
# ../Copyright file. By downloading, installing, copying, or otherwise
# using the SOFTWARE, you agree to be bound by the terms of that
# LICENSE.

if SLAX_WARNINGS_HIGH
SLAX_WARNINGS = HIGH
endif
if HAVE_GCC
GCC_WARNINGS = yes
endif
include ${top_srcdir}/warnings.mk

AM_CFLAGS = \
    -I${top_builddir} \
    -I${top_srcdir} \
    ${WARNINGS}

lib_LTLIBRARIES = libxi.la

libxiincdir = ${includedir}/libxi

libxiinc_HEADERS = \
    xicommon.h \
    xinodeset.h \
    xiparse.h \
    xirules.h \
    xisource.h \
    xitree.h \
    xiwhiffle.h \
    xiworkspace.h \
    xixpath.h

libxi_la_SOURCES = \
    xisource.c

XXXX=\
    xiparse.c \
    xirules.c \
    xitree.c \
    xiwhiffle.c \
    xiworkspace.c \
    xixpath.c
