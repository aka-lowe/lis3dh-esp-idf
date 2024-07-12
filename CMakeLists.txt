# esp32-code/components/lis3dh-esp-idf/CMakeLists.txt

cmake_minimum_required(VERSION 3.16)

# Include the ESP-IDF build system
include($ENV{IDF_PATH}/tools/cmake/project.cmake)


# Register the components within lis3dh-esp-idf
add_subdirectory(components/esp8266_wrapper)
add_subdirectory(components/lis3dh)
