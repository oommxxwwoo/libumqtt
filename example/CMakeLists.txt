include_directories(${CMAKE_SOURCE_DIR}/src ${CMAKE_SOURCE_DIR}/src/buffer ${CMAKE_BINARY_DIR}/src)

add_executable(example example.c)
target_link_libraries(example umqtt ${LIBEV_LIBRARY})
