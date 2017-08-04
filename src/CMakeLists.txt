cmake_minimum_required(VERSION 2.6)


file(GLOB ANNLibFiles "*.cpp")
add_library(ANN SHARED ${ANNLibFiles})

install(TARGETS ANN LIBRARY DESTINATION lib)
