cmake_minimum_required(VERSION 3.0.0)

set(CMAKE_TOOLCHAIN_FILE "${CMAKE_SOURCE_DIR}/generic-avr-gcc.cmake")

project("Keyboard Firmware" VERSION 0.0.1)

# include(CTest)
# enable_testing()

add_subdirectory(src)

# set(CPACK_PROJECT_NAME ${PROJECT_NAME})
# set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
# include(CPack)
