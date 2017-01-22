cmake_minimum_required(VERSION 3.4.1)

add_library(system_0x81 SHARED
            system_0x81.c)

# Include libraries needed for hello-jnicallback lib
target_link_libraries(system_0x81
                      android
                      log)
