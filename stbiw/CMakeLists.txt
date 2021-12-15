add_library(stbiw SHARED stbiw.cpp)

if (WIN32)
    target_compile_definitions(stbiw PUBLIC -D_WIN_EXPORT)
    target_compile_definitions(stbiw INTERFACE -D_IMPORTCTRLS)
endif()

target_include_directories(stbiw PUBLIC .)