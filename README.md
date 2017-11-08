# HYF_proposal
Proposal for new order of topics, cli, html/css, git, and js. And some additional notes about why and how.

Please provide comments/feedback :grin: 

## HTML/CSS/CLI

#### Week 1
> before students arrive they all have a text editor installed, have created a slack account, created a Github account and have upload their application assignment in trello. See HTML/CSS [week 0](https://github.com/HackYourFuture/HTML-CSS/tree/master/Week0) for more info on how students should prepare for the first day. Here you can find how we let them hand in their homework with Github pages in the first module: https://github.com/HackYourFuture/HTML-CSS/blob/master/Week1/MAKEME.md#how-to-hand-in-homework

We start this day at 11.30
- Introduction to HYF
- Getting to know each other

Start HTML/CSS:
- The division of labor between HTML and CSS
- Introduction to HTML:
 - Parents, children, attributes
 - Indentation
 - Semantic elements
 - Paragraphs, links, images, lists
- Introduction to ARIA:
 - What is ARIA and why is it important?
 - Using ARIA in HTML
 - Validating ARIA
- Introduction to CSS:
 - Where can we write it and what difference does that make?
 - Selectors (id, class, element type), properties
 - How to structure a CSS file
 - Naming things
- External files: relative and absolute paths
- Getting to know your text editor

#### Week 2
11.30 - 13.30:
> Do we want to start all html/css/cli classes at 11.30 to see how it goes for the first round?
> BEFORE students arrive they all should have install gitbash (which is emulation of UNIX like bash on Windows), Mac and Linux users already have a terminal. With Gitbash, every single student can execute and see the same commands with same output. Also Gitbash is later used to teach Git.

- CLI, [lecture 1](https://github.com/HackYourFuture/CommandLine/blob/master/Lecture-1.md)
    - To know the terminal/bash/command line for UNIX based systems. (cd, ls, mkdir, cp and useful bash constructs)
    - Navigate the file system without using a UI explorer.
    - Copy, rename and move files with terminal commands.  

> The idea is to let students them use the command line to build the folder structures and files they have to drag and drop into GitHub, [homework repo example here](https://github.com/mkruijt/HTML-CSS). Besides the commands that are documented in the CLI repo we can teach them how to open their code editor from the CLI and their index.html in the browser. In this way they can maybe see the intimidate use of CLI. Also in JavaScript1 students will work with Node, hopefully by introducing them to the CLI earlier on it the program they will feel more comfortable working with Node.

_After the break:_
- Responsive web design
- Media queries
- Flexbox
- How to use the inspector

#### Week 3
11.30 - 13.30:
- CLI, [lecture 2](https://github.com/HackYourFuture/CommandLine/blob/master/Lecture-2.md)
    - Learn output redirection, piping on the terminal.
    - Write basic shell scripts to ease the programming life.

_After the break:_
- Student presentations
- Last week recap and questions
- How to find information on the web
- How to rebuild an existing responsive page (getting started with this week's homework exercise)


## JavaScript/Git

#### Week 1
- Git (lecture 1 and 2)
- https://github.com/HackYourFuture/Git/blob/master/Lecture-1.md
- https://github.com/HackYourFuture/Git/blob/master/Lecture-2.md

After this session students should:
- Have an understanding of problems for developers working together on software
- Have an understanding of the need for version control software
- Have an understanding of what GIT is and what problem it solves.
- Understand what a commit is and how it represents a certain unit of work
- Know how to create a new repository using clone and init
- Know how to add / remove files to that new repository
- Know how to commit and push files in that new repository.
- Have an understanding of branches and how they can be used.
- Know what a remote is and know how to retrieve remote information from git:
- git remote [show] [-v] [-vv]
- Know what the difference between the three types of branches are.
- Know how to navigate between branches and what git commands to use for them.
- Have an understanding of what HEAD means.

> From now on students can hand in their homework via git.

#### Week 2
> Before students arrive they should all have installed Node. In JavaScript 1 we will use this to let them run their code. In JavaScript 2 we will work with JavaScript in the Browser and show them how it can work together with what they have learned in HTML/CSS.

- Intro JavaScript (What is it, where can you use it for)
- Variables [var, let, const]
- Basic Data types [Strings, Numbers, Arrays, Booleans]
- Operators
- Naming conventions
- Conditions

#### *Debugging lecture (online lecture during week 2)*
- TODO

#### Week 3
- Git [work flow](https://github.com/HackYourFuture/Git/blob/master/Lecture-3.md)

> After this Git session students are able to push pull, fork and make PR, this opens up possibilities for handing in homework and cloning repositories we want them to further work on, as homework. Can for example be used in the debugging lectures, where they fork code that they have to debug.

- Advanced data types [Objects]
- Statements vs Expressions 
- Loops (for/while)
- Functions 

#### *Debugging lecture (online lecture during week 3)*
- TODO

#### Week 4

> JavaScript in the BROWSER with HTML and CSS

- Capturing user input
- Basic DOM manipulations [img src, innerHTML]
- Code debugging using the browser
- Code commenting
- Structuring code files

#### Week 5
- Functions + JSON/Arrays
- Array Manipulations 
- JSON
- Map and filter
- Arrow functions

> The idea is to let them write arrow functions and use map and filter without going to much in depth about how it work and than the week after come back at the subject while talking about scope and closures

#### Week 6
- Closures 
- Scope 
- Events
- Callbacks

#### Week 7
- Object Oriented Programming
- Code flow (order of execution)
- Async VS Sync (use api call to illustrate -> fetch)

#### Week 8
- Structure for a basic SPA
- XHTTP Requests 
- API calls

#### Week 9
- (re)writing data structures (in JSON)
- Promises


----------------

### Added:
- MORE OBJECTS!!! (OOP)
- Online Debugging sessions + homework, lectures and assignments can be found here: https://github.com/HackYourFuture/debugging (work in progress)
- Aria (has been there for a while)
- All homework is hosted on Github + Github pages from day one HTML/CSS

### Changed:
- CLI to the HTML/CSS module
    + Why? It seemed like a good idea to get students more comfortable in their coding environment earlier on in the program. Also this makes that we can move git more to the beginning of js, which has multiple benefits for handing in homework etc. Also this will give more room (breathing space) in the super craped js modules, we need more time here to properly cover all topics.
- Git will be taught the entire day the first day of js1
- Tried to reorganize topics into a more logical order


### Removed:
- Polling
- Reduce
- TDD 

### Todo:
- Add to each module, what we expect students are able to do/builds afterwards, for example for the third module this could be something like (written by Laurens): 

> During this module you will learn how to load data from an external source and reflect that data in the DOM dynamically. You will work with JSON data provided by an API and create your own data structure. This will allow you to make a single page application that is self contained and goes beyond the basic functionality of a web page. (the goal is give a more holistic view of what you can do with what you’ve learned.)

- up until week 4 planning looks ok, after that probably some topics needs to be moved around


