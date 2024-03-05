cmake_minimum_required(VERSION 3.12 FATAL_ERROR)

set(ProjectName "ClientServerApp")

project(${ProjectName})

add_executable(
  ${ProjectName}
  server.cpp
  client.cpp
)

set_target_properties(
  ${}
  PROPERTIES
  CXX_STANDARD 17
  CXX_STANDARD_REQUIRED ON
)
