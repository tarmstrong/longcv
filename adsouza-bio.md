# Very Early Computing Experiences

In 1984, when I was 4 years old, my dad bought a ZX Spectrum - the British counterpart to the C64 that was popular in the US.
He showed me how to write simple for loops in BASIC to draw concentric circles in different colours on the screen, which is
one of my earliest memories. I have a distinct recollection of him explaining the syntax for defining a function to me
and me not understanding what a function was.

There was then a gap of a few years but I recall only playing games on the Spectrum at around age 7 or 8, just before he sold
it and bought a PC clone powered by an 8086 CPU with a pair of 5 1/4 inch floppy disks for storage - one had to hold the OS
while the other held the application!
Around age 9 or so I was bored and decided to read through the entire DOS manual and try out all the commands on the PC.
While not technically programming, that was the beginning of me using computers to do something other than just play games.

That said, I did accidentally learn one very key computing concept by playing a game. It was a silly game where you had to
guess a randomly selected number between 1 and 100. I quickly realized that the most reliably efficient way to guess the
number was by using binary search, although I didn't realize until many years later that this process had a name.

# K-12 Education

In grade 7 we had a class where we learned how to use LOGO to draw on the screen. LOGO remains my ideal choice for
introducing programming to kids because it's very simple to get started and you see immediate visual results but it is a real
programming language with precise syntax (as opposed to a visual one like Scratch).

In either grade 9 or 10 I took another class where we learned GW BASIC and I finally understood what my dad had been trying 
to explain about defining functions. 

After that I took a class in grade 11 where we learned a neat little language called Turing that had a clean syntax but could
be compiled into a binary executable. Turing is where I really learned about complex branching/selection via nested if
statements.
The next year I learned some basic C and had mild exposure to a few other things (C++, Java, Javascript). By this point I was 
pretty sold on the notion of programming as a career but didn't yet grasp the concept of memory indirection via pointers.

# College

My first couple of programming classes at the University of Waterloo were in Java, which I initially liked, and Scheme
(a Lisp dialect), which I did not. It was through Java that I learned how to use recursion and objects.
In my sophomore year we learned C++ and thereafter we had the choice of those two very mainstream languages for most 
assignments, although a few classes (e.g. OS, concurrency, distributed systems) required C++.
In my final year I also dabbled in Python a bit and had mild exposure to a few more esoteric languages (e.g. ML, Haskell).
Despite this, I still hadn't grokked functional programming!

Interspersed with classes I also did several 4 month long internships at various software companies. The first one was at a 
small company called KL Group that made commercially available tools for Java developers (e.g. a profiler called JProbe).
I did some QA for a tool that automated deployment of Java apps and then I designed a modular automated test harness.
KL Group changed its name to Sitraka while I was there - rumour had it that they paid $100k for the name - and was eventually 
acquired by Quest.

My second internship was at somewhat larger company that had recently changed its name from BlueGill to CheckFree.
The new name made much more sense in light of the fact that they made online bill payment software. They were in the process 
of rewriting a large amount of COBOL code in Java and decided to give that unglamourous task to me. After quickly realizing
that virtually all of the COBOL code in question was very straightforward business logic, I decided to try automating the
process by writing a very simple COBOL to Java translator. It actually ended up working well enough that they soon needed 
another task for me.

This time they had me doing performance optimization on a different Java codebase that they used to process their nightly 
batches of data. Their biggest potential client needed the process to finish in under 3 hours, since they had to take down 
their user-facing web-app while it ran, but they had enough data that our code was taking nearly a full day to run! As you 
might expect, they were quite unhappy about this and refused to give us their business unless we could demonstrate that the 
process would finish in under 3 hours. Initially I got some easy wins by simply switching to a new version of the Java 
compiler and VM: going from JDK 1.2 to 1.3 gave us a big performance improvement for free! Then I fiddled with various 
flags to the compiler and VM to squeeze out a surprising amount of additional performance, getting the clock time down to 
about half of what it used to be without even touching the code itself!

The next easy win was to stop allocating new string objects like they were going out of style. By using StringBuffer instead of
the + operator to concatenate strings, I brought the runtime down to under 9 hours. After that I spent weeks running samples 
of the data through the code running inside JProbe and making smaller optimizations until the whole process took around 6 
hours (a 4X speedup). By this point I had used up all the tricks I could find so they brought in a much more experienced developer
to continue the process but he was unfamiliar with JProbe so I was able to watch and learn while helping him use JProbe. In the 
end we did get the runtime down to 3 hours.

After this wonderful learning experience at CheckFree, I decided to return for another internship but on a different team.
The next time I ended up just writing JSPs, which wasn't nearly as interesting. Fortunately, my fourth internship was at a 
company called Object Technologies International (OTI) that had recently been acquired by IBM to get their hands on Eclipse.
I got to implement the FTP and WebDAV support in Eclipse 2.x under the mentorship of a couple of very capable developers,
learning a lot about architecting extensible systems.

For my fifth internship I returned to Big Blue but this time in the DB2 division, to work on the Unix portability layer.
After a few weeks of fixing various bugs, I ended up on a skunkworks project to port the stack unwinder - a critical component 
of the internal debugger - to the nascant x86-64 CPU architecture. The hardware hadn't actually been officially released yet 
and IBM had certainly not committed to supporting it but my team had somehow obtained a prerelease machine and my manager 
wanted to get ahead of the game on what he believed would be the next great CPU architecture. At the time Intel had just about 
everybody convinced that it was going to make Itanium a success by fiat but my manager turned out to be remarkably prescient.

Because all of this was happenning in secret, we didn't actually have a manual of any kind of documentation for the new 
architecture. In the absence of any guidance, I decided to simply experiment my way to success: I wrote some code that would 
generate a SIGSEGV and some other code that would catch this and let me print the contents of arbitrary registers and memory 
contents. Then I spent weeks slowly poking around various registers to see which ones held pointers to interesting areas of 
memory until I eventually figured out where to look for the stack contents. This ended up being one of the most fun projects I 
ever worked on.

My sixth and final internship was at Sun Labs on a team that included James Gosling himself. They were building a tool that 
could perform static analysis and transformations on Java source code. But they needed a way to sanity check their 
transformations, which is what my task ended up being. I wrote a tool that would examine the Abstract Syntax Tree (AST) after 
it had been transformed and see if it could spot any inconsistencies. This project taught me a lot about both the more esoteric 
features of the Java language and the value of an AST for performing operations and verification on source code.

# Industry

After spending my first year on the job using Java, I switched to C++ for the next couple of years and then to C for a year.
Then I quit my job and dabbled in using Python to build an AppEngine server, JavaScript to build an HTML5 web app and Java to
build an Android app.
I subsequently got another job where I used both C and Python for a few months and then yet another job where I learned Scala,
which I loved. Scala is what finally got me to wrap my head around functional programming.

Five years ago I started my current job, where I used mostly C++ with a bit of Python and Java for the first two years and
since then it's been mostly Go with a bit of JavaScript to build infrastructure and web front-ends. Go has cured me of the
need to use inheritence for code reuse.
