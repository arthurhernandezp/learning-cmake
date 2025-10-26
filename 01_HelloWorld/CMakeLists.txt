# 0.) Create Source and CMakeFile
# 1.) mkdir build
# 2.) cd build
# 3.) cmake ..          -> Generate the build files / Configure the project
# 4.) cmake --build .   -> Gera o executavel
# 5.) ./app

cmake_minimum_required(VERSION 3.22)

project(
    CppProjectTemplate
    VERSION 1.0.0
    LANGUAGES C CXX)

add_executable(app main.cpp)
