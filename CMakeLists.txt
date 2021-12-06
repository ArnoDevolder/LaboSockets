cmake_minimum_required(VERSION 3.10)
# set the project name
project(HTTPserver)
#add the libraries
link_libraries(libtlpi.a)
link_libraries(PJ_RPI)
# add the client executable
add_executable(HttpS http_server.c)


