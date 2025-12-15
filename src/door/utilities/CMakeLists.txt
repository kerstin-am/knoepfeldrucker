add_library(
    utilities

    timespec.h
    timespec.cpp
    eventloop.h
    eventloop.cpp
    periodic-timer.cpp
    periodic-timer.h
    timer-expired.h
)

target_include_directories(
    utilities
    INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/../..
)
