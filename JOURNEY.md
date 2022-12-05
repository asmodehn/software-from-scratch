# The Journey

This is a rough Map of programming languages based on my personal experience.
With the hope it can help guide some newcomers into the vast software science available out there.

We focus on standard, or largely popular generalist programming languages.
Theory understanding would help, but our guideline is practical existing languages in which students can code what they want (games, robots, etc.)
Also, as this is educative, it is important we use free software resources, so all information is available online.

Once the concepts are well understood through extensive practice, 
Reading science papers and source code for a DSL should be enough to grasp another concept or understand another language. 

Legacy:

- NetBSD + pkgsrc : Pick the hardware you like.

- PDP/11 arch + C. + vi  => But how do we configure things ?
check https://www.gnu.org/savannah-checkouts/gnu/autoconf/manual/autoconf-2.71/autoconf.html#Why-Not-Imake

- shell programming + autotools  => but this is a lot of information. How about some theory to try and simplify things

- lambda calculus + scheme(guile) + emacs => but wait, side-effects are not "pure" functions ? and what about immutability ?

- GUIX: functional package management.

There are three perspectives we need to keep in check:
- How the world works, numbers, arithmetics, algebra, etc. ie. the **Theory**.
- How the technology works: what we can do with what we have, at a moment in our human history, ie. the **Tech**.
- How we Humans intuitively think, as a majority, since we are the ones doing the programming, ie the **HBrain**.
  Note one's personal interpretation of this last one can differ a lot, person to person, depending on the education one has received so far.

Each of us will hold one of these perspective as less intuitive or interesting as the others.
Therefore, depending on the two most important prspectives, a path can be chosen.

# A fork in the road

## Theory + HBrain
- scheme + Racket => Ok nice but it can be hard to keep everything in one's head
- OCaml => Yeah but ...
- Haskell, and more...

## Theory + Tech
- Forth => Ok thats fine, but what about the network ?
- Erlang => Useful, but the VM is still in my way...
- Rust, Julia => Oh nice.


# HBRain + Tech: Popular technology comes at the price of choice

- Close to the Metal : C++
- Cross-platform: Java
- Interactive scripts: Python (REPL)
 
=> Object Oriented Programming is powerful, but all the design patterns and philosophies lead back to functional design!

At this stage one already knows how to program in various ways... 

Therefore the individual interest seem to be the important aspect to keep in mind, in order to guide further into our exploration:

## Batch Development

Developing a program that does a task and exits is a specific kind of software, algthough the most common.

- Speed: Python is arguably currently the best in this area. Prototyping with it is very fast.
- Safety: Rust is arguably currently the best in this area. Large set of bugs can be avoided, while keeping high performance, close to the metal
- Understanding: Julia is arguably currently the best in this area. because it provides clear and functional programming environment.

##  Continuous Development : This is still quite a small area

Before there was REPLs, but it has been mostly used for experimentations, as it was usually too limited  to build large programs.
Things are changing slowly though:
- Python with IPython augmented repl
- Julia with a multi-layer repl.
- Smalltalk with a full windowed development environment.

Contenders are programming environment with "interactive web environments":
  - Python with Jupyter (largely used, but prone to more problems than other solutions)
  - Julia with Pluto (quite niche for sciences, but functional environment yet close to the metal)
  - Elixir with Livebook (on top of Erlang VM, simplified code, but on top of a VM)




