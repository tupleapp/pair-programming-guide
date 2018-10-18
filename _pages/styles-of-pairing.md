---
layout: default
title: Pair Programming Styles
permalink: /styles
---

{% include article-top.html %}

## Driver/Navigator

Probably the most common type of pairing. This is a good place to start if you're new.

The driver types the code and stays focused on the current task. 

The navigator thinks ahead, ponders edge cases, spots bugs, suggests refactorings, asks good questions, stays zoomed out.

Don't forget to switch roles regularly.

_(Coming soon: guides on driving and navigating well.)_

To see this style in action, check out [Pairing On Elixir, Phoenix, and Elm](/pair-programming-guide/elixir-phoenix-elm).

## Ping pong

This is a great option if you and your pair practice TDD.

You'll definitely want two keyboards for this one (or a remote pairing app like [Tuple](https://tuple.app)).

Here's the flow, looped until you're done:

1. Person 1 writes a failing test.
2. Person 2 makes it pass.
3. Person 2 writes a failing test.
4. Person 1 makes it pass.

This is a great option because the work is naturally divided, and there's no need to practice the discipline of swapping drivers often.

Three recommendations:

1. Sometimes it will take much longer to write the test than the code that makes it passes, or vice-versa. Don't worry about it. Time spent typing will even out over time.
2. Try to write a _minimal_ failing test, and the _smallest_ amount of code that will make it pass. This is easy to forget in the moment.
3. Don't forget to spend some time refactoring when things are green.

Want to see this style in action? Check out [TDD Ping-Pong Pairing](/pair-programming-guide/tdd-ping-pong).

## Strong style

This seems like madness, but we're including it here for completeness:

> The golden rule for this style of pairing is: "For an idea to go from your head into the computer it MUST go through someone else's hands"

[This article](http://llewellynfalco.blogspot.com/2014/06/llewellyns-strong-style-pairing.html) has more details.
