cmake_minimum_required(VERSION 3.4.1)

project(hello_headers)

# file(GLOB SOURCES "src/*.cpp")
# set(SOURCES 
#     src/Hello.cpp
#     src/main.cpp
# )

add_executable(${PROJECT_NAME} ${SOURCES})

target_include_directories(${PROJECT_NAME} PRIVATE ${PROJECT_SOURCE_DIR}/include)

# target_include_directories(hello_headers
#     PRIVATE 
#         ${PROJECT_SOURCE_DIR}/include
# )