# esp32-code/components/lis3dh-esp-idf/components/esp8266_wrapper/CMakeLists.txt

idf_component_register(SRCS "esp8266_wrapper.c"
                       INCLUDE_DIRS "." 
                       REQUIRES "driver" "freertos")
