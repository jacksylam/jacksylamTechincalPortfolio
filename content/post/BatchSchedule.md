---
title: "Online Batch Scheduling Simulator"
showDate: False
thumbnailImage: "/img/batchschedule.jpg"
thumbnailImagePosition: left
metaAlignment: center
coverMeta: out
date: 2017-12-28

---
This was a group project to build an Online Batch Scheduling Simulator to study the performance of various algorithms.

<!--more-->

Our system simulates a compute cluster of available nodes and will allocate nodes to received jobs. In addition, our system is able to import real world data of submitted jobs from high performance computing centers from http://www.cs.huji.ac.il/labs/parallel/workload/

The algorithms we investigated were First-In-First-Out, Backfill, EASY, Shortest Processing Time First, Largest Processing Time First, Random, and Balanced Spiral Backfill. The metrics we used to evaluate the various algorithms include wait time, slowdown, and sparsity.

![](/img/batchschedule.jpg)


For more information, visit our GitHub at https://github.com/gregorylburgess/Batch