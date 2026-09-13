---
title: "Why Rider and ReSharper Were Slow to Start, and How Microsoft Helped Fix the Problem"
url: "https://blog.jetbrains.com/dotnet/2026/09/09/why-rider-and-resharper-were-slow-to-start-and-how-microsoft-helped-fix-the-problem/"
date: "2026-09-09"
author: "Alexander Ulitin"
feed_url: "https://blog.jetbrains.com/feed/"
---
When we launched ReSharper’s out-of-process (OOP) architecture, users reported slower startup times for IDEs using ReSharper on Windows. After profiling, the cause surprised us: Microsoft Defender was scanning our process for longer than we expected. This post is about what we found, what we learned working with Microsoft, and a tool we built that allows […]
