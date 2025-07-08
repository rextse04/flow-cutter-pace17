cmake_minimum_required(VERSION 3.12)
project(flow-cutter-pace17)

set(CMAKE_CXX_STANDARD 26)

include_directories(./src)

file(GLOB pace_src CONFIGURE_DEPENDS "src/*.cpp")
add_executable(flow_cutter_pace17 ${pace_src})