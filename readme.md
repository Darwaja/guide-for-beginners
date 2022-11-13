This is a guide aimed at non-programmers, or folks with little experience with computer programming
and give them a general tips, techniques & principles to follow. We won't bore you with tedious to
read text and instead jump straight in.

## Pre requisites
We expect the reader to be able to conduct searches for information on the internet. The ability to
read and write technical english is going to be very helpful, as most programming, and computer related
resources have thorough documentation written in English. 

Lastly, we also expect you to have the ability to ask proper questions. This is of the utmost importance,
as you will go into communities for help, being able to ask just the right question will get you the answer
quickest. This is a good thing to have in your arsenal, it will help increase your [hacker](https://en.wikipedia.org/wiki/Hacker_ethic) prowess.

#### Summary
- Be able to read/write technical English.
- Be able to lookup information.
- Have the patience and ability to read documentation thoroughly.

## Choosing a programming language
The first obvious step is to choose a programming language. We recommend starting with any of the following:

- Python
- Javascript
- Any Lisp

Many will inform you that programming language `xyz` is better, or language `abc` has this problem.
Don't fret, nothing is perfect. You have to start at some point using a language. Once you have 
taken the first step and mastered it, moving on is never going to be a problem. It is always the
first step that is seemingly difficult.

> Programmers, please see the [rationale][#Rationale_for_choices] section.

#### Summary
- Python
- Javascript
- Any Lisp

Choose any. You will be fine.

## How do I learn language `xyz`
Visit the language `xyz`'s website. Most websites have their own websites along with documentation
and resources for people to get familiar with it. I recommend reading books, or watching videos
only from sources recommended by the language's community. There are tutorial introductions
written by members of the community as well, so be sure to browse for them as well. 

The important thing is starting with something, and **sticking with it**. Do not give up on it.
Once you learn some basics, make sure to always write code. Write a project in it, or perhaps
do some exploratory programming.

#### Summary
- Browse official website's resources/wiki section.
- Stick with a particular tutorial, book, video/tutorial series.
- Practise what you learn.

## Environment
The environment refers to the tools, editors and the operating system you will be using while learning
and for development in the future. We recommend that you use any UNIX based operating system, such as
GNU/Linux distributions, popular ones are Debian, Pop_OS!, Arch Linux, Gentoo etc.
The reason for this is, the ability to get toolchains for some language with a single command and just
drop right into doing this. We believe that, development on windows is a bit harder than compared to these
distributions. If you're not willing to replace your current operating system, get a Virtual Machine, or dual
boot.

The Editor doesn't matter, as long as it can provide some basic text-editing features, it works. You can obviously
do a search on the internet to use a Integreted Development Environment (IDE) for any language. These are great
for newbies because once setup, it is a rock-solid environment where you can practise code.

#### Summary
- Get linux (in a VM or dual boot, if unfamiliar)
- Work in an Integrated Development Environment (IDE)

## Resources

- ### Python
1. [Beginner's Guide](https://www.python.org/about/gettingstarted/)
2. The [python wiki](https://wiki.python.org/moin/BeginnersGuide/NonProgrammers) has an exhaustive list of resources of each particular media form.

- ### Javscript
1. [Mozilla's mdn webdocs](https://developer.mozilla.org/en-US/docs/Web/javascript)
2. `Javscript(dot)com`'s resource [list](https://www.javascript.com/resources)

- ## Lisp
Lisp is a family of programming languages, whose most popular members are
- [Common-Lisp](https://common-lisp.net/)
- [Scheme](https://www.scheme.org/)
- [Racket](https://racket-lang.org/)
- [Clojure](https://clojure.org/index)

We recommend any and all of the above. 

Personal recommendations from one of the authors of this doc is:
- [Practical Common Lisp by Peter Seibel](https://gigamonkeys.com/book/)
- [Let Over Lambda](https://letoverlambda.com/)

These books are in order of experience, starting with no experience.

## Rationale for choices

- #### Memory management
The first reason for the choice of these languages was automatic memory management. As most newbie programmers
are unfamiliar with concept of pointers and manual memory management, C and C++ were immediately ruled out
as contenders.

- #### Simpler syntax
Languages such as python, javascript, or any language in the lisp family are of un-ambiguous syntax.
Readability of code in these languages is crucial so that newbs are not put off.

- #### Tooling and community
These languages have widespread communities on various platforms and have been in use for years to have
exhaustive tooling for things such as modules, libraries, compliers/interpreters that are reasonably fast.