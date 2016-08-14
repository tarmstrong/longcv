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
  * This taught me a lot of fundamental programming concepts, like control strucutres, Object-oriented programming (though I didn't understand why OOP was useful).
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

* First semester
  * Basic Java course following roughly the same curriculum as the C++ course I had taken the year before.
    * Covered everything from variables to some basic OOP concepts
* Second semester
  * Part 2 of the basic Java course, covering more advanced topics like inheritance, polymorphism, interfaces, etc.

TODO I can't remember which CS theory courses I took at the time. Look these up.

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

TODO write out more about this project

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

TODO fill in more of 3rd-year curriculum

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

## 3.5th year university

## Evolving Web part 2

I came back to Evolving Web for a summer.

## 4th year uni

## The Performance of Open Source Applications

I edited [a book](http://aosabook.org/en/index.html) while in school. It took a lot of time and pretending and help from friends.

## that NSERC undergrad research thing I did

## final year capstone project

todo

[nbdiff](https://github.com/tarmstrong/nbdiff)

## Interviewing for full-time jobs

## Getting the job and moving to San Francisco

TODO. This document is a work in progress.
