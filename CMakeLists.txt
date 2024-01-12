# Main make file of the project.
cmake_minimum_required(VERSION 3.20.0)

# Set Zephyr environment
find_package(Zephyr)
project(GT-Wheel)

target_sources(app PRIVATE ${SRC})
