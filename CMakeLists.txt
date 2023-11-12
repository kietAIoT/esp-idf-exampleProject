cmake_minimum_required(VERSION 3.16)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
set(EXTRA_COMPONENT_DIRS components/lora)
set(EXTRA_COMPONENT_DIRS components/led)
# add_subdirectory(components/led)
project(project2)
