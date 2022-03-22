cmake_minimum_required(VERSION 3.19.0 FATAL_ERROR)

include(${CMAKE_CURRENT_SOURCE_DIR}/external_process/external_setting.cmake)
external_cmake_args()

add_subdirectory(ProjectBase)