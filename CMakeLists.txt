cmake_minimum_required(VERSION 3.16)
project(Advanced_Programming_in_the_UNIX_Environment C)

set(CMAKE_C_STANDARD 11)


add_executable(Advanced_Programming_in_the_UNIX_Environment main.c error.c)

#add_executable(Advanced_Programming_in_the_UNIX_Environment main.c error.c log.c)
# You must to define and set log_to_stderr when using `log.c`.