bin_PROGRAMS=SpkAdapt
SpkAdapt_SOURCES= \
	SpkAdapt.cpp\
	SpkAdaptMain.cpp

SpkAdapt_CPPFLAGS=-I../include -I$(top_srcdir)/LIA_SpkTools/include -I$(ALIZE_PATH)/include
SpkAdapt_LDFLAGS=-L$(top_srcdir)/lib -L$(ALIZE_PATH)/lib
SpkAdapt_LDADD=-lliatools_${OS}_${ARCH}${DEBUG} $(lib_alize) $(LIBTHREAD)

all:
	mv ${bin_PROGRAMS} ${top_srcdir}/bin