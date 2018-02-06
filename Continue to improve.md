With the front of the foundation, the basic front end is getting started, this time may have some in the hearts of everyone learning direction, if still not. You can refer to the prerequisite skills mentioned in the two items, select some from the inside for development learning. Here are some good aspects:

Grunt : Front-end automation tools to increase productivity
less css : excellent CSS preprocessor
bootstrap : excellent CSS framework, the team without a designer is very good, combined with less perfect results
requirejs : AMD standard module loader, front-end modular trend of the necessary tools
Node.js : JavaScript can also be done in the background, the status of front-end engineers even more
AngularJS : A great tool to do Single Page Application
Mobile Web Development : The popularity of smart phones to mobile terminal traffic is gradually catch up with the PC side
Javascript memory management : SPA long-term operation need to pay attention to memory leaks
High Performance JavaScript (Build Faster Web Application Interfaces)
Best Practices for Speeding Up Your Web Site : Important Skills
Some personal experience
LingyuCoder learning experience
The above gods are almost summed up, I would like to talk about some nonsense here

####tool

chrome dev tools: front-end development debugging tools, pay attention to several features:
console
Elements: element style adjustment, very common
sources: adding breakpoints in the code, single-step debugging, and single-step debugging to see objects in memory
watch expression: View the current memory value by expression
call stack: View the call stack, open async, you can see the asynchronous call stack (this is very useful, especially when ajax debugging)
scope variables: variables on the scope chain, very useful
network: capture package view each request, very important, before and after the end of the joint adjustment
timeline: analysis of rendering, js implementation, etc. Each stage, performance optimization weapon
emulation: Simulation of mobile environment, mobile page development essential
Some plugins:
liveload: Automatic refresh after modifying the page, do not press F5
dimensions: Cutlery measured directly on the page
livestyle: css style automatically modify the effect, do not need to refresh, the elements can be synchronized to modify the code
image tool: measure, take color
UC two-dimensional code: Mobile debugging code necessary
pagespeed, YSlow: page performance analysis and optimization plug-ins
Mark fly like: excellent online markdown editor, write weekly quick report
sublime text2: easy coding, plug-in, fast, good performance
emmet: essential to improve the html encoding speed
sublimelinter + lint and hint in various languages: Code error correction
Some snippets: auto complete, improve development efficiency
Intellij IDEA and WebStorm: Integrated Development Environment that integrates a variety of features, development easier than sublime, but will eat more performance
Mark Men: measuring, color, marking weapon, get the visual version of the first open software
GFW Fucker: I use apricot, if you can buy a virtual server as a ladder
iHosts: Very good hosts management software, easy to modify hosts, development and debugging necessary
Charles: The best capture capture tool for the Mac platform
Rythem: AlloyTeam agent capture software package, very lightweight, easy to install, mobile (real machine) development and debugging is very good
Wunderlist: a very good Todo List, the task, when the demand is more convenient to manage it
#### Skills Front-end skills In fact, in addition to JavaScript (including NodeJS), HTML, CSS, there are many. In fact, a large front-end skills tree, where only listed in some of my development to talk about ##### language based JavaScript:

Scope chain, closure, runtime context, this
Prototype chain, inheritance
NodeJS basics and common APIs
CSS:

Selector
Browser compatibility and common hack handling
CSS layout methods and principles (box model, BFC, IFC, etc.)
CSS 3, such as animation, gradient, and so on
HTML:

Semantic label
##### Advanced JavaScript:

Asynchronous (Promise, ES6 generator, Async)
Modular development methods (AMD, CMD, KMD, etc.)
JavaScript interpreter some related knowledge
Asynchronous IO implementation
Garbage collection
Event queue
Commonly used framework and its principles
jQuery: based on the selector framework, but personally think that can not be called the framework, it should be regarded as a tool library, because it does not have the module loading mechanism, in which the source is suitable for reading
MVVM framework like AngularJS / Avalon: Focus on understanding the concept of MVVM itself and the realization of two-way binding, how to decouple
underscore: excellent tool library, easy to understand common tool code fragment implementation
polymer / React: component development, future-oriented, understanding of the principles of component development
CSS and HTML: Mainly CSS3 features and HTML5 features, as well as the browser process and drawing principles

DOM tree, CSSOM tree, render tree construction process and page rendering process
Parse HTML, CSS, JavaScript blocking
HTML5 related
SVG and vector theory
Canvas development and animation theory (frame animation)
Video and Audio
flex box layout
use of icon fonts
Common NodeJs package:

koa
express
underscore
async
gulp
grunt
connect
request
Some ideas:

Responsive Web
Elegant downgrade, progressive enhancement
don`t make me think
Web page usability, accessibility, what it means
SEO search engine optimization, understand the principle of search engine
SPA benefits and problems
Performance Optimization:

Reduce the number of requests (sprite, combo)
Application cache (http cache, CDN, localstorage, sessionstorage, memo mode)
Reduce selector consumption (right to left), reduce DOM operations (DOM and JavaScript interpreter separation)
CSS reflow and redraw
#####project

Version Management: devaluation Git, used Git will not want to use SVN
Git: Local version management mechanism
SVN: Remote Center version management mechanism
Automated build: Primarily less, template, coffee, etc. Preprocessing and code compression and consolidation
Gulp: Stream-based, fast, good module
Grunt: Independent tasks build, slow, egg-shaped configuration, high flexibility
Pre-processing and template engine
less: Simple syntax, but limited functionality
jade, ejs, velocity and other template engine, each has its own strengths
coffee: python engineer favorite, I have never used
Environment to build: The main line of code is mapped to the local and start a demo server locally, as mock simulation data, a matter of opinion
Local Agent: ihosts
Automated testing: in the case of more stable business, you can reduce the number of test events by automating the test, but when the need is high, the cost of maintaining test cases can be high, and it may be counterproductive with automated tests
jasmine
mocha
ecosystem
npm
bower
spm
Build a blog of your own
git pages
hexo
jekyll
#####future

Web Componets: Component-oriented development for the future
HTML template
Shadow DOM
Custom Elements
HTML Import
Mobile development: This is also need to understand, after the front-end engineers will often deal with the webview, but also to understand native development
##### Some other things are not test code can be done, I feel a lot of time involved in internships, these are what I met and I feel bad place to do

Thinking about the business : I am personally very deficient in this area, so on the front, more thought before knocking code business
Communication and communication skills: This is very important. The front end also needs to deal with the project manager, products, interaction and background. Poor communication can cause a lot of uselessness and delay the project
Knowledge management, time management: the balance of input and output, output is the best input. How to share, participate in the community, make exchanges, make a record
The desire for new technology, and dare to try
#### Getting Started Getting started can be done by eating the book, but many of the things in the book are outdated, and while you're still learning about the book, keep watching the new developments in technology. Here are a few books I feel good:

"JavaScript Advanced Programming": can be used as a primer book, but also a high-level book, you can quickly absorb the foundation, wait until the upgrade and then come back to see
"JavaScript authoritative guide": not suitable for entry, but essential, do not understand where to go look up, very helpful
"Write maintainable JavaScript" and:
Node.js Development Guide: Good Nodejs starter book
"Easy to understand Node.js": Nodejs Advanced Books, essential
JavaScript Asynchronous Programming: Understanding JS Asynchronous Programming Concepts
"JavaScript Patterns" and "JavaScript Design Patterns": JavaScript's code patterns and design patterns that transform development thinking into JavaScript, very good books
"JavaScript framework design": At the same time with the wheel, you should know how to turn the wheel, explain in great detail, from the source level to explain the realization of the various parts of the framework, with an existing framework to read, you can learn a lot
"Don`t make me think": the concept of web design, user behavior, very good
"CSS Zen Garden": an enduring piece of work, also passed the concept of web design and design issues that need attention
"High-Performance JavaScript" and "High-Performance HTML5": A book that emphasizes performance, not just performance tuning, but also a lot of fundamentals worth learning
"HTML5 Canvas Core Technology": The book I am reading is very helpful for canvas usage, animation implementation, and animation framework development
"HTTP authority guide": HTTP protocol necessary, front-end development and debugging will often be involved when the knowledge
"Responsive Web Design": Technology itself is not difficult, it is important that the design concept of responsive web pages, as well as mobile first thought
"JavaScript language essence": the path of the book, but also universal JavaScript development thinking a good book, very suitable for getting started
#### some nice websites

Github : Nothing to say, read more of the source code, and upload your own source code, to learn from the big cattle around the world
codepen : feel the beauty of the front of the place, there are a lot of cool effects and excellent plug-ins
echojs : Quickly understand js new information website
stackoverflow and segmentfault : Basically a variety of questions can be answered above
google web fundamentals : Each article is suitable for careful reading
static files : open CDN, good use
iconfont : Ali's vector icon library, very good, support CDN and support projects
Html5 rocks : a nice site, many new browser features, and cutting-edge technology, can find articles on this
css tricks : How to make use of CSS, as well as learn about CSS new features, here to meet you
JavaScript Secret Garden JavaScript beginner must see, very good
w3cplus : a front-end learning site, the quality of the articles inside are pretty good
node school : a good node learning website
learn git branch : A git learning site that interacts well
Front-end chaos stew : a front-end article sharing community, there are many excellent articles
Regular expression : a regular expression tutorial, very worth a visit
Ruan Yifeng's blog and Zhang Xinxu's blog : A quick way to learn about some of your knowledge, but if you need to dig deeper , you need other resources
Daniel cattle blog: This is too much, do not paste, know there is a very full
Various specifications of the official website, do not know when to read norms
#### Course Before doing Java SSH, half-way out of the front, so the level is relatively weak, more problems encountered. Basically get started by reading books and tutorials at the W3C School , as well as some front-end blogs, such as Uncle Tom's blog . Previously just use jQuery, js did not study too much native, then gradually read a lot of animal books, such as the essence of the language and so on. I learned a lot of linguistic knowledge from these books. But this is obviously not enough, so I often go to the community to see what people are talking about, and then go to see the relevant information, interested will find more information to see, or write a demo. Learning CSS is mainly through this approach. Later, I started to pay more attention to Daniel's blog and some of the more profound books, and pay attention to some new knowledge and framework, and continue to hand-submit code to github, so also learned a lot of knowledge. In the internship process, personally involved in the actual project development, can learn a lot of ideas and thinking can not be learned in school, which is also a great help. Do not say, I'm going to move brick and offer ...

MrRaindrop 's learning experience
Should be invited to share qiu God front-end learning experience, here on the front end of the knowledge architecture is not summarized, you big God's summary has been quite place, and I will contribute a few personally think it is more useful links , And then mainly to share the problems I encountered in the front-end learning process and lessons learned, if you can help to get started introductory FE beginners (I tentatively assumed to be the audience type of this article), so that they less Take a detour, every step you know the direction of the next step, this is the best. For the summing up and sharing of God you see FEI learning arranged by qiu god .

Say first, the front end of this thing everyone can have their own learning methods, this is for reference only, write a bit messy, you make do.

origin
I belong to the wrong type of collision into the front, has been to do the direction of the game before, engage in the game site, played the game engine, such as unity, unreal this commercial engine, fiddle with a few game prototype, but since the fight Research into the laboratory, sent directly to the instructor js wrote, the mentor gave me half a month to let me write a Baidu map api data display page, although this time is still quite generous, but not how to write After js, will not use the map api, so I nibbling the "Guide to Javascript" (rhinoceros book) while referring to the laboratory code left behind by the predecessor, and finally write down all the features. That page count my js entry made, but also the beginning of my front-end learning route.

Now think about it, although assigned to do front-end, but has been done and still have to rely on interest to maintain, of course, the front end is a fun technical field, and the community is very "lively every day."

Project, the next project
Personally, I think the front-end learning, beginner stage you can completely divorced from the book, project-driven . Although I personally start eating from a rhinoceros book, do not be like me if you do not have enough time, or if you think it's boring and boring. Of course, if you decide to eat the best book is to follow the book examples are knocked over again. I did not contact before the study js, April did not go to school it was directly dumped a mentor Baidu map api project to the face, followed by a variety of ERP, map data display, although for the design to a little not heavy , But basically are front-end live, SSH and android development also played soy sauce, the whole laboratory to write a front-end dare I believe? Rich client SPA era backend is a restful interface, the amount of code are basically in the front ah, I wrote a person how a cool word ... During the period with the mentor to feel a start-up every day from 7:00 10 o'clock at night, can be considered a period of rapid growth.

Master a technology first grasp its general framework, think of an idea can be achieved, to be able to run on a demo, and then to improve its details, until the demo is completed, this technology has a perceptual knowledge, and then To eat book, the harvest will be much larger. I started writing native js jquery, to extjs, then to angularjs, from the mentor designated technology to do their own technical selection, a project followed by a project practice, just like Daguai upgrade like. Of course, without a project to create their own projects, to start their own ideas is a matter of fun and accomplishment.

Collecting addiction and knowledge management
There are characteristics of front-end learning, a lot of things are fragmented, scattered, you need to organize, summarize and summarize. Weibo, know almost follow the many gods, you not only to listen to gossip, the gods only words sometimes leave is the endless aftertaste, it is possible that a word inadvertently mentioned to become your next one The goal of learning. Collect this information, make good use of google, ask questions, think. Just like the elements of the game collection, front-end learning is also a "game" full of elements of collection, except that you need a knowledge management tool to serve as inventory and warehouse, and all I know are serious about knowledge management tools user. Previously used oneNote, then not yet bound to the cloud storage, and now basically Evernote, notes have accumulated to 1200+ articles. Bookmark always intended to use delicious, because it is based on the tag management, but has been useless. Of course, the focus is not on these tools, but handy tools can improve your learning efficiency. Of course, the key is always to maintain a strong desire to learn . Your goal is to understand everything about the front end (not all of course is something you have to master as you have limited energy, and in reality it is unlikely).

Follow God
This controllability seemingly not big ... with the boss did not say much, to a certain extent depends on good fortune. But having said that, more exchanges with the experts around him is king, the master does not have to be high, but must have passion for technology. When I was a researcher, I went to the lab door every day at 7 o'clock and I found out that a guy was even older than me. Later found that this guy left in the morning, Afternoon came again, and the mentor on this accustomed to, the original guy did not sleep at night writing code, ran back to sleep in the morning. Later, often with the God to discuss the issue, every time I experience the value of Cengru rub to rise. Then there was another God in the lab who was described by the night-time angels as "can only look back and keep chasing and never catch up". The two gods all know something about everything, so I can discuss anything with you Well, I have a period of time to do a reading plan, from c / c + + to vc / mfc to unix network programming, the last one to see java core technology and C # programming guide on MSDN, and God can also pull very high

In short, these two gods pulled me into the pit, or jumped from one pit to another. Although both gods did not engage in front-end, there was always the same connection between technologies.

reading
Study, read more books, read a good book. You see in Liu's blog that there is a formula in your first month's salary equal to the sum of the prices of technical books you bought (read) before ( in the technical book, those classic, well-recognized good books). It seems pointless to discuss the correctness of this formula, but its rationality is no doubt that it is to read more classical technical books. At its most extreme, Google's Yu Xu said in my university that he ransacked the library's entire TP312 bookshelf. For front-end classic books, there was a list of front-end books (if there were missing front ends Classic good book, please leave a message to tell me), the conditions can try to brush these books again, I am also looking for the complete time to gnaw them. Before that, loose knowledge of the front end, the collection of fragmented knowledge points, rapid learning from the blog, etc., these are just one aspect of front-end learning, if you want to understand a knowledge system, understand its ins and outs, establish a systematic understanding of it Reading classics is still essential.

I started to eat the rhinoceros book, and then went to see some of the other classic front-end technology books, and then later through the laboratory project and get some small projects gradually on the road ahead of the field, look after Javascript mode "," Javascript design mode "," write maintainable Javascript ", and later learned that node and started using node to do some gadgets, and read the" NodeJS up and run "and" Mongodb authoritative guide " , But the feeling of the former slightly pit. Then there Pu Ling that the profound things in simple language (the book so da) did not come out, and later went out to borrow the library to read, so look down feel pretty good, but still feel less than expected, but also need to continue Brush (refer to the above book column).

Front-end positioning
The positioning of the front ends depends on what kind of knowledge and skills you need to absorb and determine what you need to be particularly sensitive in the tech world. If you think the front end just stays on the cut page to fulfill the requirements of interaction and vision, then your understanding of the front end is still in its infancy. Ali, the end of the examiner asked me such a question: the ever-changing front-end technology, the scope of the broader and wider, more and more standards, it seems that any one tentacles can reach far. How to front a suitable positioning? The examiner gave me an analysis for a long time, and then summed up in one sentence, that is, the user and the site's connector, the creator of user experience (the original is not the case, but generally the meaning). In other words, the ultimate goal of the front end is actually to create a user experience, enhance the user experience, and take the user experience as the center . Whether you start from interactive design, or optimize from a performance perspective, or improve the workflow to improve workflow efficiency, the ultimate goal is to create and enhance the user experience, ultimately reflecting the user experience. I think this summary is very reasonable (of course, "user experience" is too broad, and not just the scope of front-end engineers, such as the development of the background of a data processing process to optimize and enhance the overall performance, which is also the user An improvement of experience).

Currently, front-end engineers will inevitably come into contact with a lot of deeper issues than cutting pages, realizing visual requirements and realizing interaction, such as front-end automation, image programming, performance optimization, and so on, and pushing PHP / JSP / ASP / nodeJs, the past back-end templates generally belong to the back-end category, and now with the evolution of the front-end architecture , you may want to write the back-end template code, you need to use backend language (PHP / Java / C #, etc.) This is what is called a big front end (however , this is not a departure from the positioning of the front end, and the part of the front end processing that is still in contact with the user is still an optimization of the user experience). Perhaps the most common or most talked about is the node, in fact, these types of technology can be selected, bat is said Baidu Baidu more than PHP, Ali with more nodes.

Uncle mentioned in his blog so-called full-width is horizontal, the whole stack is vertical. All the terminals that all the terminals are the front end, because they are related to the user experience, direct contact with the user. Adapt to the development of multi-terminal, requires you to be based on the web front end, may also want to extend the knowledge of android development and ios development, Fortunately, due to the prevalence of hybrid development methods, the skills used to develop the native language will not be so deep .

The whole stack can be said that the most suitable for a startup type of development, in a broad sense, is considered from the front to the back-end, from development to operation and maintenance, this does not say, most people should not want to go in this direction Development, you want to become full-stack dev in this sense, may not need to look at my article; the narrow sense of the whole stack specifically refers to the use of js language from the front-end write erected in the nodeJs on the back end, Before and after the end of a unified language, unified programming model, or even common code. Learn more about the development of the full stack You can look at the full-stack engineer Yupi talk about this .

These are some superficial understandings of the front-end and the derived technical route, and it is still important to learn how one area masters its overall course and trend. In addition, if you want to have a holistic understanding of the front-end learning direction and career growth path, we recommend you to look at the front-end development on the 10th day of the conclusion .

At last
Contribute a few links to front-end learning, interview helpful:

Front-end-interview-questions collection (Front-end-Developer-Interview-Questions)
Front-end skills summary (JacksonTian)
Another front-end skills summary map
Front-end that thing (book column)
byr forum yiyizym suggestion
Learning gulp is easier than grunt

Do SPA, recommended backbone.js and backbone.marionette.js

Do not toss over the wall, spend ten bucks to buy a month of apricot.

It's okay to play the basics and learn again.

html nothing to say, free to learn html5.

css try to look at the document , because many Chinese data are held one, see more but confused.

A website can find html / css tags, attribute support in all browsers, very good.

javascript to see javascript advanced programming. However, read such a thick book will forget. Explain the core concept of javascript: object / prototype chain / constructor / execution context / scope chain / closure / this, there is a good article here .

Have time to look ecmascript 6, plans to release in June next year. Ruan Yifeng's website has entry information.

There are many jquery API, this site can be easily found. Have time to figure out the usage of jquery deferred.

More to sublimetext plug-in, for example, check the code is wrong, create a new directory file, organize the code.
