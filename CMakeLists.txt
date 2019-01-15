cmake_minimum_required(VERSION 3.12)
project(esp8266_led C)

set(CMAKE_C_STANDARD 99)

add_executable(esp8266_led main/main.c)
