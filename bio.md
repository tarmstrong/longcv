# Tavish's excessively long programmer biography

I'm curious about what skills people need to know before they get jobs as programmers at bay area tech companies. So the story goes, you have to be a nerdy kid who was given a PDP-11 that you soldered yourself with a soldering iron that you built yourself. Or whatever. Generally speaking I reject the narrative of the genius young programmers of Silicon Valley, because I think the skills I use at work can be learned, and I believe they can be learned more efficiently than the way I learned them. While I might be stereotypical in some ways, I don't think my success as an engineer is _because_ I started young.

This document is an attempt for me to recall all the programming skills I learned and how I learned them. I do not want to suggest that these are all skills that you need to learn before getting a job at a fancy pants bay area tech startup. Nor would I suggest that they are sufficient, or that bay area tech startups are good at evaluating engineers, or any of that. I don't think I'm all that good or useful as a programmer, honestly. But I'm curious to find what I'll learn when I write out this history in excruciating detail.

A lot of this history, especially the early stuff, might be incorrect. If you happen to have known me at any of these points in my career and know that I'm wrong about something, please correct me.

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
  * I learned how to make a really basic text-file based Content Management System in PHP. Specifically, this amounted to something along the lines of `<?php include "./content/" . $_GET['page'] . ".txt"; ?>`. I do not recall whether or not these scripts were smart enough to prevent filesystem traversal, but let's just say that I didn't learn about web security at this time.
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


## First Programming Job, Sort of (Summer 2009)




TODO. This document is a work in progress.
