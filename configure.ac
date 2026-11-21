AC_PREREQ([2.60])
AC_INIT([xlibre-xf86-video-v4l],
        [25.0.1],
        [https://github.com/X11Libre/xf86-video-v4l/issues],
        [xlibre-xf86-video-v4l])

XLIBRE_INIT_MODULE_AM(v4l)

# Newer xorg-server.m4 defines this too; keep it for older SDKs.
version_suffix=`echo "$PACKAGE_VERSION" | sed 's/^[[^-]]*//'`
AC_DEFINE_UNQUOTED([PACKAGE_VERSION_SUFFIX], ["$version_suffix"],
                   [Pre-release suffix of the version])

AC_CONFIG_FILES([Makefile src/Makefile man/Makefile])
AC_OUTPUT
