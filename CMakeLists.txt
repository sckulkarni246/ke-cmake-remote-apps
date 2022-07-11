cmake_minimum_required(VERSION 3.23.1)

set(REM_SRCS "")

set(REM_SRCS ${REM_SRCS} ${CMAKE_CURRENT_SOURCE_DIR}/remote_hello_world.c)

set(SRCS ${SRCS} ${REM_SRCS} CACHE STRING FORCE))
