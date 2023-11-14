---
title: Foundational Techologies
date: 2023-06-27
---

SZ4 is under active development.  We hope to release our first version soon.  Here are some of the fundamental technologies that SZ4 will be built on:

# SZ3

SZ3 is a  modular error-bounded lossy compression framework for scientific datasets.
It provides low-level interfaces and abstractions for writing compressors.
You can find the code for [SZ3 on Github](https://github.com/szcompressor/SZ3), and you can install it with spack `spack install sz3`

# cuSZ

cuSZ is a version of SZ3 optimized for the NVIDIA GPUs and other GPU platforms.

You can find the code for [cuSZ on Github](https://github.com/szcompressor/cuSZ)

# LibPressio

Pressio is latin for compression. LibPressio is a C++ library with C compatible bindings to abstract between different lossless and lossy compressors and their configurations. It solves the problem of having to having to write separate application level code for each lossy compressor that is developed. Instead, users write application level code using LibPressio, and the library will make the correct underlying calls to the compressors. It provides interfaces to represent data, compressors settings, and compressors.  Compared to SZ3, it provides much higher level interfaces and abstractions.

You can find [LibPressio on GitHub](https://github.com/robertu94/libpressio), its [documentation on the web](https://robertu94.github.io/libpressio/), a [full tutorial](https://github.com/robertu94/libpressio_tutorial), extensive [example codes](https://github.com/robertu94/libpressio-interesting-scripts).  You can also install it via spack `spack install libpressio`

