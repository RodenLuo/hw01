if (WIN32)
    set(CMAKE_WINDOWS_EXPORT_ALL_SYMBOLS ON)
endif()

add_library(stbiw SHARED stbiw.cpp)
target_include_directories(stbiw PUBLIC .)