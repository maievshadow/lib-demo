cmake_minimum_required (VERSION 2.6) 
#link_libraries(${PROJECT_SOURCE_DIR}/lib)
include_directories(/usr/local/include/hello)
add_executable(Main
    main.c
)
target_link_libraries(Main hello)