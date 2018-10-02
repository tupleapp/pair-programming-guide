---
layout: default
title: The Case for Pair Programming
permalink: /the-case-for-pair-programming
---

# The Case For Pair Programming

<div class="border-t-4 border-indigo-dark w-24 mt-4 mb-8"></div>

## A naive model of software development

It is tempting, but inaccurate, to think of software development like widget assembly:

1. We have a pile of widget parts.
2. We have a team of widget assemblers.
3. Each widget assembler can work independently, so doubling the number of widget assemblers doubles our throughput.
5. Once a widget is constructed, we ship it out and never think of it again.

It sure would be nice if software worked this way. If it did, our industry might not be plagued by late projects. 

**The biggest flaw in this model is that it leads to the conclusion that _work does not slow down over time_.**

Unfortunately, reality disagrees.


## A more accurate (and depressing) model

1. Our task is to build a single, extremely complicated widget.
1. Adding new pieces to the widget often breaks existing pieces.
1. Pieces tend to interact, thus each new piece makes future pieces harder to create.
1. Bad decisions made years ago can slow today's work tremendously.

In reality, **our project is doomed to slow down over time.**

Great teams slow down gradually, bad teams slow down quickly, but there is no escaping this gradual drop in productivity.

Your most important task as a developer or manager is to mitigate this slowdown.


## What slows down development?

The best way to answer this is to look at what teams that ship slowly spend a lot of time doing:

### Fixing regressions

Slow teams often break previously-working features.

### Fixing fresh bugs

Slow teams fail to cover all the edge cases in new functionality, and tend to discover them once they're "done" and in production.

### Rewrites

Slow teams find their projects sink to a quality level where comprehension and changes become harder than throwing everythnig away and starting again.

### Fighting bad architecture

Slow teams build on shaky foundations. When the architecture is discovered to be poor, they don't bite the bullet and fix it.

### Being distracted

Slow teams are frequently distracted by meetings or pure slacking off.


## The good news

