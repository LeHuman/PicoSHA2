add_library(PicoSHA2 STATIC "picosha2.h" "picosha2.cpp")

set_target_properties(PicoSHA2 PROPERTIES LINKER_LANGUAGE CXX)