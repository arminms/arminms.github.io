---
title: "Scalable Memory Allocation for Parallel Algorithms"
date: 2021-03-17T16:04:07-04:00
menu:
  sidebar:
    name: Scalable Memory Allocation
    identifier: sma
    parent: videos
    weight: 80
hero: images/p1000123.jpg
draft: false
---
#### I presented this webinar on March 17, 2021 as a part of a series of regular biweekly General Interest Webinars ran by [SHARCNET](https://sharcnet.ca).
---
{{< youtube 1UGwixrLQGU >}}

---
In a multithreaded C/C++ program, using standard non-threaded allocators, memory allocation can become a bottleneck. That is firstly caused by thread competition for a lock on a shared global heap, and secondly for caching effects. Programs that run this way are not scalable and may slow down as the number of cores increases. Scalable memory allocators such as Intel’s TBB allocators, FreeBSD’s jemalloc and Google’s TCMalloc solve this problem by providing various optimizations such as per-CPU caches, thread-private heaps, sized deletes and fast/slow path improvements. You can easily gain a 20-30% performance improvement for parallel sections and even 4X in extreme cases by simply relinking with a scalable memory allocator. This webinar will tell you all about these allocators, with a live session running some benchmarks at the end. Materials presented during the live session are available on [GitHub](https://github.com/arminms/scalable_allocators).