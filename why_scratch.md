Why My Kid is Learning Scratch and Yours Should Too
===================================================
I have been thinking about what programming language I ought to start my kids with for a good long while. It wasn't that
I felt like programming for its own sake was quote worthwhile unquote - more that I wanted my children to be able to
take a complex task, analyze it, and then break it down into smaller procedures that when assembled in the right order
gave the same result.  I want them to be able to think computationally about things.  Most math curriculums that I've looked at
get at this, but the feedback loop with computers is more engaging for my kids. 

So at most conferences over the past several years, I've asked people who spend a lot of time teaching and instructing (some with kids andsome without kids) what they recommend as far as a way to get started with programming computers. The results have been interesting.  I've heard (or read) recommendations for everything from Racket (be still my little functional programming heart), to Python and (quelle horror) Javascript.  One interesting suggestion was to get started with the [Scratch](http://scratch.mit.edu) programming language.  Scratch is a visual programming language - it uses literal snap-together blocks that represent computer instructions which can be dragged into stacks and executed top to bottom.  

Why Scratch?
------------
For the past two years, my kids and I have been doing the [Code.org](https://studio.code.org) tutorials during the 
"Hour of Code" events in December. This platform (they call "Blocky") uses a "Scratch like" UI to build procedures 
(that compile to Javascript for execution in a browser.) So visually, my son already intuitively understood that 
blocks represent directives to make the computer do actions. 

Scratch has first-class facilities for manipulating sprites, sound control and (rudimentary) animations.  In short, 
it is an ideal platform for building simple games that teach computational thinking which has been my goal for this
work from the beginning. One other neat thing is that kids (with parent's permission) can upload their Scratch 
projects and let other kids play, favorite and review them.  They can even get the "source code" for a project 
and remix it if they want.

While Scratch *looks* simple - I felt overwhelmed trying to understand the full system **and** build a set of lessons
which we could implement successfully in the time my wiggly seven year old would sit through (15-20 minutes tops!)

A Wild "Learning Scratch" Resource Appears
------------------------------------------
This past fall my wife became an Usbourne books consultant. One of the books she bought for $15 was 
[Coding for Beginners - Using Scratch](https://x4311.myubam.com/p/5591/coding-for-beginners-using-scratch-ir) which is a 
short (96 pages) and beautifully designed spiral bound book which contains 15 progressively more ambitious projects 
(games, mostly) which can be implemented in that sweet spot 15-20 minute attention span window for my seven year old. (**Disclosure**: If you order books through that link my wife will earn a small commission.)  We are now going through the
projects - simple ones in a week, longer ones over a few weeks - together every Thursday.  

Preparation is easy: I read through the 2-3 page project the night before and estimate about how far I think we can get in 
20 minutes.  That amount of implementation becomes our goal for our coding session. While we're working on it, I get to
introduce concepts like variables, sprites, animation, using vector math and more. The remainder of the time I let him 
have "free play" exploring other projects/games in the project gallery or messing around in the Scratch UI on his own.

The results so far have been very encouraging and exciting.  If you have been thinking about teaching your younger kids
to code, you ought to give this platform and the book some serious consideration.

Is my kid ready to code?
------------------------
My guideline has been "Can my son read well enough?" Obviously, your mileage may vary. It wasn't until this year that I felt 
he could read fluently enough to really do computer activities semi-independently.  My 4 year old daughter
enjoyed the Hour of Code tutorials but those were guided by me since she is not reading well enough yet to
do it by herself.  Instead, I have been using the [Hello Ruby](http://www.helloruby.com) book and exercises with her
to get her thinking computationally in a more traditional "off-line" setting. She loves Hello Ruby by the way. 

You have a young child? Fret not - check out (former co-worker) Eric Redmond's [CS for Babies](http://www.csforbabies.com)
which aims to introduce computational ideas in a fun and engaging way for very young kids.

Older kids
----------
We haven't quite gotten to this point yet, but my son is an avid Minecrafter. In a few years, I envision we will be 
building our own Minecraft game mods - like Pragmatic Programmer's [Learn to Program with Minecraft Plugins](https://pragprog.com/book/ahmine2/learn-to-program-with-minecraft-plugins). 
I don't have direct first-hand experience with this book, but trust in the Pragprog brand enough that I'm sure its great.

If you have a high schooler who might not be interested in the "simplicity" of Scratch or doesn't like Minecraft (any more :), 
let me recommend the amazing free book [How to Design Programs](http://www.htdp.org) which is a 101-level college textbook that 
introduces all of the foundational concepts of designing programs in a succinct and easy to understand way.

A Quick Note about Scratch
--------------------------
Scratch is a really cool system, but it doesn't implement *everything* I'd like - including first class lists, continuations 
and closures. There's an extended version called [Snap!](http://byob.berkeley.edu) from UC Berkeley which does have these things. 
If you're in that age zone that's above "basic games" and below HtDP, you might give Snap! a try as your child's first programming
language.