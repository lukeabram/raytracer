cmake_minimum_required(VERSION 3.15)
project(raytracer)
add_executable(rt 
    main.cc
)

target_compile_features(rt PRIVATE cxx_std_20)
