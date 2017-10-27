cmake_minimum_required(VERSION 2.6)


file(GLOB ANNLibFiles "*.cpp")
#ubuntu calls its library in small letters
add_library(ann SHARED ${ANNLibFiles})

install(TARGETS ann LIBRARY DESTINATION lib)
