cmake_minimum_required(VERSION 3.25)
set(CMAKE_CXX_STANDARD 17)
project(validate_time)



file(GLOB SOURCES *.cpp *.h)
add_executable(${PROJECT_NAME} ${SOURCES})
target_link_libraries(${PROJECT_NAME} PUBLIC pthread )
