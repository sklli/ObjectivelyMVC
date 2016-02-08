lib_LTLIBRARIES = \
	libObjectivelyMVC.la

include_HEADERS = \
	Action.h \
	Button.h \
	Checkbox.h \
	Colors.h \
	Control.h \
	Font.h \
	Image.h \
	ImageView.h \
	Label.h \
	Log.h \
	Option.h \
	Select.h \
	StackView.h \
	TextView.h \
	View.h \
	Viewcontroller.h

libObjectivelyMVC_la_SOURCES = \
	Action.c \
	Button.c \
	Checkbox.c \
	Colors.c \
	Control.c \
	Font.c \
	Image.c \
	ImageView.c \
	Label.c \
	Option.c \
	Select.c \
	StackView.c \
	TextView.c \
	View.c \
	ViewController.c

libObjectivelyMVC_la_CFLAGS = \
	-I $(top_builddir) -I $(top_builddir)/Sources\
	-DPACKAGE_DATA_DIR=\"$(pkgdatadir)\" \
	@HOST_CFLAGS@ \
	@FONTCONFIG_CFLAGS@ \
	@OBJECTIVELY_CFLAGS@ \
	@SDL2_CFLAGS@

libObjectivelyMVC_la_LDFLAGS = \
	@HOST_LDFLAGS@ \
	-shared

libObjectivelyMVC_la_LIBADD = \
	@HOST_LIBS@ \
	@FONTCONFIG_LIBS@ \
	@OBJECTIVELY_LIBS@ \
	@SDL2_LIBS@