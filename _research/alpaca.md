---
title: 'Alpaca: Energy Profiler'
time: Summer 2017
link: /gh/alpaca
---

Alpaca is a software profiler that measures the energy consumption of a program's
individual functions. Target functions are analyzed, and their key actions, such
as writes to the heap and return value, are recorded. The function is then disabled
and the captured key actions are replicated. The ideal target function would be one
that has more computation than storage so that energy usage meaningfully gets
reduced by skipping instructions.