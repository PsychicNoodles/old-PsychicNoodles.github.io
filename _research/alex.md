---
title: 'Alex: AnaLysis of EXecution'
time: Summer 2018
link: /gh/alex
---

Alex is a software profiler for Linux programs that helps software developers
find performance issues with their program. In particular, hardware problems
such as caches and branch predictors can cause slowness or inefficiency and yet
are difficult to diagnose due to the relatively closed nature of hardware details.
What sets Alex apart is it allows users to hook into hardware events and counters
as well as records and displays data throughout the course of the program's
runtime, not just as a group of averages and call graphs.

Abstract:

> Identifying performance problems in code is crucial for software developers. Even small inefficiencies can incur large costs in complex, long-running systems. While programmers can tune their programs by using efficient algorithms and data structures, hardware resources such as caches and branch predictors can still be a major source of inefficiency. Such inefficient uses of hardware resources are rarely obvious in the program's source code.  
> During summer 2018, we developed a tool called AnaLysisof EXecution (ALEX) to help developers diagnose performance problems. ALEX gathers and displays performance data from unmodified programs run on GNU/Linux. Our visualization helps developers quickly find patterns of poor performance, and the accompanying analysis leads developers to the relevant source code. In our talk, we will demonstrate how ALEX can help developers, explain how it works, and discuss our summer research experience.