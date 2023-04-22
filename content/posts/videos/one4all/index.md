---
title: "CUDA, ROCm, oneAPI – All for One or One for All?"
date: 2023-04-21T16:04:07-04:00
menu:
  sidebar:
    name: CUDA, ROCm, oneAPI
    identifier: one4all
    parent: videos
    weight: 110
hero: images/p1030224.jpg
draft: false
---
#### I presented this webinar on April 19th, 2023, as a part of a series of weekly [Compute Ontario Colloquia](https://www.computeontario.ca/training-colloquia).
---
{{< youtube RYtdiOhrv0Q >}}

---
For a long time, CUDA was the platform of choice for developing applications running on NVIDIA’s GPUs. That is starting to change in recent years with the introduction of AMD’s ROCm and Intel’s oneAPI which both support GPUs by other vendors. While ROCm targets both AMD and NVIDIA GPUs, using the recently released drivers by CodePlay, oneAPI applications can run on NVIDIA and AMD in addition to Intel’s GPUs. The question this seminar is trying to answer is if in 2023 you want to start a project targeting GPUs, what would be your platform of choice? Should you go with one or all of them? Later in the seminar, a boilerplate framework named [one4all](https://github.com/arminms/one4all) will be introduced that streamlines the process of developing applications targeting all the above platforms. Unit testing with Catch2 as well as benchmarking with Google benchmark are already supported by the framework.
