cmake_minimum_required(VERSION 3.7)
project(VehicleRoutingwithSplit)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
#        main.cpp
#        Program
        commandline.cpp
        commandline.h
        main.cpp
        Pb_Data.cpp
        Pb_Data.h
        Split.h
        Split_Bellman.cpp
        Split_Bellman.h
        Split_Bellman_Bounded.cpp
        Split_Bellman_Bounded.h
        Split_Bellman_Soft.cpp
        Split_Bellman_Soft.h
        Split_Linear.cpp
        Split_Linear.h
        Split_Linear_Soft.cpp
        Split_Linear_Soft.h
        Trivial_Deque.h
        Split_Linear_Bounded.cpp
        Split_Linear_Bounded.h
        )
add_executable(VehicleRoutingwithSplit ${SOURCE_FILES})