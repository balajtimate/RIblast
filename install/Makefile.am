## File used by automake to generate the Makefile.in ##

# Project layout (foreign as not following the std layout of a GNU project)
AUTOMAKE_OPTIONS=foreign

# Program name
bin_PROGRAMS=RIblast

# Directory variable for source files
RIblastdir = src

# Source files
RIblast_SOURCES = \
    src/db_construction.cpp \
    src/fastafile_reader.cpp \
    src/main.cpp \
    src/rna_interaction_search_parameters.cpp \
    src/ungapped_extension.cpp \
    src/db_construction_parameters.cpp \
    src/fmath.hpp \
    src/raccess.cpp \
    src/encoder.cpp \
    src/gapped_extension.cpp \
    src/rna_interaction_search.cpp \
    src/seed_search.cpp \
    src/sais.cpp

# Header files
RIblast_HEADERS = \
    src/energy_par.h \
    src/hit.h \
    src/rna_interaction_search.h \
    src/seed_search.h \
    src/db_construction.h \
    src/fastafile_reader.h \
    src/intloops.h \
    src/rna_interaction_search_parameters.h \
    src/ungapped_extension.h \
    src/db_construction_parameters.h \
    src/gapped_extension.h \
    src/raccess.h \
    src/encoder.h \
    src/sais.h

# Add headers to the distribution
dist_noinst_HEADERS = $(RIblast_HEADERS)