cmake_minimum_required(VERSION 3.22)
set(BOARD rpi_pico)

find_package(Zephyr)
project(Dhruv_01)

target_sources(app PRIVATE src/main.c) 
