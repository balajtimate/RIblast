# Define minimum cmake version
cmake_minimum_required(VERSION 3.5 FATAL_ERROR)

# Project name and supported language
project(RIblast LANGUAGES CXX)

# Require C++11
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# List all source files
set(SOURCE_FILES
    src/db_construction.cpp
    src/fastafile_reader.cpp
    src/main.cpp
    src/rna_interaction_search_parameters.cpp
    src/ungapped_extension.cpp
    src/db_construction_parameters.cpp
    src/fmath.hpp
    src/raccess.cpp
    src/encoder.cpp
    src/gapped_extension.cpp
    src/rna_interaction_search.cpp
    src/seed_search.cpp
    src/energy_par.h
    src/hit.h
    src/rna_interaction_search.h
    src/seed_search.h
    src/db_construction.h
    src/fastafile_reader.h
    src/intloops.h
    src/rna_interaction_search_parameters.h
    src/ungapped_extension.h
    src/db_construction_parameters.h
    src/gapped_extension.h
    src/raccess.h
    src/encoder.h
    src/sais.cpp
    src/sais.h
)

# Name of the executable
add_executable(RIblast ${SOURCE_FILES})

# Install the binary
install(
  TARGETS RIblast
  DESTINATION bin
)