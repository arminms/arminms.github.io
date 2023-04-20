---
title: "Dipping into C++17 Parallel Algorithms with Intel's Parallel STL"
date: 2019-02-27T16:04:07-04:00
menu:
  sidebar:
    name: Parallel STL
    identifier: parallel_stl
    parent: videos
    weight: 60
hero: images/p1010379.jpg
draft: false
---
#### I presented this webinar on February 27th, 2019 as a part of a series of regular biweekly webinars ran by [SHARCNET](https://sharcnet.ca).
---
{{< youtube yU645WpDcuM >}}

---
If you are programming or have already developed with C++, there is a good chance that you have used Standard Template Library (STL) containers and algorithms in your codes. In that case, you can easily boost the performance of your existing codes with parallel algorithms introduced in C++17. The good news is you do not have to wait until the support for the parallel algorithm is added to the C++ compiler of your choice. The Intel’s Parallel STL is a fairly complete implementation of the C++ standard library algorithms with support for execution policies, as specified in ISO/IEC 14882:2017 standard, AKA C++17. It is a standalone header-only library available for free on GitHub (https://github.com/intel/parallelstl). It can work with any C++11 compiler that works with Intel’s Threading Building Blocks (TBB), which is also available for free at https://www.threadingbuildingblocks.org/. In addition, if you want to use non-standard vectorization (unsequenced policies), your compiler should support OpenMP 4.0 SIMD constructs. Intel have offered to donate their implementation to both GCC and Clang.

This talk gives an overview of the C++17 execution policies, demonstrates how to use the Intel’s Parallel STL library on SHARCNET’s Graham cluster, and concludes with some benchmark results. 

Code examples: https://git.sharcnet.ca/asobhani/parallelstl_tutorial