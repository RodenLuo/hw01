add_library(stbiw INTERFACE)
target_include_directories(stbiw INTERFACE .)

target_compile_definitions(stbiw INTERFACE -DSTB_IMAGE_WRITE_IMPLEMENTATION)