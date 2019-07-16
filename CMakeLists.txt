cmake_minimum_required(VERSION 3.13 FATAL_ERROR)


add_library( gfx_spirvheaders INTERFACE )
target_include_directories( gfx_spirvheaders INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include )