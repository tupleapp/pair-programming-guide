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

Unfortunately, reality is much more complicated.


## A more accurate (and depressing) model

1. Our task is to build a single, extremely complicated widget.
1. We will constantly guess wrong about how the widget should be built, requiring expensive changes.
1. Pieces of the widget tend to interact, so each piece we add makes adding the next one harder.
1. Bad decisions made years ago can slow today's work tremendously.
1. Every widget assembler we add to the team slows it down.
1. Widget assemblers are easily distracted, and are lucky to get four productive hours in per day.

**Notice the unfortunate takaway: work will slow down over time.** 

Great teams slow down gradually. Bad teams slow down fast. Everyone slows down eventually.


## What slows down development?

The best way to answer this is to look at what teams that ship slowly spend a lot of time doing:

### Fixing regressions

Slow teams often break previously-working features.

### Fixing fresh bugs

Slow teams fail to cover all the edge cases in new functionality, and tend to discover them once they're "done" and in production.

### Rewrites

Slow teams find their projects sink to a quality level where comprehension and changes become harder than throwing everythnig away and starting again.

### Being distracted

Slow teams are frequently distracted with meetings or slacking off.


## The good news

Pair programming mitigates 



## Bias alert

Our brains are poorly-equipped to take actions that pay off over the long run at the expense of immediate pain.

Everyone knows they should save for retirement, but the far-off pain of a destitute old age is dominated by the immediate reduction of disposable cash.

(what's the name of this bias?)
