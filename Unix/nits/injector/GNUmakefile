TOP = ../..
include $(TOP)/config.mak

CXXSHLIBRARY = nitsinj

SOURCES = injector.cpp \

DEFINES = UNICODE

INCLUDES = . $(TOP) $(TOP)/common

ifeq ($(OS), DARWIN)
LIBRARIES = $(PALLIBS)
else
LIBRARIES = rt $(PALLIBS)
endif

include $(TOP)/mak/rules.mak
