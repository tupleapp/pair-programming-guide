---
layout: default
title: Scientific Research Into Pair Programming
permalink: /scientific-research-into-pair-programming
---

{% include article-top.html %}

Regrettably, there's not much. But here are the papers worth reading and sharing.

## [The Costs and Benefits of Pair Programming](https://collaboration.csc.ncsu.edu/laurie/Papers/XPSardinia.PDF)

The paper covers much of the existing research (and research-like artifacts, such as surveys).

From their abstract:

> Using interviews and controlled experiments, the authors investigated the
> costs and benefits of pair programming. They found that for a
> development-time cost of about 15%, pair programming improves design quality,
> reduces defects, reduces staffing risk, enhances technical skills, improves
> team communications and is considered more enjoyable at statistically
> significant levels.


## [The Case for Collaborative Programming](https://www.researchgate.net/publication/27295641_The_Case_for_Collaborative_Programming)

_Nosek, J. T. (1998)_

> A field experiment was conducted using experienced programmers who worked on
> a challenging problem important to their organization, in their own
> environments, and with their own equipment. **Findings revealed that all the
> teams outperformed the individual programmers, enjoyed the problem-solving
> process more, and had greater confidence in their solutions.**

Teams completed their task 40% _faster_ than the individuals (and this result
was statistically significant).

Studies in industry are rare, so this one is a nice find.


## Management Impact on Software Cost and Schedule

_Jensen, R. W. (1996)_

(No link available. Summary taken from [Pair Programming
Illuminated](https://www.amazon.com/Pair-Programming-Illuminated-Laurie-Williams/dp/0201745763A),
p. 35)

Regarding the performance of pairs vs individuals:

> Final project results were outstanding.  Total productivity was **175 lines
> per person-month (lppm) compared to a documented average individual
> productivity of only 77 llpm.**

> The error rate [&hellip;] was **three orders of magnitude lower than the
> organization's norm.** 

(Pairs had a defect rate _one thousandth_ of individuals&apos;. Holy crap!)


## [The Collaborative Software Process](http://www.cs.utah.edu/~lwilliam/Papers/ICSE.pdf)

_Wiliams, L. A. (2000)_

> An experiment was run in 1999 with approximately 40 senior Computer Science
> students at the University of Utah. Two-thirds of the students worked in
> two-person collaborative teams [&hellip;]. The other students worked
> independently [&hellip;] to develop the same assignments.  The productivity,
> cycle time, and quality of the two groups have been compared. **Empirical
> results point in favor of the collaborative teams [&hellip;].**

One key finding: the pairs took 15% more developer hours to produce their
solutions, but those solutions had 15% fewer bugs. 


## [Strengthening the Case for Pair Programming](https://collaboration.csc.ncsu.edu/laurie/Papers/ieeeSoftware.PDF)

_Williams, Kessler, Cunningham, Jeffries_

An easy read paper that summarizes some of the research above, as well as
providing supporting anecdotes from industry veterans.

The authors also summarize the results of the paper just above, [The
Collaborative Software
Process](/pair-programming-guide/scientific-research-into-pair-programming#the-collaborative-software-process):

> The pairs always passed more of the automated post-development test cases.
> Their results were also more consistent, while the individuals varied more
> about the mean. Some individuals didn’t hand in a program or handed it in
> late; pairs handed in their assignments on time. We attribute the pairs’
> punctuality to positive pressure the partners exert on each other. They admit
> to working “harder and smarter” because they don’t want to let their partner
> down.


<p class="text-sm pt-10">Do you know of any research into pair programming (with positive *or* negative results) that should appear here? Please <a href="https://github.com/tupleapp/pair-programming-guide/issues/new">open an issue</a>.</p>


{% 
include navigation-buttons.html 
previous-title="How To Pair With A Junior Dev" 
previous-url="/pair-programming-guide/how-to-pair-with-a-junior-developer"
next-title="Great External Resources"
next-url="/pair-programming-guide/links"
%}
