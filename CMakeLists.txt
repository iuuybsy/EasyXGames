cmake_minimum_required(VERSION 3.27)
project(EasyXGames)

set(CMAKE_CXX_STANDARD 11)

include_directories(./EasyX/include)
link_directories(./EasyX/lib64)
link_libraries(libeasyx.a)

add_executable(EasyXGames main.cpp)