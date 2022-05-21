cmake_minimum_required(VERSION 3.20)

project(sample)

if(NOT "${CMAKE_CXX_STANDARD}")
  set(CMAKE_CXX_STANDARD 11)
endif()

message(":::::OK:::::")

message(":::::CMAKE_CXX_STANDARD=${CMAKE_CXX_STANDARD}:::::")
