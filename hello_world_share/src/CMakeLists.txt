
ADD_EXECUTABLE(main main.c)
INCLUDE_DIRECTORIES(../include/hello)

TARGET_LINK_LIBRARIES(main libhello.so)
