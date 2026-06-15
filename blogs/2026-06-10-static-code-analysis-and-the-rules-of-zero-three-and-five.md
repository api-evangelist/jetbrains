---
title: "Static Code Analysis and the Rules of Zero, Three, and Five"
url: "https://blog.jetbrains.com/qodana/2026/06/static-code-analysis-and-the-rules-of-zero-three-and-five/"
date: "2026-06-10"
author: "Kerry Beetge"
feed_url: "https://blog.jetbrains.com/feed/"
---
The Rule of Zero, Three, and Five, sometimes written 0/3/5, is a set of C++ guidelines about resource ownership and the special member functions. They exist because the alternatives are double-frees, dangling pointers, and silently broken copies. In this post we’ll work through the rules by tripping over each of those bugs in turn, then […]
