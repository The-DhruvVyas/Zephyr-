cmake_minimum_required(VERSION 3.22)
find_package(Zephyr)
set(BOARD esp32_devkitc_wrover)

project(Dhruv_ssd1306)

target_sources(app PRIVATE src/main.c)