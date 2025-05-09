cmake_minimum_required(VERSION 3.7)
project(
    HelloApp
    VERSION 0.0.1
    DESCRIPTION "The loading Hello World program"
    LANGUAGES CXX
)
add_executable(HelloAppBinary main.cpp)
target_compile_features(HelloAppBinary PRIVATE cxx_std_23)