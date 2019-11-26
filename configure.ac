AC_PREREQ([2.65])
AC_INIT([mtwist], [0.8], [fr.teodoro@gmail.com])
AM_INIT_AUTOMAKE([foreign -Wall -Werror])

m4_ifdef([AM_PROG_AR], [AM_PROG_AR])

# Checks for programs.
AC_PROG_CC
AC_PROG_RANLIB

# Checks for header files.
AC_CHECK_HEADERS([limits.h stdlib.h sys/time.h sys/timeb.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_HEADER_STDBOOL

# Checks for library functions.
AC_CHECK_FUNCS([gettimeofday sqrt])

AC_CONFIG_FILES([Makefile])

AC_OUTPUT
