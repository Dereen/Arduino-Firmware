cmake_minimum_required(VERSION 2.8)
set(CMAKE_TOOLCHAIN_FILE C:/Users/cihal/Desktop/ArduinoProject/arduinoSoftware/cmake/ArduinoToolchain.cmake)
set(PROJECT_NAME Arduino_Firmware.ino)
project(${PROJECT_NAME})

set(${CMAKE_PROJECT_NAME}_BOARD uno)
set(${CMAKE_PROJECT_NAME}_PORT COM3)

set(${CMAKE_PROJECT_NAME}_SKETCH Arduino_Firmware.ino)
generate_arduino_firmware(${CMAKE_PROJECT_NAME})
