AM_MAKEFLAGS = --no-print-directory
AM_CFLAGS = ${GTK2_CFLAGS}

bin_PROGRAMS = trayer
trayer_SOURCES = \
	bg.c \
	bg.h \
	dbg.h \
	eggmarshalers.c \
	eggmarshalers.h \
	eggtraymanager.c \
	eggtraymanager.h \
	fixedtip.c \
	fixedtip.h \
	gdk-helper.c \
	gdk-helper.h \
	main.c \
	main.h \
	misc.c \
	misc.h \
	panel.c \
	panel.h
trayer_LDADD = ${GTK2_LIBS} ${X_PRE_LIBS} -lX11 ${X_LIBS} ${X_EXTRA_LIBS}

dist_man1_MANS = man/trayer.1
dist_noinst_DATA = CHANGELOG CREDITS
