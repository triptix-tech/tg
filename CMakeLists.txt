cmake_minimum_required(VERSION 3.20)
project(tg)

add_library(tg tg.c)
target_include_directories(tg PUBLIC .)

#if (MSVC)
#    set_source_files_properties(tg PROPERTIES LANGUAGE CXX)
#    target_compile_features(tg PRIVATE cxx_std_23)
#endif()