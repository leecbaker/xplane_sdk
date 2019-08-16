# Necessary CMake
project(example_plugin CXX)
cmake_minimum_required(VERSION 2.8)

# Include the SDK. Adjust this path to wherever you have the SDK repository
add_subdirectory(../ bin/)

# Set up the plugin
add_xplane_plugin(example_plugin_xp10 210 example_plugin.cpp)
add_xplane_plugin(example_plugin_xp11 301 example_plugin.cpp)

