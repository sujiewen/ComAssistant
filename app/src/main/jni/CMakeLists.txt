cmake_minimum_required(VERSION 3.4.1)

add_library(serial_port SHARED
            SerialPort.c)

# Include libraries needed for serial_port lib
target_link_libraries(serial_port
                      android
                      log)
