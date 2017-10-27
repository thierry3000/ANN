cmake_minimum_required(VERSION 2.6)


file(GLOB ANNLibFiles "*.cpp")
add_library(ann SHARED ${ANNLibFiles})

install(TARGETS ann LIBRARY DESTINATION lib)
