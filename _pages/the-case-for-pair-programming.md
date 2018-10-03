---
layout: default
title: The Case for Pair Programming
permalink: /the-case-for-pair-programming
---

# The Case For Pair Programming

<div class="border-t-4 border-indigo-dark w-24 mt-4 mb-8"></div>

_This is a guide for developers or managers who wonder if engaging in/allowing
pair programming might be right for them._

## In three sentences

1. Teams tend to ship slower over time because they accumulate sub-par code that impedes their progress.
1. A pair of programmers will tend to produce better code than someone working alone.
1. Teams that pair often will tend to maintain a fast shipping speed longer.


## In three paragraphs

A team that ships slowly almost always does so because it is fighting a sub-par codebase. It spends lots of time fixing bugs and regressions, and finds that changes ripple across the system in surprising ways, requiring deep exploration to make changes. Writing code that minimizes these problems is quite difficult.

Pair programming brings much more intellectual firepower to bear on this challenge. With two sets of eyes, bugs are caught earlier. With two brains to storm, more creative solutions can be found. With someone always watching, fewer corners are cut (and fewer distractions are indulged in).

Investing in higher-quality code through pair programming leads to a better codebase which allows future development to proceed faster.


## In three sections

### What actually slows down development?

The best way to answer this is to look at what teams that ship slowly spend a lot of time doing:

#### Fixing regressions

Slow teams often break previously-working features.

#### Fixing fresh bugs

Slow teams fail to cover all the edge cases in new functionality, and tend to discover them once they're "done" and in production.

#### Rewrites

Slow teams find their projects sink to a quality level where comprehension and changes become harder than throwing everything away and starting again.

#### Fighting bad architecture

Slow teams build on shaky foundations. When the architecture is discovered to be poor, they don't bite the bullet and fix it.

#### Being distracted

Slow teams are frequently distracted by meetings or pure slacking off.


### How can pair programming help?

#### Regressions

Regressions are preventable with a good test suite.

Most folks know they should be writing tests, but don't do it consistently.

In a pair, the level of testing trends towards the maximum of the two developers involved. A little social pressure goes a long way.

#### Fixing fresh bugs

Slow teams fail to cover all the edge cases in new functionality, and tend to discover them once they're "done" and in production.

#### Rewrites

Slow teams find their projects sink to a quality level where comprehension and changes become harder than throwing everything away and starting again.

#### Fighting bad architecture

Slow teams build on shaky foundations. When the architecture is discovered to be poor, they don't bite the bullet and fix it.

#### Being distracted



## The duality of code

In the normal course of events, every line of code you add to a project does two things:

1. Provides additional value to the project's users.
2. Makes the project harder to maintain and add to in the future.

A codebase is simultaneously an asset that provides value and a liability that requires maintenance and consideration during future development.

That last point is particularly important. Even with excellent engineering practices, it is difficult to write code that need not be considered when writing new features. 

Again: every line of code we write makes the next line harder. 

This brings us to an unfortunate conclusion:


## Shipping speed always slows down

Every project ships quickly in the beginning. 

There are no bugs to go back and fix, and very little context required to make changes.

But soon, things get worse. 

Bugs are discovered, changes in dependencies can force change on us, and adding new code requires understanding an ever-growing amount of context. Architectural decisions from years ago can impede current work.

Features that would have flown out the door in a brand new app can become death-marches.

Thus, our job as developers and managers is to maximize the value our code generates while minimizing its future costs.

Pair programming is particularly useful as a tool to accomplish the latter.


## How pair programming helps

### Fewer bugs

The easiest time to catch a bug is seconds after you wrote it.

I




## What slows down development?

A good way to answer this is to look at what teams that ship slowly spend a lot of time doing:

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

Pair programming mitigates all of the above.



