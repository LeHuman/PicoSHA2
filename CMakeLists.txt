add_library(PicoSHA2 STATIC "picosha2.h" "picosha2.cpp")

target_include_directories(PicoSHA2 PUBLIC ".")

set_target_properties(PicoSHA2 PROPERTIES LINKER_LANGUAGE CXX)