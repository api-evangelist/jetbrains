---
title: "Async VFS Content Writes - What Plugin Authors Need to Know"
url: "https://blog.jetbrains.com/platform/2026/06/async-vfs-content-writes-what-plugin-authors-need-to-know/"
date: "2026-06-03"
author: "Jakub Chrzanowski"
feed_url: "https://blog.jetbrains.com/feed/"
---
The IntelliJ Platform now allows asynchronous disk writes through the Virtual File System (VFS), requiring plugin developers to update code that depends on synchronous file synchronization with external tools. The post provides technical guidance on the necessary code adjustments to ensure plugins remain compatible with the new VFS behavior.
