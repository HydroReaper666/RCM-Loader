cmake_minimum_required(VERSION 3.4.1)
add_library( payload_launcher SHARED src/main/cpp/payload_launcher.cpp )
add_library( lakka_launcher SHARED src/main/cpp/lakka_launcher.cpp )
include_directories(src/main/cpp/)