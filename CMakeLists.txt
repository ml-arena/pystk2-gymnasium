# Wrapper CMakeLists.txt for pystk2-gymnasium
# This includes the pystk2 build from pystk2_build subdirectory

cmake_minimum_required(VERSION 3.15)
project(pystk2-gymnasium)

# Add the pystk2_build subdirectory which contains the actual SuperTuxKart build
add_subdirectory(pystk2_build)
