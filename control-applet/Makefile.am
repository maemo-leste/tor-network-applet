controllib_LTLIBRARIES = control-applet-tor.la
controllibdir = $(controlpanellibdir)

control_applet_tor_la_SOURCES = \
	control-applet.c \
	wizard.c

control_applet_tor_la_CFLAGS = \
	$(libhildon_CFLAGS) \
	$(hildoncontrolpanel_CFLAGS) \
	$(gtk2_CFLAGS) \
	$(glib2_CFLAGS) \
	$(libosso_CFLAGS) \
	$(gconf_CFLAGS) \
	-Wall -Werror

control_applet_tor_la_LIBADD = \
	$(libhildon_LIBS) \
	$(hildoncontrolpanel_LIBS) \
	$(gtk2_LIBS) \
	$(glib2_LIBS) \
	$(libosso_LIBS) \
	$(gconf_LIBS)

control_applet_tor_la_LDFLAGS = -Wl,--as-needed -shared -module -avoid-version

