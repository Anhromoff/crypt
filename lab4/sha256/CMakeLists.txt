cmake_minimum_required(VERSION 3.10)
project(sha256 C)

set(CMAKE_C_STANDARD 99)

add_executable(sha256 sha256.c sha256.h sha256_test.c)