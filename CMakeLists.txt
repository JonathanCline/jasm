cmake_minimum_required(VERSION 3.8)

project(jasm)


set(lib_cxx 20)



add_executable(${PROJECT_NAME} "${PROJECT_NAME}.cpp")
target_compile_features(${PROJECT_NAME} PUBLIC cxx_std_${lib_cxx})
