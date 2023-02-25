project(test_project)

add_executable(test_project main.cpp)

find_package(unofficial-recast CONFIG REQUIRED)
target_link_libraries(test_project PRIVATE recast)
