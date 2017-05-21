# Value of code exercises (working title)

## Series

I'm going to go with the idea of a series, but my original post, which is good
and I want to use addresses the applicability concern. So, I'll need to come up
with a different part 3, because a series is not a series without at least 3
parts. Perhaps the Elixir-inspired version implemented in Ruby. I can always add
to the series later, but I want at least 3 parts to start with, so that I can
present them as a numbered list, just not yet linked up.

## Draft

One of the best and enjoyable ways to learn a new programming language is
through code exercises. [ Indeed, the popularity of exercism.io speaks to the
effectiveness and fun of learning coding this way. ]

It's not two kinds of code exercises, really, it's a spectrum, like everything
is. On one end of the spectrum, we have just getting the tests to pass. [ "Quick
green excuses all sins." ] But in the very next sentence he tells us: "But only
for a moment." In truth, just getting the tests to pass is often good enough
when learning a new language. But time invested in refactoring can pay huge
dividends.

- [ ] Get actual citation from Kent Beck's _Test Driven Development_.

The great part about this is that nobody is telling you what to do. Nobody is
giving you a deadline. You have total freedom. [ There's much more well-written
material on this subject below. ]

Code exercises are often [purposed] for learning a new programming language.
This has value. Success and utility of exercism.io speaks to this value.

But code exercises have a place in the expansion of our software design skills
as well. Code retreat, Corey Haines, Conway's Game of Life. It's not enough to
just get the tests passing.

Design exercise challenges: score along the way, no conditionals.

Although there is great value in unpacking the problem from scratch, walking
through it, in the interest of keeping this article a reasonable length, I'm
going to show you the end result and unpack the biggest takeways.

[ Insert gist ]

Qualities

Learning

Through this small code exercise we unearthed some big ideas. It is true that
good things come in small packages.

Address applicability to day-to-day work? Toys? [ Maybe a followup to this blog
post - failure of imagination. ]

## Outline

- Ideas about code exercises
- Bowling example
- What did I learn
- Future considerations
- Acknowledge:
  - One way to do this, not *the* way
  - Not unpacking how I arrived at this code

## Ideas to incorporate

- Design exercises are not the same as code exercises. Give yourself challenges.
  Examples.
- Perhaps just reveal the latest Ruby exercise. Follow up later with new games,
  Elixir, etc. Don't worry so much about the secret sauce. This is interesting
  work that I'm doing and I'd rather share it multiple times than not at all,
  even at the risk of losing a little bit of money over it. It might actually
  gain me money if the blog post works as an ad for the book.
- From previous draft remove: West End stuff, at least change 99B stuff if keep
  it at all.

## Draft

- [ ] Add stuff about spectrum of approaches to code exercises. Get the tests
  passing and move on. Refactor until you love the code and would not hesitate
  to ship it in a production app. (Often, I skip error handling, so my code,
  even when it's very well-factored, is not production ready. Hasn't considered
  security and error handling.)
- [ ] Introduction of constraints. Can be in part 2.

I've had the great good fortune to participate in Sandi Metz's POOD Course [
link ] both as student and co-instructor. The curriculum teaches object-oriented
programming principles and practices through a series of code exercises. Despite
being small and easy to understand, the code exercises impart a
disproportionately deep amount of learning (and teaching).

Yet, when the idea of small code exercises comes up amongst developers, almost
certainly someone will disparage them as toys and not relevant to the complex,
large codebases they inhabit for a living.

As programmers, we've come to expect complexity in our day-to-day jobs. We're
asked to solve formidable, hairy problems, and as if that isn't difficult
enough, it's often under unrealistic deadlines, working with code that we didn't
write, don't like, and cannot possibly understand quickly. It's no wonder that
developers used to these kinds of daily pressures, when sitting down to write a
greenfield solution to an easily-grokkable problem, see no relevance to their
day jobs. The experience feels too far removed from their daily work
experiences. But the absence of day-to-day work pressures and constraints is
precisely what makes working on code exercises valuable.

Programming is about decomposing and simplifying problems. When we work on
problems of modest size, that we solve from scratch, we focus our efforts around
this fundamental quality of programming. When we allow ourselves time explore
code exercises, we exercise our intellectual curiosity, free from the pressures
of time and free from the constraints placed upon us by building on top of code
we neither wrote nor conceived. Free to focus on simplicity and elegance, we can
craft solutions that follow the principles of clean code, that we know are good
and right, but that we so often, perhaps even habitually, eschew under
externally-imposed pressures. In other words, we are free to do our best work.

Without knowing our best work, we diminish our ability to apply it to larger
codebases and more complex problems. Much like building substantial LEGO
structures from small bricks, our larger codebases should be collections of
small, decoupled, reusable, flexible abstractions. They should be a collection
of the very kinds of solutions that we come up with when tackling small
problems.

But to extract full value from a code exercise, it's not enough to get the tests
passing and move on. It requires that we exercise the freedom to experiment and
the resolution to do our best work. It requires that we forget about the
time-to-market sensibility that guides our for-pay work, and simply play. While
practicing on a code exercise, when we ask ourselves, "What if?", we should feel
free and compelled to follow our intellectual curiosities.

Though I've framed this approach to exercise as play, and it is, it should also
be considered practice. The things we learn in practice are, of course, directly
applicable to our work when the pressure is on. An elegant solution we
discovered while experimenting with a code exercise may be a good fit for our
next work task. [ Good point, but improve wording: Without having played with
that elegant approach, we're likely to think of an inferior approach first, and
under pressure, the first thing we think of is often the most practical path to
follow. ]

A spirit of curiosity and inquiry likely attracted us to programming in the
first place.  Honor it by diving deep, pushing the boundaries of your knowledge,
and trying new approaches. A commitment to spending time on exploration and
practice is one of the the highest-yield investments one can make in improving
programming skills.

In the next article in this series, I'll put my money where my mouth is and walk
through a thoroughly decomposed solution to a well-known but sneakily complex
code exercise.

---

I'm not going out on a limb here, asserting that doing code exercises, much like
doing physical exercise, is beneficial. But to extract the full value of working
on code exercises takes a mindset change. We should allow ourselves the freedom
to push the boundaries of our knowledge by diving deep, by trying new
approaches, and by following the spirit of curiosity and inquiry that likely
attracted us to programming in the first place. I consider a commitment to
spending time on fun and practice one of the the highest-yield investments one
can make in improving programming skills.

But you don't have to take my word for it. Sandi Metz and Katrina Owen are
publishing a book [ link ] that takes a deep dive into a single, small code
exercise. I've been exposed to some of this content in the aforementioned POOD
courses [ link ] and I've read early drafts of the book. I think it will change
the way you write and think about code, and perhaps, the deep learning potential
of code exercises.

Doing small code exercises is one of the most valuable, deep learning
experiences we can give ourselves as a developers.

[ I've been hosting monthly West End Ruby meetups [ link ] for the better part of
six years. While I've always enjoyed them and received positive feedback from
attendees, the last few have been the best so far. Why? Because we've worked on
code exercises as a group. It has brought a renewed energy; we've hit our
attendee cap each of the past four months.

Despite the fact that I'm one of the more experienced developers in the group
and that I work on the exercise ahead of time, I've learned something at each of
these meetups. At first this surprised me, but shouldn't have, because it
underscores something I already knew, but perhaps didn't fully accept: doing
small code exercises is one of the most valuable, deep learning experiences we
can give ourselves as a developers. ]

[ Like practicing scales. Scales themselves are not songs, not compositions. They
are building blocks. Nobody wants to sit and listen to you practice scales. But
without knowledge of scales, nobody wants to sit and listen to you improvise on
anything because you simply won't have the knowledge, the musical vocabulary to
do it. The same is true for code exercises. In and of themselves, they're not
applications. They don't have externalized value. But they have tremendous value
as skill builders. By learning techniques through code exercises, you are able
to better build larger applications. And larger applications are a collection of
smaller pieces. If you think code exercises are toys because they don't have
enough code, I would wager that your production code has units (modules,
classes, methods, functions) that are too large. Decomposition enables
composition. ]
