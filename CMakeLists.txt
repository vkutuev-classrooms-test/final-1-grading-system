cmake_minimum_required(VERSION 3.7)
project(tests LANGUAGES C ASM)

set(CMAKE_C_STANDARD 99)

if (IS_DIRECTORY ${STUDENT_DIR})
    set(STUDENT_SOURCE_DIR ${STUDENT_DIR}/src)
endif()

