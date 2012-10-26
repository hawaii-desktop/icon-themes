Icon Themes
===========

Icon themes for the Hawaii desktop environment.

## Dependencies

There's no build-time dependency but you need the qtsvg module
in order to see icons in applications.

## Build

Building Icon Themes is a piece of cake.

Assuming you are in the source directory, just create a build directory
and run cmake:

    mkdir build
    cd build
    cmake -DCMAKE_INSTALL_PREFIX=/opt/hawaii ..

If not passed, the CMAKE_INSTALL_PREFIX parameter defaults to /usr/local.
You have to specify a path that fits your needs, /opt/hawaii is just an example.

## Installation

It's really, it's just a matter of typing:

    make install

from the build directory.
