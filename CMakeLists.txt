
cmake_minimum_required(VERSION 3.12)
project (MyProject VERSION 1.0.0)

add_library(
  say_hello
  hello.hpp
  hello.cpp
  )
  
  add_executable(howtoCMakeGood-1a-A main.cpp)
  target_link_libraries(howtoCMakeGood-1a-A PRIVATE say-hello)
  
