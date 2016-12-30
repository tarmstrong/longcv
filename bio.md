# Tavish's excessively long programmer biography

I'm curious about what skills people need to know before they get jobs as programmers at bay area tech companies. So the story goes, you have to be a nerdy kid who was given a PDP-11 that you soldered yourself with a soldering iron that you built yourself. Or whatever. Generally speaking I reject the narrative of the genius young programmers of Silicon Valley, because I think the skills I use at work can be learned, and I believe they can be learned more efficiently than the way I learned them. While I might be stereotypical in some ways, I don't think my success as an engineer is _because_ I started young.

This document is an attempt for me to recall all the programming skills I learned and how I learned them. I do not want to suggest that these are all skills that you need to learn before getting a job at a fancy pants bay area tech startup. Nor would I suggest that they are sufficient, or that bay area tech startups are good at evaluating engineers, or any of that. I don't think I'm all that good or useful as a programmer, honestly. But I'm curious to find what I'll learn when I write out this history in excruciating detail.

You'll notice that I had a very privileged upbringing. I was exposed to computers at a young age and had access to the internet. I had a lot of financial support from my parents that allowed me to spend time learning how to program instead of making enough money to cover tuition (until I got internships that paid well enough to do so). I also had great mentors who helped accelerate my learning.

I want to explicitly point out my privilege, not because I think it's required, but because it's part of why I want to develop more efficient ways of learning this material. People with less privilege or who are learning these things as adults who don't have time to waste should still be able to learn computing skills because it's fun, rewarding, and a great career.

A lot of this history, especially the early stuff, might be incorrect. If you happen to have known me at any of these points in my career and know that I'm wrong about something, please correct me.

## Baby Tavish (1990--1998)

I was born in 1990. My earliest memories related to computers involve my mum typing `w` at a DOS prompt, which was, if I recall correctly, the way that you started Windows at the time. My mum also liked to play Doom, but I wasn't allowed to watch. (I include this anecdote to make my age more apparent in the next sections, and to explain why I thought learning how to use a terminal would be cool when I was older.)

## The early days (1998--2003)

* In 1998 or thereabouts (grade 4?), I discovered [Netscape Composer][composer], a WYSIWYG editor for web pages. My sister and I made goofy websites about figure skating.
* Around that time, my uncle introduced me to [Webmonkey][webmonkey], a website that had tutorials about web programming.
  * I learned how to use a basic text editor (Notepad.exe) for code
  * I read a basic HTML tutorial
  * I read Thau's Javascript Tutorial
    * This tutorial seems to have been republished in on [Wired][wired] in 2010. You can see it in less readable but more authentic form [here][thau-authentic].
  * I read Mulder's Stylesheets Tutorial, which seems to have been republished by Wired [here](http://www.wired.com/2010/02/mulders_stylesheets_tutorial/).
  * Most of what I learned in this period of time was used to make stupid web pages with my sister that would load `alert()` prompts ad nauseam.
    * Specifically, I learned how to use variables, `if`/`else` statements and `while` loops.
    * You might argue that through Thau's more advanced tutorial, Thau's Advanced JavaScript Tutorial, I learned things about functions. I only learned enough to attach a chunk of code to an `onclick` HTML attribute, though.
* In 2000/grade 6, I was enrolled in a program for "gifted" children. Once a week, I would be bussed to a different school in the area to study with other gifted children. This program had a large emphasis on puzzle solving (which I hated) and self-directed study (which I loved). My end-of-year project involved a 45-minute long presentation to my peers. For this project I decided to teach my fellow students basic web skills (like HTML, CSS, and JavaScript). During the presentation, I gave a lecture using marker on an overhead projector. This lent itself surprisingly well to explaining the structure of a basic web page. At the end of the lecture portion, my fellow students used the computers in the classroom to practise what they learned. They made some basic web pages!
* Around 2002--2003 I started learning some more advanced web design from a friend of mine from school who had gotten involved in the Harry Potter fandom. At the time, fansites didn't have wikis or other modern technology: you would draw out your page in Adobe Photoshop 5 and then slice it into images that you then dumped into a table-based layout.
  * I learned some basic Photoshop skills, using a copy of Photoshop that my dad brought home from his office.
  * I learned how to make a really basic text-file based Content Management System in PHP. Specifically, this amounted to something along the lines of `<?php include "./header.php"; include "./content/" . $_GET['page'] . ".txt"; ?>`. I do not recall whether or not these scripts were smart enough to prevent filesystem traversal, but let's just say that I didn't learn about web security at this time.
  * To set up forums for a Wheel of Time fansite I ran, I installed bootleg copies of phpBB and vBulletin, which involved learning how to use FTP. This also introduced me to editing configuration files.


Throughout this period I relied on various free hosting providers because I was too embarrassed to tell my parents about the websites I was making and I didn't think they'd want to spend money on web hosting. I think at one point I might have convinced my dad to pay for some really cheap hosting but the details are eluding me.

I made a feeble attempt at learning C++ during the fansite years, encouraged by someone in the Wheel of Time community who gave me some pointers (over MSN) on how to learn to program. He gave me a few programming challenges, which I really enjoyed. But eventually I got frustrated by not knowing how to use abstractions like functions and modules. I didn't know how to learn this stuff and eventually got bored and distracted by other pursuits.

[wired]: http://www.wired.com/2010/02/javascript_tutorial/
[composer]: https://en.wikipedia.org/wiki/Netscape_Composer
[webmonkey]: https://en.wikipedia.org/wiki/Webmonkey
[thau-authentic]: http://currell.ca/js/hotwiredlycoscom/webmonkey/programming/javascript/tutorials/tutorial1.html

## High school (2004--2008)

* In 2005 I took a basic programming course. We learned Visual Basic 6.
  * The details are fuzzy, but I recall a visual tool for designing UIs. The general concepts were similar to Javascript in that you would write event handlers that were triggered by the UI.
* In 2006 I had a similar class that continued to teach Visual Basic 6. I was bored and spent a lot of time helping my classmates. When I finished the requirements of the final project, I wrote a simple Snake-like game where your avatar was a picture of Tony Jaa (with his legs on fire).
* Near the end of high school I used money I had earned from teaching figure skating to buy myself a laptop in preparation for university. I can't remember exactly when this happened, but I believe I installed Ubuntu on my laptop before I left for university. Somehow I managed not to trash the thing, but you can be assured that wireless did not work.
  * From trawling the Ubuntu forums for instructions on how to get wireless working on my laptop I was exposed to some basic command-line skills.
    * File navigation and management: `cd`, `mkdir`, `wget`, `curl`, `cp`, `mv`
    * I did not learn how to use these, but I was exposed to advanced commands like `ifconfig`, `modprobe`, `rmmod` `insmod`. I still don't really know how to use any of these but now I sort of know what they do.
    * I would have used `gedit` for editing files, not a command-line editor.

## First Year University (2008--2009)

(This part is rambly -- sorry about that.)

Many people know that I graduated from Concordia University with a B. Eng. in software engineering. Few people know that I didn't actually enter Concordia as an engineering student -- I started as a French Translation major (with a minor in German). That lasted about one semester, during which I learned that graduating with a translation degree in a city where many people grew up bilingual was going to be difficult. Not difficult in a good way, but rather difficult in a way that was going to involve a lot of suffering. It was going to involve a lot of tears, but not the sexy, artful french tears I had hoped for.

During that first semester I was also taking an elective -- a C++ course offered by the computer science department for non-CS majors. This class was taught by [Prof. Nancy Acemian][nancy], who later won an award in the department for teaching excellence. Thanks to that excellent class, I realized that programming was a lot of fun and more likely to result in a job. So I switched into the Software engineering program.

[nancy]: https://www.concordia.ca/encs/eng-society/faculty.html?fpid=nancy-acemian

Around this time I also discovered writers like Cory Doctorow and through him the open source community. Richard Stallman came to my university and gave a talk with a floppy disk on his head. I started reading Reddit's /r/programming and Hacker News regularly. I was hooked!

With that background out of the way:

* I was told by the internet that being able to edit text quickly was important to my success as a programmer, so I learned how to use vim.
* I learned some basic LaTeX and used it to typset school assignments because nerds on Hacker News told me that it was cooler than Microsoft Word.
* I learned the basics of version control using git for my own personal projects
  * To learn how to use Git, I read [Pro Git](https://git-scm.com/book/en/v2).
  * I think Github existed back then but I didn't know about it, so I had no way of interacting with git servers. I used git entirely for local work.
  * I didn't have that much code to write, so I mostly used git for tracking fiction that I was writing at the time.
* The internet told me that CS students who learned Java were useless and CS students who learned Python got jobs, so I learned Python.
  * The python tutorial I read was [Dive Into Python][diveinto]
  * This taught me a lot of fundamental programming concepts, like control structures, Object-oriented programming (though I didn't understand why OOP was useful).
  * Perhaps more importantly than that, it taught me how to access documentation, how to find libraries that would help me build what I wanted, etc.
  * It also taught me about unit testing, although it took me several years before I found tests more useful than painful.

[diveinto]: http://www.diveintopython.net/


## First Programming Job, Sort of, and my first `rm -rf /` (Summer 2009)

My childhood babysitter who grew up across the street from my parents' house ran a web development consultancy in my hometown. When I was looking for a summer job my parents mentioned to him that I was learning to program and would he please hire me as an intern? When he was a child, my mother once deployed first aid on him after he was wounded in a playground accident so he obliged.

While he didn't offer me steady work (he billed by the hour) he offered to let me hang out in his office and do odd web development jobs that he didn't have time to do himself. He gave me fixed-price quotes. This was mutually beneficial -- I didn't desperately need a steady paycheque and he didn't desperately need me to complete my tasks quickly.

At this gig I:

* Continued to develop my HTML, CSS, and JavaScript skills.
  * In particular, I had to figure out how to make things look good enough for a client. While I had some very basic web development skills, I had never had to make something for someone else; everything I had built could be built sloppily because it was for my own enjoyment.
* I wrote basic PHP code -- plugins for the in-house CMS.
* I got more comfortable deploying PHP sites to servers using graphical ftp clients.

While the person I was working for didn't have much time to help me on a regular basis, he did help me get unstuck a lot. He was an old timey unix nerd from way back when and he taught me about man pages for syscalls.

When I didn't have work to do I messed around with various programmy things:

* I tried in vain to install the audio synthesis programming environment [supercollider](http://supercollider.github.io/) which, at the time, involved chroots and other dark magic that I didn't understand as I copy-pasted it from the internet. This experience actually taught me some valuable lessons in systems administration:
  * I learned what [symlinks](https://en.wikipedia.org/wiki/Symbolic_link) were.
  * I learned why `sudo rm -rf`, run on a hard-link that eventually links to your root directory, will delete your entire filesystem.
  * I learned what happens when your filesystem is deleted while your operating system is running.
  * I learned that taking regular backups is a good idea when you regularly do stupid things to your computer without understanding them.

## Second-year University (2009-2010)

* Fall 2009
  * COMP 248: obj-oriented programming i
    * Intro to Java programming (variables, control structures, basic class definitions)
  * COMP 232: math. for computer science
    * Boolean logic
    * Complexity theory
    * TODO A bunch of stuff I'm forgetting right now
  * MATH 205: differential&integral cal ii
    * Integrals and such
  * PHYS 205: electricity & magnetism
    * Electricity: how does it even work?
    * Magnetism: how does it even work?
    * Electricity and magnetism: are they even related?? Yes!
* Winter 2010
  * COMP 249: obj-oriented programming ii
    * Actual object-oriented programming concepts like
      * visibility (private/protected/public)
      * encapsulation
      * method overriding
      * inheritance
      * java interfaces
      * polymorphism
  * SOEN 228: system hardware
    * How operating systems work: system interrupts, assembly programming, etc.
    * The class project for this was fantastic! We built a 4-bit computer "from scratch" using integrated chips, breadboards, etc. We had to build our own timing circuit and program counter; we had to program the RAM using tiny physical switches; we implemented registers and INC/MOVA/MOVB instructions with physical wires! This was so much fun and I finally felt like I understood how computers worked.
  * SOEN 287: intro. to web applications
    * HTML, JavaScript, CSS, CGI/Perl

* First semester
  * Basic Java course following roughly the same curriculum as the C++ course I had taken the year before.
    * Covered everything from variables to some basic OOP concepts
* Second semester
  * Part 2 of the basic Java course, covering more advanced topics like inheritance, polymorphism, interfaces, etc.

In my spare time I learned:

* Django and used it to build some toy apps for myself

## CUSEC (2010)

In January 2010, I attended the 2010 edition of the Canadian University Software Engineering Conference. Some talks I remember:

* Leigh Honeywell talked about computer security -- basic concepts, where to learn it (e.g., OWASP). This talk inspired me to learn more about computer security. I haven't really succeeded, but I vaguely remember reading some helpful OWASP tutorials afterward that were really helpful.
* Thomas Ptacek also gave a talk about security. The details of this one are even fuzzier, but I seem to recall him making an audience member do a [Diffie-Hellman handshake](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange) with him.
* Reginald Braithwaite gave a talk that I don't remember well but, I think, inspired me to think about programming differently than I had before.
* [Greg Wilson spoke about software engineering research](https://vimeo.com/9270320) and how the industry ignores a lot of what academic software engineering researchers publish. This was my favourite talk of the conference. More on Greg later.
* Douglas Crockford spoke about... programming. I don't remember a single thing about this talk but it did inspire me, for better or worse, to buy and read _JavaScript: The Good Parts_. This book taught me a lot of programming concepts:
  * TODO explain what I learned from this book

This conference was very formative. I learned so much about programming -- in particular the culture of programming -- in those few days and it was the first time I felt really, really excited about my career as a software engineer.

## Failed adventures in consulting

To buy food I wanted to make some money on the side by programming. I had read a bit about entrepreneurship on the internet. I found a customer on craigslist and took way too long to produce a lot of really crappy code. In the end my hourly rate probably amounted to $1/hour.

The project itself was a book editing web application that would allow a customer to arrange their photos in a scrapbook-style book and order a printed copy. Needless to say, this is a large task that a broke student should not offer to do for a fixed, extremely lowballed price. Poor business decisions aside, the project itself looked like this:

* I wrote a custom PHP backend that
  * shelled out to Imagemagick for some basic image processing tasks (rotating, cropping, resizing).
  * integrated with Paypal for basic payment processing.
* I wrote a Javascript frontend to enable editing of page layouts. I might have attempted to use HTML5 but back then the browser support was poor.

Overall I was not very successful business-wise (even in absolute revenue, let alone revenue per hour) and not very successful technically. What I delivered was a proof-of-concept, far from what I would consider production-ready today.

This project didn't teach me how to architect software projects but it sure taught me how unpleasant it can be when you don't have any architecture at all. Every single piece of this project was bolted on to other things that were also bolted on. It also turned out to be hard to stitch together a bunch of components that were just slightly within your capabilities in a way that worked well; just because I could do A, B, and C individually doesn't mean I could build something using A, B, and C together.

## Second summer of coding for money (JavaScript: The Bad Parts) (Summer 2010)

This summer I struggled to find part-time work in my hometown and the same person who I worked for the previous summer offered to pay me to build a project management app. This was largely unsupervised and by the end of the summer I had built a pile of unusable spaghetti code. But, it was a prototype.

* I wrote about 15K lines of JavaScript. This was the largest program I had ever worked with and it was the first time I had to really think about architecture. I had no idea what I was doing and didn't know how to learn.
  * I spent a lot of time learning how to use jQuery
  * I used jQuery UI and various other plugins
* The PHP backend that I wrote had some structure going into this, which I pretty swiftly mangled.

This project was not a success. I did get a lot of practise writing and debugging my own code, though, and it was very challenging. One lesson I learned around this time was that if I feel like I'm making no progress it can be useful to take a step back and refactor the code that is hard to work with. This is easier said than done!

## Third year university

* fall
  * Data structures and algorithms
* winter
  * the software engineering curriculum at Concordia places a big emphasis on project management; that winter we had our first group project that involved building a web app that would build a class schedule for you based on the courses you needed to take and when they were offered.
    * I convinced my classmates to use Python/Django with MySQL as the data store.
    * We had to extensively document our design using UML
    * We used Subversion for version control
    * I learned that it is hard to install Python and Django on Windows machines (my peers largely used Windows and had never been exposed to Python before)
    * I learned that it is a bad idea to try to get your classmates to learn Python in the middle of a busy semester

Fall 2010
* COMP 352: data structures + algorithms
  * Linked lists, hashtables, binary trees, heaps, etc.
  * Complexity analysis (big-O and such)
* ENCS 282: tech. writing + communic n.
  * THIS WAS THE BEST CLASS
  * Rhetoric
  * Techniques for technical writing
  * Persuasion
* ENGR 201: profess l. practice+respons.
  * Engineering ethics
  * Whistleblowing
  * Keeping records and stuff.
* ENGR 213: app.ordinary diff.equations
  * Differential equations.
* ENGR 233: applied advanced calculus
  * I have no idea what we learned in this class TODO
 
Winter 2011
* COMP 346: operating systems
  * Concurrency control
  * Philosophers??!?!
  * Schedulers
  * TODO more...
* ELEC 275: principles of electrical engineering
  * I was really bad at this.
* ENGR 371: probability+statistics for engineers
  * Probably the most useful math class I took
  * Statistical tests (e.g., t-tests, standard deviations, etc. etc. etc.)
* ENGR 391: numerical methods in engr
  * Linear regression
  * TODO fill this out more
  * The project was written in Matlab; I used Octave
* SOEN 341: software process
  * Introduction to software engineering.
  * Talked about a lot of famous case studies like THERAC-25
  * Talked about the history of the discipline: the Software Crisis, the CHAOS report, etc. etc.
  * Learned basic UML documentation techniques.
  * Built a web app to help build class schedules for the class project, as a team of 3-5.

## CUSEC 2011

In 2011 I went to CUSEC again and saw some talks that influenced me one way or another:

TODO fill this in

## Co-op interviews

In February 2011 I joined the co-op program at Concordia. Engineers in the bay area will be most familiar with University of Waterloo's co-op program, which does a fantastic job of getting their students out to San Francisco, but many other Canadian universities have similar programs. I'm not sure I would have had much success getting internships at places like Google, but in any case, I only applied to local companies.

I specifically focused on applying to smaller companies that were using technologies I thought were interesting, or doing open source work. In the end I got three interviews:

* One was at a company based in Laval that did C# development (I think?). I didn't pass this interview, which largely talked about my experience and interests.
* One was at a small startup called [Nimonik](http://nimonik.com/). They made me an offer after a phone screen with their developer.
* One was at a small Drupal (PHP) consulting firm called [Evolving Web](https://evolvingweb.ca/).
  * If I recall correctly, this interview involved:
    * a small data structures problem
    * a "bug squash" where I had to fix a Drupal installation that was failing to load. This involved print-statement debugging.
      * It's worth mentioning that there's essentially no way I would have solved this problem without the help of my interview, who on the spot taught me how to debug a really large, unfamiliar program. Specifically:
        * Focusing on forming hypotheses, and editing the random library code to add print statements or throw errors

In the end, I chose to go with Evolving Web because the pay was better, and because they offered to pay me more if I took off my Fall semester to work with them. So, not only did it pay better, but I was going to earn even more due to the length of the internship. And my tuition costs were cut in half thanks to being a part time student that semester (I only took 2 night classes that semester). At the time, I wanted to be (mostly) financially independent, so the decision was easy.

## Evolving Web (summer 2011, autumn 2011)

This 8 month period was probably the most educational for me because I got a lot of great mentorship from my colleagues. Alex, the co-founder, spent hours with me teaching me how to debug code, how to do various systems administration tasks, etc. It's hard to understate how important Alex was to my current career as a developer. My current `.bashrc` basically dates from this era.

Specific skills I learned:

* How to write plugins for Drupal
  * Drupal, at the time, used this funky "hook" architecture where, at various points in the "Core" drupal code, you could insert your own code to modify data structures that were passed around. These data structures were just nested PHP `array`s (for those of you who don't know PHP, `array` is a list _and_ a hash table) that controlled everything from routing to page structure to rendering.
  * A lot of what I learned here was how to poke at the "core" Drupal code to figure out how it was working. Judicious use of print statements, pretty-printing, and staring at the code got me pretty far. (Again, I want to stress that Alex taught me these skills. I did not come by them naturally.)
  * It was considered anathema to "patch core", i.e., to maintain your own fork of the vendored code you used to build a Drupal site. This meant you had to jump through a lot of hoops to do it the "right" way with a hook, sometimes by submitting a patch to the open source module you were using.
  * To that point, I learned how to submit patches to open source Drupal modules. Drupal had its own change revision system.
* How to use Chef to configure servers
* How to use Ruby to write plugins for Redmine (the open source ticketing tool that we abused extensively)
  * This used a lot of the skills I learned from writing Drupal modules, but with a different plugin model.

Evolving Web was very active in the Drupal conference circuit and encouraged me to participate in them and give talks. With the mentorship of the team I gave some talks at a few conferences, largely about Drupal's [new Field API](https://github.com/tarmstrong/poutine_maker/blob/master/poutine_maker.module). I also participated in some open source sprints, though I found it difficult to make much progress on a lot of the bugs I tried to fix. That said, there are [3 commits](http://cgit.drupalcode.org/drupal/log/?qt=grep&q=tarmstrong) in core that I contributed to in some small part (whether that was a partial patch that was thrown away, or some minor testing). I found the Drupal community to be really supportive and welcoming.

I owe a lot to Alex, Suzanne, Jon, Thomas, and [Logan](https://twitter.com/loganfsmyth) who taught me a lot during this time.

## 3rd year university

During my internship (fall 2011)

* COMP 335: intro/theoretical comp sci
  * formal language theory
  * automata, grammars, etc. 

Side note: around this time, I discovered a few talks from the Chaos Communications Congress that changed everything about computers for me. The first was a talk by Travis Goodspeed on [packet-in-packet attacks][travis] that exploit poorly written hardware parsers. The second was [The Science of Insecurity](https://www.youtube.com/watch?v=3kEfedtQVOY) by Meredith L. Patterson, which blew my mind completely. This was in no small part because I had just spent a semester learning about formal language theory. I knew that it was useful for building parsers, but this talk really made something _click_ for me, and made me feel like learning all this CS theory was useful after all. It's one of the technical talks that I think about most often, even as of this writing.

[travis]: https://www.youtube.com/watch?v=euMHlV6MNqs

Winter 2012

* COMP 345: advanced program design, c++
  * This course was a pretty straightforward class about the C++ language. The professor was one of the more savvy programmers in the department and did a decent job of helping us write decent C++ code.
  * One of the programming assignments was building a search index from scratch.
    * Specifically, we used TF-IDF to implement this.
* COMP 445: data comm + comp networks
  * In this class I learned a lot about how networks work:
    * How the physical layer works (e.g., pulse width modulation)
    * Major protocols: IP, TCP, UDP, etc.
    * More detail about TCP:
      * Sliding windows
* SOEN 385: control systems+applications
  * Control theory: laplace transforms, PID controllers, etc.
* ENGR 392: impact/technology on society
  * Technology is not politically neutral.
  * Technology does not develop deterministically and linearly; the social context drives development of technology.

## Evolving Web part 2

This summer involved a lot of similar work to the previous summer.

* We did some English/French localization work. I learned about tagging UI strings and other such things.
* I worked with [Julia Evans](http://jvns.ca/), who taught me a lot and continues to teach me a lot about programming. And being a good person.

## 4th year uni

Fall 2012
* SOEN 342: sw requirements + specs.
  * Lots of formal theory on how to write software requirements. This was basically a class on writing super long contract-esque requirements docs. This is not how my job works.
  * Some formal specification stuff like the Z language.
* SOEN 343: s.w. architecure & design i
  * This project focused a lot on open source software development techniques because that's what the professor was interested in researching.
  * This was where I learned about Conway's Law, which fascinates me constantly.
  * The final project involved [proposing a refactoring change to an open source project](http://tavisharmstrong.com/2012/11/29/phergie-refactoring-idea/)
* SOEN 384: mgmt+quality ctrl./sw dev.
  * Dubious ways of measuring the quality of software
    * test coverage
    * mccabe complexity (note: this correlates with lines of code so is not actually predictive?!)
    * etc.
  * How to measure qualitative aspects of software:
    * e.g., SLAs on uptime
* SOEN 422: embedded systems/software
  * Using low-level operating systems knowledge and some electrical engineering knowledge to build robots and such.
  * For fun, on the side, I built [interactive documentation](http://tavisharmstrong.com/timer1) for the Teensy's 16bit timer.
  * Spent a lot of time writing embedded C code to make motors go.
* SOEN 423: distributed systems
  * Concurrency control (locking, etc.)
  * Distributed clock systems (e.g., Lamport clocks)
  * Consensus algorithms
  * RPC technologies (CORBA, WSDL, etc.)
 
Winter 2013
* SOEN 344: s.w. architecure & design ii
  * Old-school Gang of Four architectural concepts.
  * Refactoring strategies.
  * More UML documentation techniques.
* SOEN 345: s.w. testing, verif & qa
  * Unit testing, integration testing, load testing, etc.
* SOEN 357: user interface design
* SOEN 390: software engr. team project
  * We formed groups of 8-10 and ran a software project to replace a food bank's computer system.
  * We used the (somewhat overwrought) software development process that had been taught to us: we wrote long requirements documents after meeting with the "customer"; we documented our design thoroughly with UML before beginning implementation; we wrote our code; we documented our testing process and used measurement techniques (like McCabe Cyclometic Complexity, dubiously); we got approval from the "customer" at the end; documented maintenance plans.

Summer 2013
* ENGR 301: engr.mgmt.princip.+economics
  * Basic engineering management. This was a course meant for all engineering disciplines at Concordia. The techniques discussed in this class bear no resemblance to how planning at tech companies happens; it seemed to be more suitable to budgeting and planning at a civil engineering firm with clear, predictable projects.

## The Performance of Open Source Applications

I don't remember when I discovered _The Architecture of Open Source Applications_ (eds. Amy Brown and Greg Wilson). When I learned that they were working on a second volume and needed help, I emailed Greg (who I knew from the previously mentioned CUSEC 2010 talk). Greg and Amy are both very good at wrangling volunteers and let me proofread some chapters. It was fun!

After they published the second volume of AOSA, Greg wanted to publish a third volume that focused on performance. Unfortunately, it was too much for him to take on personally at the time. So, he started looking for a victim. I was one of those victims. Originally I started working on the book with Tony Arkles, but he sadly had to drop out because of other commitments. That said, editing a book is an exercise in organizing people, and the amount of people who pitched in to help was staggering.

I've never really written out what it takes to edit a book like that. Roughly speaking:

* You email a bunch of people and ask them if they would pretty please write a chapter for your book. (Lots of email.)
* If they agree, ask them for a plot summary (so you can help make sure they're on topic before they waste a ton of time)
* Ask for a first draft; provide feedback on that draft (usually high-level concerns like "does this fit the theme?" or "would this be interesting to anyone?")
* Wait for feedback on that draft. Provide feedback on the second draft and send it for technical review.
* Get technical reviewers to take a pass at the chapters and look for technical problems, factual errors, etc.
* At this point, you apply more structural edits, and get all the chapters into a common format so that your army of copyeditors can work with consistent text.
* Deploy your copyeditors! Build a style guide for people to apply consistently. (Do you capitalize "Web"? What kind of words are typset as code? Which are capitalized? Do you use sentence case or title case for second-level headers?)
* Typeset!

The end result was [The Performance of Open Source Applications](http://aosabook.org/en/index.html). What did I learn from this experience?

Thankfully, you'll notice that the hardest part is done by the authors (actually writing the damn thing). For me, there were a few challenging aspects of this project. First, it took about a year, which was, at the time, the longest running project of any kind I had ever worked on. Second, I had to give feedback on technical writing in domains that I knew very little about to people that were way more experienced than me. This was intimidating, but thankfully got a lot easier once I learned how wonderful all the authors I was working with were.

## Summer 2013

I spent the summer of 2013 working with Prof. Peter Rigby at Concordia University, researching code review on open source projects. I spent a lot of time mining data from open source change trackers like Gerrit and Rietveld, and bug databases like Google Code. I was particularly interested in linking bugs in the bug database to bug _fixes_ in the code review tools, and using git history to look at the code review history of the files that were (supposedly) therefore deemed buggy. With this sort of research project it helps to be very focused; I tended to go down rabbit holes and was ultimately not very successful as a researcher.

I did learn quite a bit from this experience, though:

* I wrote a very large amount of code for scraping Web APIs and dumping those into PostgreSQL databases. 
  * Technologies:
    * Python, BeautifulSoup, SQLAlchemy
  * I learned a lot about how to write long-running jobs that deal with interruptions and errors gracefully.
  * These scripts, which ran on my university desktop, would save the result of every HTTP request locally on the filesystem before attempting to insert it into the SQL database. This made it much faster to recover after my program crashed on unexpected input after 100000 requests, and meant that if I wanted to make a change to the processing code I could do so without re-doing all of those HTTP requests.
  * I learned how to throttle my scrapers to avoid Google's ire.
* I wrote tools for importing Git history into PostgreSQL databases.
* I wrote _a lot_ of SQL queries. Specifically I learned about:
  * `with`, `group by`, sql functions, the `psql` command line tools.
  * I experimented with but discarded sql stored procedures written in Python.
* I used R for statistcal analysis and learned about
  * I learned about different correlation tests (like Pearson and Spearman)
  * How to understand distributions in a dataset
    * with violin plots and box plots
    * q-q plots
  * time-series analysis tools like [cross-correlation](http://tavisharmstrong.com/2013/07/06/what-i-cannot-create-i-cannot-understand/)

On the side, I was also helping a grad student with their project, which was a code review tool built _in_ Git itself. Essentially, we used git objects to store code reviews (which were formatted in the bottom-posting style of the linux kernel mailing list). TODO flesh out what I learned about Git.

## Final year of school

Fall 2013
* COMP 348: prin./programming languages
  * Learned about many categories of programming languages: imperative, object-oriented, functional, declarative, logic.
  * Wrote toy programs in Prolog, Ruby, C, Scheme.
* COMP 472: artificial intelligence
  * Learned about the history of AI.
* SOEN 691D: topics/software engineering (grad-level course on topics similar to my summer research work)
 
Winter 2014
* CLAS 266: intro classical archaeology
  * Greek archaeology from 30000 BC to roughly 400 BC.
  * Learned how we discover things about ancient civilizations: what is durable enough to survive, what is not; how we can date artifacts and discover how they were used; etc.
  * Learned how to interpret things about the history of these places based on archaeological remains.
  * Learned lots about painted ceramics, related technologies.
  * Learned lots about bronze and marble statuary
    * Many statues we have are actually marble ripoffs of bronze statues, copied by the unoriginal Romans!
  * This class actually taught me a lot about software development! We often deal with many layers of software that has been created over the years. A lot of it has been lost, and we can only see the most durable software. Isn't that fascinating?!?!?!?!?!?!?!?!
* SOEN 331: intro to fml mthds for soen
  * Design by contract
  * Z specification language
  * Aspect-oriented programming (see [pyadbc](https://github.com/tarmstrong/pyadbc).

## final year capstone project

Concordia's software engineering program requires students to build a "capstone" project in their final year. We had a few rules: we had to have a "customer", the project had to be extensively documented, and you had to form a team of 5 or more. The most time-consuming (if not hardest) part of the project was the documentation -- everything from the process (e.g., agile) we used and why we used it, the architecture (with UML), and particularly silly aspects like billable hours all needed to be bundled in the documentation we submitted to the professor at the end of the year.

The "customer" had to just be someone who wanted a piece of software built. I turned to Greg Wilson, who is an expert at coming up with work for people. He pitched a few projects. One was a WebRTC-based videoconferencing tool for inverted classrooms. I believe I ruled this out early because it was too technically complex, relied on newer, fast-changing technology, etc. The next suggestion was a diffing and merging tool for the IPython Notebook. I had worked a lot with Python (and with IPython Notebooks) in the past so I thought this was a cool project and much less risky since I understood the relevant technologies much better.

After a year of hard work from the entire team, we released [nbdiff](https://github.com/tarmstrong/nbdiff). Unfortunately, none of us have had much time to maintain the project since we graduated and got full-time jobs, and keeping it up-to-date with the fast-moving IPython project takes a pretty significant amount of time. In retrospect, I think the only way a project like this would be successful is if it was in the core IPython project, such that you had to keep the nbdiff tests passing in order to make your changes to IPython.

Here are some things I learned over the course of this project with my teammates:

* How to navigate a medium-sized Python project to understand what parts of the IPython project's code we could re-use.
* How to set up travis-ci for a small team
* How diffing and merging algorithms work, in order to write a module to do structured diffing on hierarchical data.
  * We looked up the original Hunt and McIllroy paper to figure out how to implement this
  * (Actually, we didn't look up prior art for merging, we just took the diffs between base/HEAD and base/branch and diffed those, like a second-order diff. I don't know if that's how merging algorithms worked.)
* Yes, even some skills related to documenting a Python project with UML. There are challenges: the tools for making diagrams are clunky, don't have support for version control, and are hard to keep up to date with your changing project. That said, I think there are some benefits to high-level diagrams of your project's architecture and thought it was an interesting [AOSA](http://aosabook.org/en/index.html)-style exercize in communication.
* I was the "team-leader" for the project. While the entire team contributed equal amounts of work, I had much more experience with Python and especially with open source practises, so I had a heavier hand when it came to design and code review. This was basically the first experience I had with a typical code review process outside of small interactions with the open source community.
* I got a lot more practise writing tests.

There is now a successor to this project called [nbdime](http://nbdime.readthedocs.io/en/latest/).

## Interviewing for full-time jobs

## Getting a job and moving to San Francisco

* ruby
* operations
* monitoring
* working with banks
* batch processing
* problems of scale
* incident response
* safely making changes to a production system
* mentorship
* growing engineering team
