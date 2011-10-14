cmake_minimum_required(VERSION 2.8)

PROJECT (HELLO)
ADD_SUBDIRECTORY(src)

INSTALL(FILES COPYRIGHT README DESTINATION share/doc/cmake/hello_world_out)
INSTALL(PROGRAMS runhello.sh DESTINATION bin)
INSTALL(DIRECTORY doc/ DESTINATION share/doc/cmake/hello_world_out)


