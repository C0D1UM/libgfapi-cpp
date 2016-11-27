# libgfapi-cpp
Modern C++ bindings for GlusterFS libfapi

Gluster's `libgfapi` is a collection of C API which allows developers to increase I/O performance by skipping its FUSE layer and directly accessing the bricks. However, due to its C API nature, this could be error prone for those C++ developers more comfortable with RAII, object-oriented paradigm. The objective of this library is to provide a C++ wrapper using modern C++ features which promote:
- Type safety
- RAII
- High performance
