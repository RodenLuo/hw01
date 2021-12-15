add_library(stbiw STATIC stbiw.cpp)
target_include_directories(stbiw PUBLIC .)

target_compile_definitions(stbiw PRIVATE -DSTB_IMAGE_WRITE_IMPLEMENTATION)