cmake_minimum_required(VERSION 3.20)
project(tg LANGUAGES C)

add_library(tg tg.c)
target_include_directories(tg PUBLIC .)