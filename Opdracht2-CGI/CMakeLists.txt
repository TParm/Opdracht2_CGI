cmake_minimum_required (VERSION 2.6)
project (JSONEXAMPLE-CGI)
add_executable(JSONEXAMPLE-CGI jsonExample-cgi.c)
file(COPY ${CMAKE_CURRENT_SOURCE_DIR}/test.json
    DESTINATION ${CMAKE_CURRENT_BINARY_DIR})