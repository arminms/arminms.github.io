---
title: "How to Use C++ Parallel Algorithms in a Distributed Memory Setup (i.e. MPI)"
date: 2020-07-29T16:04:07-04:00
menu:
  sidebar:
    name: PGAS
    identifier: pgas
    parent: videos
    weight: 70
hero: images/p1010380.jpg
draft: false
---
#### I presented this webinar on July 29th, 2020 as a part of a series of regular biweekly General Interest Webinars ran by [SHARCNET](https://sharcnet.ca).
---
{{< youtube H1LGxHN7Bqk >}}

---
Last year and earlier this year, SHARCNET presented two webinars introducing C++17 parallel algorithms
([first webinar](https://youtu.be/BQpp8SaIrgE); [second webinar](https://youtu.be/yU645WpDcuM)).
There was an interesting frequently asked question: is it possible to use them in an MPI setup? This seminar tries to address that question. First, there will be a very short intro to C++17 parallel algorithms followed by an overview of Partitioned Global Address Space (PGAS) parallel programming model. Then, [DASH C++ template library](http://www.dash-project.org/) will be introduced. A live demonstration of installing and building programs with DASH concludes the webinar. You can find material presented during the live session on [GitHub](https://github.com/arminms/dash-tutorial).