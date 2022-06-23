project(cpp_lib-code-thebin CXX)

add_executable(
        thebin
        src/main.cpp
)

target_link_libraries(thebin PRIVATE myLib)
