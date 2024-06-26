cmake_minimum_required(VERSION 3.29.3)

project("calulator")

add_subdirectory(lib)


include_directories(include)

add_executable(Myexe src/main.c)


target_link_libraries(Myexe MyLib)