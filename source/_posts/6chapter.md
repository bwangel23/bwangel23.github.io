---
title: '6chapter.md'
date: 2016-04-10 10:56:54
tags: python_tdd
---

__摘要__: 这是一篇关于python_tdd的文章，主要介绍6chapter
<!-- more -->
完成最简可用的网站
==================

+ Django url的自动重定向

 在Django中，如果访问的url几乎正确，就是少了末尾的斜线，那么django就会返回一个301永久重定向，重定向到添加了末尾斜线的url。

+ 测试隔离和全局状态

 不同的测试之间不能相互影响，也就是说每次测试结束后都要还原所做的永久性操作。