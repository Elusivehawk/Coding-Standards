# Coding-Standards

The coding standards for Elusivehawk, LLC.! Follow them to the letter if you're working on code!


## How to Use

In short, go into Eclipse and use the Hawk's Format.XML file that applies to what programming language you're using, use the supplied Placeholder file for anything that could use a placeholder, and that's about it.


## Format

The format is rather simple, and tries not to deviate too much from standard coding procedure:

* Use 4-long tabs, and NEVER 4 space indents. Tabs allow for the coder to get past long indents without having to use the mouse. Also, do NOT use tabs that are longer or shorter than 4 spaces, in order to keep within convention. Exception: During Python code development, you may (And actually must) use 8-long tabs.

* Use Eclipse. I'm dead serious, failure to use Eclipse for any given reason besides the use of a programming language Eclipse doesn't support will end very badly. Exception: You may use IDLE for Python development.

* Document EVERYTHING. I don't care how long it takes, you made the code, you know how it works, document it!

* Keep code nice and organized, since organized code is much easier to edit. Who wants to go through 100+ files in order to fix a typo in the UI? That's what I thought.

* NEVER use nameless variables, i.e. "var1", "par5", etc. Make your variable's names make sense.

* If it hasn't been tested, don't give it to us. I don't care if you directly copy/pasted some code that worked fantasically in something else, TEST IT!

* Stress test EVERYTHING. Always try to cheat the system in order to find bugs, even if you had no intention to do so. Doing so will improve the integrity of the code, which is always a plus.

* Before trying to squash a bug, think about if it's not actually a bug, and if squashing it will create other bugs. I'm honestly sick and tired of people finding "bugs", "fixing" them, and then screwing up half the code base in the process.

* Keep optimizations to a minimum. Optimizations not only open up new possibilities for bugs to crop up, but can also decrease the moddability of code. Really now, think before you optimize.

* Textures and special effects come first, the only exception being in the creation of new worlds, maps, dimensions, etc.

* For anything not stated here, look at how Hawk's Format handles it.

* If you abbreviate, think before you do it. "DB" *probably* stands for "DataBase", but what if it doesn't? People will go WTF is this person doing with his DB?!?!

* Finally, if you have a choice between making a new class file and a new interface, make a new interface. Interfaces are NICE. :D


## Tasks

In any given project, coders will be given tasks that will limit what they can do. This ensures coders will be able to squash a given set of bugs without being overwhelmed, while allowing for pull requests to be sent and received at will with minimum conflicts.

<<<<<<< HEAD
Tasks will be posted in table format (From now on known as the Task Table) on the project's repository. If you're not listed on the Task Table, you can still code, but you will not be paid, and unless you work for Elusivehawk, LLC.,  contributed code will be considered "Community help", which can therefore be subjected to other limitations which will be defined on a per-project basis.
=======
Tasks will be posted in table format (From now on known as the Task Table) on the project's repository. If you're not listed on the Task Table, you can still code, but you will not receive compensation, and unless you work for Elusivehawk, LLC.,  contributed code will be considered "Community help", which can therefore be subjected to other limitations which will be defined on a per-project basis.
>>>>>>> Updated README.MD.


## Note

These coding standards are subject to change at any point in time. If they do change, kindly, as the kids say, "suck it in and deal with it". Thank you.
