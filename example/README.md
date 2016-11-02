# X-Plane SDK with CMake example
This is a basic plugin that shows how to use the X-Plane SDK CMake scripts. It's a quick way to get a plugin up and running without writing lots of boilerplate CMake, and tweaking linker settings to make your plugin load in X-Plane.

### How to build
This will build the example plugin:
```
mkdir build
cd build && cmake .. && make
```
You should have `mac.xpl`, `lin.xpl` or `win.xpl` in the build folder, ready to go.