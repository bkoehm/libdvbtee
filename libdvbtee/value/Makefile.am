lib_LTLIBRARIES = libvalueobj.la

libvalueobj_la_SOURCES = value.cpp object.cpp array.cpp utf8strip.cpp

EXTRA_DIST=value.h object.h array.h

VALOBJ_LIBRARY_VERSION=1:0:0

libvalueobj_la_LDFLAGS = -version-info $(VALOBJ_LIBRARY_VERSION)

library_includedir=$(includedir)/value
library_include_HEADERS = value.h object.h array.h
