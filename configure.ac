dnl Process this file with autoconf to produce a configure script.
dnl configure.ac is read by both autoconf (configure) and automake (Makefile.in)
dnl AC_ : autoconf macros
dnl AM_ : automake macros

dnl  package name, package version, contact address
AC_INIT([foobar], [1.0], [zheming.jin@mail.com])

AC_CONFIG_AUX_DIR(config)

AC_CONFIG_SRCDIR(src/foobar.cpp)

dnl: enable automake to check dubious instructions in "Makefile.am"
AM_INIT_AUTOMAKE([-Wall -Werror gnu])

dnl: search for a C++ compiler and defines the variable CXX with its name
AC_PROG_CXX

AC_CONFIG_FILES([Makefile src/Makefile])


dnl: produce files 
AC_OUTPUT
