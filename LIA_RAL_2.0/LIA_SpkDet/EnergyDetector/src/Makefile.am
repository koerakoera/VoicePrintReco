bin_PROGRAMS=EnergyDetector
EnergyDetector_SOURCES= \
	EnergyDetector.cpp\
	EnergyDetectorMain.cpp

EnergyDetector_CPPFLAGS=-I../include -I$(top_srcdir)/LIA_SpkTools/include -I$(ALIZE_PATH)/include
EnergyDetector_LDFLAGS=-L$(top_srcdir)/lib -L$(ALIZE_PATH)/lib
EnergyDetector_LDADD=-lliatools_${OS}_${ARCH}${DEBUG} $(lib_alize) $(LIBTHREAD)

all:
	mv ${bin_PROGRAMS} ${top_srcdir}/bin