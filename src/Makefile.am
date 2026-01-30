# SPDX-License-Identifier: MIT OR X11
#
# Copyright © 2026 Enrico Weigelt, metux IT consult <info@metux.net>
#

AM_CFLAGS = $(XLIBRE_SERVER_CFLAGS)

v4l_drv_la_LTLIBRARIES = v4l_drv.la
v4l_drv_la_LDFLAGS     = -module -avoid-version
v4l_drv_ladir          = @xlibre_video_drivers_dir@

v4l_drv_la_SOURCES = v4l.c videodev2.h
