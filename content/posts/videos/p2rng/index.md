---
title: "p2rng – A C++ Parallel Random Number Generator Library for the Masses"
date: 2023-10-23T10:51:00-04:00
menu:
  sidebar:
    name: p2rng
    identifier: p2rng
    parent: videos
    weight: 130
hero: images/PXL_20220718_233206312.jpg
draft: false
---
#### I presented this webinar on October 18th, 2023, as a part of a series of weekly [Compute Ontario Colloquia](https://www.computeontario.ca/training-colloquia).
---
{{< youtube nyOH8nvHBss >}}

---
`p2rng` (https://github.com/arminms/p2rng) is a modern header-only C++ library for parallel algorithmic (pseudo) random number generation supporting [`OpenMP`](https://www.openmp.org/), [`CUDA`](https://developer.nvidia.com/cuda-zone), [`ROCm`](https://www.amd.com/en/graphics/servers-solutions-rocm) and [`oneAPI`](https://www.intel.com/content/www/us/en/developer/tools/oneapi/overview.html). Playing fair, mostly required for debugging and unit testing, is one of the unique features of `p2rng`. That means using the same seed and distribution you always get the same sequence of random numbers on all supported platforms. `p2rng` provides parallel versions of *STL*’s `std::generate()` and `std::generate_n()` algorithms with the same interface.
In this seminar we first start with a quick review of preliminary concepts about algorithmic random number generators in general and parallelization techniques in particular. Then we continue with the standard way of generating random numbers with *STL* algorithms and how we can turn them into parallel version using `p2rng`.
 