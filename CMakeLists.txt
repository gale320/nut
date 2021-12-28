cmake_minimum_required(VERSION 3.16)
project(nut C)

include(cmake/option.cmake)


include_directories(include src/core src/utils src/lib src/nutlog src/port src/script src/plugin)


add_subdirectory(src)
add_subdirectory(app)
add_subdirectory(test)




