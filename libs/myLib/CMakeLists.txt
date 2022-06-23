project(cpp_lib-code-mylib CXX)

add_library(
        myLib
        STATIC

        src/MyCodeLib.cpp
)

target_include_directories(
        myLib PUBLIC ${CMAKE_SOURCE_DIR}/libs/myLib/include
)