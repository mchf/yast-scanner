# Makefile.am for scanner/tools

ybin_SCRIPTS =					\
	create_scanner_database			\
	autodetect_scanners			\
	determine_active_scanners		\
	determine_active_scanner_backends	\
	activate_scanner_backend		\
	deactivate_scanner_backend		\
	test_scanner_backend			\
	determine_network_scanner_config	\
	setup_network_scanner_config

EXTRA_DIST = $(ybin_SCRIPTS)

ybin_PROGRAMS = displaytest
displaytest_SOURCES = displaytest.c
displaytest_LDADD = -lX11

