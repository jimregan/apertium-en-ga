#                                               -*- Autoconf -*-
# Procgas this file with autoconf to produce a configure script.


AC_PREREQ(2.52)

AC_INIT([apertium-en-ga], [0.0.1], [jimregan@users.sourceforge.net])
AM_INIT_AUTOMAKE([apertium-en-ga], [0.0.1], no-define)
AC_PROG_LN_S
AC_PROG_AWK
AC_CONFIG_HEADER([config])

m4_define([required_apertium_version], [3.2.0])
PKG_CHECK_MODULES(APERTIUM,   apertium >= required_apertium_version, [], [PKG_CHECK_MODULES(APERTIUM,   apertium >= required_apertium_version)])
                          
ALTXSL="alt.xsl";

AC_SUBST(ALTXSL)

  
AC_OUTPUT([Makefile])
