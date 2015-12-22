# A Postwork Confessional

> Brit Butler, TIY Atlanta
>
> August 16th, 2015

My dearest students, y'all, congratulations.

First of all, I'm proud of your hard work and how far you've come.
But you probably knew that. Keep being patient with yourselves,
curious about the magic of computing, and respectful of your peers.

## Now What?

Keep in mind the following:

1. Your focus should probably be the job hunt,
   marketing yourself (i.e. portfolio), and
   improving your Ruby/Rails chops for a bit.

2. As graduates of this course, my door is always open to you.
   I'll respond to emails and slack messages as best I'm able.
   I'm also happy to help you dig into new topics that interest you.

3. Keep learning and be wary of impostor syndrome.
   You'll never know it all, neither will anyone else, and that's good.

## Disclaimer

What comes out of my mouth is not gospel.

I'm going to suggest some things to look into to broaden your horizons over
the next **year or two**. These things are a bit open ended and are colored
by my own biases and background. I'll try to point out where my preferences
are influencing suggestions.

Whatever your goals, I hope you have a discovered a love for programming.
Don't view the below as an exhaustive task list to complete, look at it as
a jumping off point to interesting destinations and adventures. **Do what interests you.**

There are three broad categories I'll group these suggestions into:

> R) Keep **reinforcing** your backend/web-dev chops.
>    * Write more Rails apps, practice unit testing, dip your toes in ops or frontend.
>
> F) Work on your **fundamentals**.
>    * Take the magic out of programming, master scoping and evaluation.
>
> P) Gain a greater appreciation for programming **paradigms** and new languages.
>    * What does it mean to do Object-Oriented or Functional Programming and why do we do it?

They all share one commonality: You'll learn the most by getting your hands dirty. :)

## The Confession

I have not historically been very interested in web development.
I got into a career making web apps mostly by accident.

I have always been driven by a curiosity about how computers work,
why they do the things they do, and how to get them to behave differently.

The good news is that with a solid understanding of the fundamentals,
I could apply that knowledge to web apps in a straightforward manner.

Think back to every time you were impressed by my speed debugging a problem
you'd spent an hour staring at. I attribute my ability to do this not to
tons of experience with Ruby and Rails but to many hours spent working on
simple programs and thinking about the *fundamentals*.

The big controversial belief I'm arguing for is this:

    For about the next year, you'll get as much benefit from
    sharpening your fundamentals as writing another Rails app.

If you think about it, the main time we had to focus on the "fundamentals"
were the first 2-3 weeks of the course. After that, we got wrapped up in
web apps and MVC. Now, don't get me wrong, MVC is great. But when you see
a new problem, I'd prefer you not to first think "How do I break this into
a model, controller, and view?"

The more you can broaden your horizons, the more ways you can think of to
break up and decompose problems, the better off you'll be. Seeing everything
through the lens of MVC and Rails limits your view. Keep learning more
about Rails but don't forget to learn things that might not seem
immediately applicable to your career.

Anyway, enough about that. I'll get off my soap box.

## Suggestions

I'm going to group these suggestions by a rough order. Some of them are
things you should pursue immediately, others will be most helpful to you
a good deal later.

In the end, run towards what excites you.

### 1-3 months post-graduation

At this point, you'll primarily be focused on practicing what you've already learned
and finding paid work. Rather than showing you *entirely* new concepts, this period is
about reinforcing and building on your knowledge.

#### Book: POODR (R, F, and P!)

First and foremost, *please, please, please* read
[**Practical Object-Oriented Design in Ruby**][poodr] by the fantastic Sandi Metz.
It's worth reading through twice, it's cheap ($30), and it has the wonderful benefit
of ticking off all my boxes:

  * It builds on and reinforces your existing knowledge of plain old Ruby.
  * It isn't focused on Rails apps, it's focused on *fundamentals*, good problem solving,
    decomposition, and how to write **elegant, good code**.
  * It will greatly deepen your understanding of the whys and hows of Object Orientation.

[poodr]: http://www.poodr.com

#### Book: Objects on Rails (R, P)

I lack a religious fervor about this, but try reading Avdi's [Objects on Rails][oor].
It's insanely cheap ($5) and shows how to apply OO Design to an example Rails app.

It will help you critically think through how you write Rails apps and the book walks
you nicely through Avdi's thought process including testing! On the down side, the
versions of Ruby and Rails used are a *wee* bit old and Avdi's style is slightly unusual.
That said, there's much to learn here.

[oor]: http://objectsonrails.com/

#### Project: Unit Testing Practice (R)

Go back and try to write a tested, terminal version of checkers or the todo list app.
Write some tests for your final project if you haven't.

Use minitest or follow along with a blog that teaches testing with Rspec. The important
thing is to get reps and become comfortable with thinking about how to test code.

#### Smorgasborg (R)

There are countless other useful resources that are worth taking a swing at if you're looking
for ways to practice keeping your skills fresh. Here are a few:

* Complete the [Ruby Koans](http://rubykoans.com/) (ruby, testing)
* Complete Michael Hartl's [Rails Tutorial](https://www.railstutorial.org/) (rails)
* The awesome [Justin Herrick][jah] at TIY Austin wrote a [Final Assessment][final].
  Take it! (and hit me up if you're stuck or unsure about anything)
* Might be good to sign up for [exercism.io](http://exercism.io) and just do a half
  dozen problems every day or two.

[jah]: https://twitter.com/jah2488
[final]: https://github.com/tiy-austin-ror-jan2015/postwork/blob/master/FinalAssessment.pdf

### 3-6 months post-graduation

At this point you should be employed (hopefully happily!) in the tech industry.
It is totally reasonable at this point to just be keeping up with your job and
enjoying some well deserved rewards. If you want to broaden your skills,
here are a few night projects worth looking at.

#### Book: SICP (Chapters 1 and 2) (F)

[SICP][sicp] is the book that got me started on programming. If you'll excuse the
appeal to authority, just google about it and see how many best programming books
lists it pops up on! Even in the last week when one of my favorite hackers,
[Luke Gorrie tweeted about it][books-tweet]. Oh, and here's a
[glowing endorsement of SICP][sicp-review] from Google's Director of Research.

I have to admit I haven't finished SICP. I only read Chapters 1 and 2. SICP is pretty
challenging but I cannot think of a better source for getting comfortable with the
fundamentals of computation. It's free online and there are countless resources (including
[MIT's video lectures][sicp-lectures]) for it. Additionally, I'm happy to give feedback or
suggestions if you get stuck. You'll also want a version of Scheme to work through the exercises.
Try [Racket][racket].

Just after Chapter 1 a substantial amount of *magic* will disappear from the code around you.
And in Chapter 2 you'll see how you could add Classes and Objects to a language that doesn't
have them! If you're brave enough to proceed to chapters 3, 4, and 5, you'll get a taste of
the logic programming paradigm and then even build your own language and compiler!

**NOTE**: Try doing some of the exercises, but don't commit to doing **every single one** like
I did. Getting exposed to the ideas is the most important thing, do a few exercises each section
to grasp the material better.

[books-tweet]: https://twitter.com/lukego/status/632450443566780416
[sicp-review]: http://www.amazon.com/review/R403HR4VL71K8/ref=cm_cr_dp_title?ie=UTF8&ASIN=0262510871&channel=detail-glance&nodeID=283155&store=books

[sicp]: https://mitpress.mit.edu/sicp/
[sicp-lectures]: http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/
[racket]: http://racket-lang.org

#### Book: Eloquent Javascript (At least Chapters 1-6) (R+)

[Eloquent Javascript][elojs] is written by an incredible hacker, [Marijn Haverbeke][marijn].
It is, in my opinion, the best current book for learning Javascript from scratch. Better yet,
it's free. Being knowledgeable about both Ruby and JS is a *huge* buff to your resume. While
the first 6 chapters teach you the core of Javascript, it's chapters 12 through 9 that teach
how it interacts with the browser and how to meaningfully use it in web apps. If you have
the time and energy to read the whole thing, you'd be wise to do so!

[elojs]: http://eloquentjavascript.net/
[marijn]: http://marijnhaverbeke.nl/

#### Project: Add some styling/JS to your homepage (R)

You should all already be building portfolio sites to help market yourself and aid in
the job hunt. Spend a little time trying to understand or modify the styling with bootstrap
or materialize. Or add some interactive elements to the page with Javascript, even if it's
just a spinning tilde! Just being able to do decent layout and markup is a big win.

### 6+ months post-graduation

At this juncture, you are hopefully settled comfortably at a job you enjoy,
learning and challenged but "beyond the terror". At this point, you may want
something different and weird to play with at night to explore the wide world of code.

It's around this point that it would be reasonable to start playing with a new
programming language or two. Here are a few suggestions...

#### Book: Functional Programming in Scala (P)

There is no easy road to a completely new programming paradigm. Everything will
seem alien at first but that's good. It's the sound of your brain stretching.

I think an excellent place to start is [Functional Programming in Scala][fps] and my friend
[Paul Snively's review][psr] speaks to why. It's a bonus that Scala is ultimately a
hybrid Object/Functional language and that its usage in industry is growing.

If you're still hooked and want more after that, maybe get a look at programming in a
more dedicated Functional language and read Real World Ocaml or Real World Haskell.

[fps]: http://www.amazon.com/Functional-Programming-Scala-Paul-Chiusano/dp/1617290653
[psr]: http://www.amazon.com/review/R8P9W8Z7QXLWW/ref=cm_cr_dp_title?ie=UTF8&ASIN=1617290653&channel=detail-glance&nodeID=283155&store=books

#### Project: Read Some Good Code (R, P)

This is one I feel compelled to include but I don't have particular code to recommend.

I may package up a mailing list that's disappeared from the net called "kragen-hacks".
It was a great source of small, interesting programs (often in Python) that were well
explained by the author.

It would be worthwhile to watch [this RailsConf talk][rgc] and browse [their site][rcg]
or [awesome-rails][a-rails] for interesting projects to try reading. Try to rope in
some other students for a reading group!!!

If you are looking for some interesting non-ruby code bases to read, well ...
I'm working on building up a good list in my spare time. And I can definitely
make some lisp recommendations. Hit me up! :)

[rgc]: https://www.youtube.com/watch?v=mW_xKGUKLpk
[rcg]: http://www.readingcodegood.com/
[a-rails]: https://github.com/ekremkaraca/awesome-rails

#### Book/Playground: Smalltalk Best Practice Patterns (P)

If you're interested in a deeper dive after POODR, I would recommend playing with
[Pharo Smalltalk][pharo] and perhaps reading Kent Beck's famous
[Smalltalk Best Practice Patterns][sbpp]
which is purported to be one of the best exemplars of OO Design, regardless of what language you're using.

[pharo]: http://pharo-project.org
[sbpp]: http://devblog.avdi.org/2011/09/20/sbpp-1-introduction/

#### Smorgasborg (P+)

Here's a scattering of other excellent texts, mostly with a stronger CompSci bent if
you want to get deeper into specific areas.

Read **good** code, thoughtfully and carefully explained, meditate on software *design*:
* Thinking Forth
* Paradigms of AI Programming (see [this review][paip-review])

Learn about Algorithms for that R&D position you've been wanting:
* (read this first) Algorithms 4th edition by Sedgewick
* Algorithm Design by Kleinberg/Tardos

Figure out how the hell programming languages work and how to make one:
* Essentials of Programming Languages by Friedman/Wand

Figure out what the Operating System does for programmers, how things work "under the hood":
* Computer Systems: A Programmer's Perspective by Bryant/O'Hallaron

[paip-review]: http://www.amazon.com/Paradigms-Artificial-Intelligence-Programming-Studies/product-reviews/1558601910/ref=cm_cr_dp_synop?ie=UTF8&showViewpoints=0&sortBy=bySubmissionDateDescending#R26TS0X19V6HJ4

## Happy Hacking

Welp, that's it. Every strong jumping off point I could think of.

I'll likely add a few videos and blog posts to this over but
what's most important is a starting point and I think this is a good one.

I haven't done everything on this list and that is okay! We've all
got to pay the bills and get away from computers too. Remember to
have a beer and some time in the sun with loved ones.
I'm here if you have questions or feedback.

Thank you for being my students. :beers: :balloon: :tada:
