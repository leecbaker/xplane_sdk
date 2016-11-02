# X-Plane SDK

This repository contains the X-Plane SDK as downloaded from [here](http://www.xsquawkbox.net/xpsdk/mediawiki/Download), along with some scripts that I use for creating plugins.

### How to use
Add this repository as a submodule of your repo:
`git submodule add https://github.com/leecbaker/xplane_sdk`

Initialize the submodules:
`git submodule init && git submodule update --recursive`

Add this submodule to your CMakeLists.txt:
```
add_subdirectory(xplane_sdk)
add_xplane_plugin(your_plugin_name your_plugin_file1.cpp your_plugin_file2.cpp)
```

Start your build, and that should be it! There's an example plugin in example/ that you can reference to see how it works.
