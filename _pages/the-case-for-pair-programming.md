---
layout: default
title: The Case for Pair Programming
permalink: /the-case-for-pair-programming
meta: An attempt to argue for the benefits of pair programming based on extensive personal experience.
---

{% include article-top.html %}

_This article focuses on an argument based on the author's extensive experience with development and pairing. If you'd like to read a summary of scientific studies conducted on pair programming, check out our [Scientific Research Into Pairing](https://tuple.app/pair-programming-guide/scientific-research-into-pair-programming) article._

## In three sentences

Teams tend to ship slower over time because they accumulate sub-par code that impedes their progress.

A pair of programmers tends to produce better code than someone working alone.

Teams that pair often will maintain a fast shipping speed longer.


## In three paragraphs

A team that ships slowly almost always does so because it is fighting a sub-par codebase. It spends lots of time fixing bugs and regressions, and finds that changes ripple across the system in surprising ways, requiring deep exploration to make changes. You can write code that minimizes these problems, it's just much harder.

Pair programming brings more intellectual firepower to bear on this challenge. With two sets of eyes, bugs are caught earlier. With two brains to storm, more creative solutions can be found. With someone always watching, fewer corners are cut (and fewer distractions are indulged in).

Investing in higher-quality code through pair programming leads to a better codebase, which allows future development to proceed faster.


## In three long sections

### What actually slows down development?

The best way to answer this is to look at what teams that ship slowly spend a lot of time doing:

* **Fixing regressions.** Slow teams often break previously-working features (without noticing it).

* **Fixing fresh bugs.** Slow teams fail to cover all the edge cases in new functionality, and tend to discover them once they're "done" and in production.

* **Fighting bad architecture.** Slow teams build on shaky foundations. When the architecture is discovered to be poor, they don't bite the bullet and fix it. 

* **Rewrites.** Slow teams find their projects sink to a quality level where comprehension and changes become harder than throwing everything away and starting again.

* **Being distracted.** Slow teams are frequently distracted by meetings and social media.

### How can pair programming help?

* **Regressions.** Regressions are preventable with a good test suite. Most folks know they should be writing tests, but don't do it consistently. In a pair, the level of testing trends towards the maximum of the two developers involved.

* **Fixing fresh bugs.** Bugs tend to hide in unconsidered edge cases. In a pair, one developer is explicitly tasked with thinking about these edge cases while the other types, increasing the chances they're handled properly.

* **Fighting bad architecture.** When every architectural decision is automatically considered by two people, teams will tend to find superior solutions.

* **Rewrites.** This might still happen, but with a higher quality bar, it'll be longer before it's necessary.

* **Being distracted.** Nothing like a person at your desk to break your Twitter habit. 


### How should we get started?

Check out our guide on [your first pairing session](your-first-pairing-session).

{% 
include navigation-buttons.html 
previous-title="All Content" 
previous-url="/pair-programming-guide/"
next-title="Your First Pairing Session"
next-url="/pair-programming-guide/your-first-pairing-session"
%}
