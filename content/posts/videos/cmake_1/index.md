---
title: "Automating Software Build Process using CMake - Part I"
date: 2016-09-14T16:04:07-04:00
menu:
  sidebar:
    name: CMake - Part I
    identifier: cmake_1
    parent: videos
    weight: 20
hero: images/p1010039.jpg
draft: false
---
#### I presented this webinar on September 14, 2016 as a part of a series of regular biweekly General Interest Webinars ran by [SHARCNET](https://sharcnet.ca).
---
{{< youtube 7wxzoAdZcKE >}}

---
CMake is a cross-platform, free and open-source build system that allows you automatically build, test, verify, package and deploy software in a compiler-independent manner. CMake was originally created in 1999 for the Insight Toolkit (ITK) funded by the US National Library of Medicine (NLM) as part of the Visible Human Project and over the past 17 years has become the most popular build tool for C/C++ especially in the field of scientific research (e.g. medical computing, visualization, computer vision and HPC). Some notable applications that use CMake for their build process are: Qt, MySQL, Gromacs, Blender, OpenCV, VTK and ParaView.

CMake is designed to be used in conjunction with native build environments such as Unix Makefiles, Microsoft Visual Studio and Apple’s Xcode. The build process is controlled by creating one or more configuration files (called CMakeLists.txt files) in each source directory (including subdirectories) that make up a project. Each CMakeLists.txt consists of one or more commands. One of the key features of CMake is the ability to build a directory tree outside the source tree, hence, in case the build directory is removed, the source files remain unaffected. CMake can generate makefiles for many platforms and IDEs including Unix, Windows, Mac OS X, OS/2, MSVC, Unix Makefiles, Ninja, Cygwin, MinGW, NMake, Xcode, CodeBlocks, CodeLite, Eclipse CDT and even Sublime Text.

This talk will introduce CMake and go over the basics of using CMake on both user computers and SHARCNET systems to configure and build software. Basic steps of developing a working CMakeLists.txt for a sample software project will also be covered. Some programming experience is helpful but not mandatory.
