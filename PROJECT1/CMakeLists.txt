cmake_minimum_required(VERSION 3.14)
project(Project1)

# Include directories for header files
include_directories(src)
include_directories(testing)

# Add subdirectories for src and testing
add_subdirectory(src)
add_subdirectory(testing)

# Custom target to compile src
add_custom_target(src
    COMMAND ${CMAKE_COMMAND} --build ${CMAKE_BINARY_DIR}/src
    COMMENT "Compiling src"
)

# Custom target to compile tests
add_custom_target(tests
    COMMAND ${CMAKE_COMMAND} --build ${CMAKE_BINARY_DIR}/testing
    COMMENT "Compiling tests"
)