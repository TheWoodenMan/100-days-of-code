# 100 Days Of Code - Log

### Day 1: March 16, 2022
##### 
**Today's Progress**: Finished Guess the Number Project, last commit to github done and project made project.
Moving on to the next exercise which is about modal windows operated by buttons which change class using 
document.querySelector and eventlisteners. 

**Thoughts:** 
Most of the debug mistakes I am making came down to class/id symbol being dropped or simply bracket mis-alignments.
I am getting more confident in calling the DOM though and have a few good ideas for future projects and/or updating
the guess the number project beyond the basic requirements.

I need to implement the modal window changes to a project for me to really remember how it works, if the JS course doesn't
do that, I'm going to adapt one of the freecodeacademy projects I finished to do it instead.

**Link to work:** 

1. [Guess-the-Number](https://github.com/TheWoodenMan/Guess-the-Number)

_______________________________________________________________________


### Day 2: March 17, 2022

**Today's Progress**:
1. I completed 2 pages of the 30 days of JavaScript, primarily as revision but also because I've realised that different developers and tutors put different emphasis on coding fundamentals, or have different projects or exercises which will help me with knowledge retention. I can skip the parts I know and focus on the extra detail.  the 30 days course is very comprehensive and as it's in written format, it's easy to digest quickly. 
2. I completed the ES6 Section of basic Javascript - freecodecamp , learning more about the uses of const/var, arrow functions, default parameters, rest parameter, spread operator, destructuring assignment, Template literal, class syntax, getters and setters, export/import function, promise functions, resolving promises with result/catch,


**Thoughts**

There are a bunch of math/string options that haven't really been properly explored yet. it's worth knowing that in future so I can simply look them up if needed.

I'm currently alternating my learning between three main sources, **jonas.io Complete Javascript Bootcamp** which has already covered the fundamentals and is now project based which is good but it's quite carefully led, **freecodecamp** which tends to be heavily scripted, fairly technical and rigid - but very challenging. and **30 Days of Javascript** which is text based, but very well explained, the exercises at the end let you practice what you need to learn but it's fluid and free-form.

I've come to the conclusion that I learn less from freecodecamp than I do when im writing my own code examples. freecodecamp has good detail but it feels more like 
"crossword puzzle" style challenges that need to be solved so you can pass to the next, I need practical application to really learn and remember. There is a lot of great content in there however and it's structured in a sensible, methodical way that builds up over time. I need to devise projects that implement the code structures I learned in freecodecamp JS ES6 - I feel like I have good awareness but not aptitude yet - I need more direct experience.

I much prefer working with visual studio code, it is intuitive and keeps me on the right path 99% of the time.


**Link(s) to work**

1. https://github.com/TheWoodenMan/30-Days-of-Javascript-Exercises
2. https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-javascript 

_______________________________________________________________________

### Day 3: March 18, 2022

**Today's Progress**:
1. Finished the L3 exercises in Day 2 and started Day 3 of 30 Days of JavaScript
2. started the Regular Expressions (regex) part of freecodecamp, I will work my way through this but it's unlikely i'll finish today.
3. I started reading "the javascript way" as revision on the recommendation of a fellow 100 days student :) it reads well and gets straight to the point which I like a lot.

**Thoughts**

1. Day 2 of 30 days was good because it covered things I haven't seen yet, but day 3 seems like mostly maths, boolean and operators that i've seen before. I'll skim through and skip to the exercises and try to do them blind as a challenge. confirm() was new, time functions were also new to me.
2. Most of the exercises were ok, I had to backtrack and check time functions because they're new to me. I am actually good on writing conditional functions on the fly now, I just need to make sure I alternate between arrow functions, ternary operators and different variations on things in general so I can diversify my range a bit and not just fall into the same functions all the time.

**Link(s) to work**

1. https://github.com/TheWoodenMan/30-Days-of-Javascript-Exercises

_______________________________________________________________________
### Day 4: March 19, 2022

**Today's Progress**:
1. Completed the regular expressions section of freecodecamp, this was quite difficult!
2. Finished the exercises at the end of day 3 for 30 days of JS which were quite easy - I'm getting good at functions!
3. Started debugging section of freecodecamp.

**Thoughts**
1. it's good to have worked through reg expressions in a methodical way, I understand the syntax now but maybe dont see how I could use this usefully yet.
2. the "restrict possible usernames" problem on freecodecamp is currently blowing my mind, and from the comments I can see Im not the only one. I am 99% done and determined not to look up spoilers! haha i did it!

<code>let username = "JackOfAllTrades";</code><br/>
<code>let userCheck = /^[a-z]+([a-z]+|[\d][\d]+)\d*$/i; // Change this line</code></br>
<code>let result = userCheck.test(username);</code></br>

3. I have a little experience at debugging already from the jonas.io bootcamp and I quite enjoy it. Looking forward to seeing how freecodecamp recommend you do it.
4. practical applications of regex are more apparent now, restricting usernames and passwords for example, already in use all over the world. The ability to extract only the information you need, there are a few good excel projects i've worked on that would love the specificity of that function.
5. i'm getting curious about some of the various frameworks attached to JS, react.js and vue.js for example. I'm interested in how these can enhance the already quite fluid functionality.
6. I need to revise time operations, I still don't 100% understand the maths of it, unix time and formatting for example.

7. Repeating capture groups really kicked my ass to be honest, I found the syntax kind of unintuitive initially, but honestly it's completely logical, and whenever I looked up a solution it was always totall understandable. I will keep going on this and need to explore the exact definitions more to gain aptitude on it. 

**Link(s) to work**

1. https://github.com/TheWoodenMan/30-Days-of-Javascript-Exercises
2. https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#regular-expressions


_______________________________________________________________________
### Day 5: March 20, 2022

**Today's Progress**:
1. Started codewars - Worked through some of the introductory challenges and graded in at 8th kyu.
2. Started and COMPLETED! the Data Structures part of freecodecamp and am now more than half way through.

**Thoughts**
1. I picked up more JS than I realised, when presented with a problem, I have been able to leverage quite a few different techniques and to come at the problem from different angles if needed.
2. If i'm rushed or interrupted for any reason, family or w/e I make more mistakes
3. always check spelling/typo/bracket errors first because these are by far the most common.
4. Slice() and Splice() are functionally very different and the inputs can be deceptively similar, 
remember: splice(x, y) x is the index, y is the number to remove. slice(x, y) x is the start index and y is the end index (up to, not including).
4. freecodecamp is like a dictionary-like step-by-step run through of Javascript fundamentals, but it doesn't really test applications. I need to flip back to project work to really learn some of this stuff in practice.
5. I gained a lot of confidence in working with arrays and objects todays, one of the problems in particular was very difficult but I managed to research my way out of it. 
6. I seem to have a tendancy of overcomplicating challenges *slightly* I sometimes mis-read the question and either add in features that aren't 100% needed, or just see the potential for those features and try to add them in as a bonus. I need to be better at sticking to the brief, so I'll be adding assignment objectives to my code to keep me focused on the end-goals so I don't waste any time.

**Link(s) to work**
1. https://github.com/TheWoodenMan/Bootcamp-Exercises
2. https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-data-structures
_______________________________________________________________________
### Day 6: March 21, 2022

**Today's Progress**:

1. Completed the "Categorize new Member" kata on codewars.
2. Ran through the "pig game" project on Complete Javascript '22
3. Completely Finished pig-game and committed it to github!
4. Gained aptitude in eventlisteners and changing elements using queryselector/getelementid
5. Learned about toggle/add/remove to change class elements.
6. Started Basic Algorithm Scripting Chapter of Freecodeacademy.

**Thoughts**
1. I was able to solve the categorise problem really easily with a simple for loop, if statement and push.
2. I think it would be healthy to at least try one codewar problem per day, even If i can't solve it, it's good to see what code i'm able to leverage intuitively.
3. The pace of the Jonas' javascript course on udemy is a little slow but it's extremely good at explaining the detail of what is going on, I always retain the knowledge of what is being explained.
4. I have been trying to pause the videos at the beginning of every new feature so I can try and do it myself and although I didn't follow the exact same path of the instructor - I was able to produce a working product at each step which was fantastic.

**Link(s) to work**

1. https://www.codewars.com/kata/5502c9e7b3216ec63c0001aa/solutions/javascript/me/best_practice
2. https://github.com/TheWoodenMan/Pig-Game---Basic-Dice-Game

_______________________________________________________________________
### Day 7: March 22, 2022

**Today's Progress**:
1. Started codewars problem "Persistence"
2. Started "how does javascript work" section of complete javascript course '22
3. Made a little progress in FCC algorithms solving the "Return Largest Number in Arrays" problem and "confirm the ending"

**Thoughts**

1. hoo boy is this a hard one, I spent a few hours on persistence and wrote some good functions. one checks if an array only has one digit or not, another converts a number to a string, then an array - BUT I learned that it's possible to just do this with toString.split("");
2. I've noticed 2 more tendencies I need to iron out - 1) I have a tendency to overcomplicate things (and that there is usually a javascript command to shortcut common functions. and 2) READ THE QUESTION CAREFULLY. For this problem I had been trying to report the single digit number at the end - but the question asks for a count of the number of steps!!
3. despite my setbacks, I learned more in detail about recursion, toString, .slice and .map so it's not all bad news! persistence is the name of the game ;)
4. Largest arrays was largely revision but I did have to nest a for loop, (which caused a few issues) and deal with negative numbers.
5. confirm the ending was pleasantly easy and probably a good point to spot at :)

**Link(s) to work**

1. https://github.com/TheWoodenMan/Bootcamp-Exercises/blob/main/codewars.js
2. https://github.com/TheWoodenMan/Bootcamp-Exercises/blob/main/fccalgorithms.js
_______________________________________________________________________
### Day 8: March 23, 2022

**Today's Progress**:
1. Completed the first 10 exercises of regexone
2. Completely finished the algorithm section of freecodecamp.

**Thoughts**

1. my regex comprehension is only going to get better if I find ways to either implement it more or use practice exercises to develop it.
2. Algorithms was a huge undertaking, I spent around 6 hours on this but stayed on it til it was done. Some of the challenges I solved easily in a few minutes.  Other challenges I spent a few hours on trying out various techniques I already knew and reading up and trying new ones where i didn't.
3. It takes longer to do this way but I would rather stay on it instead of looking up the answer directly, both as a way to test my skills and to reinforce my ability to quickly work out how to do something.
4. I'm noticing that a lot of the "core" systems in Javascript often have shortcut commands that can abbreviate them quickly and easily, I will often reach for function building and for loops to iterate through arrays and solve problems as a default, but I need to diversify and learn more techniques.

**Link(s) to work**

_______________________________________________________________________
### Day 9: March 24, 2022

**Today's Progress**:

1. Day 5 of 30 Days of Javascript, and exercises level 1
2. Regexone lessons 10-15 Completing the introduction.
3. Continued - how does javascript work? - Complete Javascript Course '22 

**Thoughts**
1. Day 4 of 30 Days was already done and was mainly about conditionals which I know quite well, so i've moved to day 5 which is about Arrays. I'm using the 30 days as revision and practice exercises mainly so it's not a big deal if it doesn't match up with the 100 days schedule. 
2. I self tested on Array commands and got 14/16, needed to look up .fill and .lastIndexOf which I hadn't encountered yet. I got .splice and .toString, but was a little fluffy on syntax so I re-read them.
3. I found a nice program for testing out regular expressions which breaks down the characters and explains what's happening https://regex101.com/

**Link(s) to work**

1. https://github.com/TheWoodenMan/30-Days-Of-JavaScript/blob/master/05_Day_Arrays/05_day_arrays.md
2. https://github.com/TheWoodenMan/Bootcamp-Exercises

_______________________________________________________________________
### Day 10: March 25, 2022

**Today's Progress**:

1. Watched the explanation videos on .this functionality on Complete Javascript '22
2. Started Object Oriented Programming on freecodecamp.

**Thoughts**

1. "how javascript works" is incredibly dry, but it's also already proved very useful. I just need to break it up with exercises.
2. I totally forgot about the "persistence" challenge on codewars and need to get back to it.

**Link(s) to work**

_______________________________________________________________________
### Day 11: March 26, 2022

**Today's Progress**:

1. Continued the freecodecamp section on Object Oriented Programming
2. Completed! Object Oriented Programming,
3. Started Day 6 of 30 Days of JS - Loops

**Thoughts**

1. Object Oriented is going quickly and it's quite intiuitive, need to slow down a little to make sure I am properly comprehending and retaining the information.
2. I slowed it down a LOT and am going through step by step, I need a challenge to really get this stuff to stick to my brain though.
3. This makes a lot of sense and I understand the structure of whats happening, but I need practice so I don't forget the specific syntax of how this works,
4. Before I move onto functional programming, I will go back to complete javascript on udemy and work on OOP.

**Link(s) to work**

1.https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#object-oriented-programming
2.https://github.com/TheWoodenMan/Bootcamp-Exercises
3.https://github.com/TheWoodenMan/30-Days-Of-JavaScript/blob/master/06_Day_Loops/06_day_loops.md 

_______________________________________________________________________
### Day 12: March 27, 2022

**Today's Progress**:

1. Made another attempt at codewars "persistance"
2. Revised for loops.

**Thoughts**

1. this is a tough one, I tried a new angle, made a little progress. I broke the problem down into steps and sucecssfully made a few functions to help.
 
 -  a function to get the length of any number</br>
 <code>function checkLength(number) {</code></br>
 <code>return number.toString().length;}</code></br>
 
 - a function to convert any number into a series of individual numbers in an array:</br>
  <code>function numberToArray(number) {</code></br>
  <code>let tempArray = number.toString().split("");</code></br>
  <code>const numArray = tempArray.map((x) => parseInt(x));</code></br>
  <code>return numArray}</code></br>
  
These both worked well and did the job, but the part I am struggling with comes next where I have to factorise the array and count each step, outputting the number of steps it takes to get to one digit. I suspect i have to use recursion which isn't fully understood yet. I will sleep on it for now and come back to it fresh later.
this challenge is 6th kyu and i'm 8th so it is probably supposed to be quite difficult.

2. I went into detail on for loops, main differences between do and do while is in whether the expression gets executed before or after the condition is checked for repeat. Whenever I do revision like this I find I am picking up more and more detail each time, especially when I go to different instructors who focus on different things.
3. This section is broadening my understanding of maths in javascript, use of Math.trunc Math.random and the modulus character to generate or determine certain numbers.

**Link(s) to work**

1. https://www.codewars.com/users/TheWoodenMan/completed
2. https://github.com/TheWoodenMan/30-days-of-javascript-exercises
_______________________________________________________________________
### Day 13: March 28, 2022

**Today's Progress**:

1. 30 days of javascript day 6 exercises 2
2.

**Thoughts**

1. The difficulty has ramped up a little with these and I am having to research other commands i've not used yet (charAt) and working in different character types like hexadecimal, uft-16 and what they mean, but thats kind of healthy.
2. I made an observation about my coding learning, I have probably been a little too stubborn in doing things myself, probably wasting a lot of time on things that I could have just looked up or that have simpler ways of solving. I need to recognise that i'm still at the start of my coding journey and likely will need a lot of help and lookups from others.
3. A good example of this is in the 30 days exercise where i had to make a RNG alpha-numeric generator, last week I probably would have stayed on this for a few hours but after maybe 30 mins I just looked up how to do it, saving a lot of time and frustration and then learning about new commands. Immediately after that I was able ot adapt the code and made a nice little function to generate a random hex color which i'm really quite happy about! (and then another one that randomizes an RGB):
  
  <code>function randHex() {</code></br>
  <code>let output = "";</code></br>
  <code>let hexChar = "";</code></br>
  <code>for (let i = 0; i < 3; i++) {</code></br>
  <code>  hexChar = Math.floor(Math.random() * 255).toString(16);</code></br>
  <code>  output += hexChar}</code></br>
  <code>return `#${output}`}</code></br>
  
4. I picked up an amazing little detail that has been causing bugs - if you empty a subArray for reuse - it resets all copies and instances of that array!! (edit - because of references staying the same when you use const to define an array, use let to create a new memory reference that is independant of the source array)
5. https://blog.greenroots.info/ways-to-empty-an-array-in-javascript-and-the-consequences Thanks to this blog link that explains it I managed to modify my code. The two ways I know to empty an array have different consequences, array.length = 0 mutates the original which references all instances of that array. array = []; only works if the array is defined using let and allows the array to be updated independantly from it's original reference, this solved the problem and gave me some valuable information. 

**Link(s) to work**

 1. https://github.com/TheWoodenMan/30-days-of-javascript-exercises
 2. https://github.com/TheWoodenMan/30-Days-Of-JavaScript/blob/master/06_Day_Loops/06_day_loops.md
_______________________________________________________________________
### Day 14: March 29, 2022

**Today's Progress**:

1. Attended #100devs live stream with @Leonnoel.
2. Completed a number of live challenges coding along with the stream.
3. Started Microsoft "What is Github?" Training.
4. Read through the documentation about git. 

**Thoughts**

1. Ive been using github for a while but didn't really use every feature thats available, until I start contributing to projects maybe it won't be so possible. I am reading the full guide so I can pick up on fork, clone, branch etc and really understand what is going on.
2. I coded along with a dev-stream, it was really good! I learned a bunch of stuff as well as revised things I already know. 
3. I got some practice creating objects, creating them manually and also via constructor.

**Link(s) to work**

1. https://docs.microsoft.com/en-us/learn/modules/introduction-to-github/1-introduction
2. https://docs.github.com/en/get-started/using-git/about-git
3. https://github.com/TheWoodenMan/100Devs

_______________________________________________________________________

### Day 15: March 30, 2022

**Today's Progress**:

1. I forked, created a branch, cloned a repository, changed it, commited it, then compared and submitted a pull request all in github. This is in line with the first-contributions guide on github and linked from microsoft.
2. I am following a guide on how to contribute to open source for absolute beginners https://www.firsttimersonly.com/ there are a bunch of really interesting open source projects on here that I could contribute to in the future when I get more skill.
3. I completed the "How does Javascript work?" part of the complete javascrpt bootcamp. all about primitives vs reference types. Moving on now to section 9 - "Data Structures, Modern Operators and Strings"
4. I went back to codewars and completed "Merge two sorted arrays into one", "Sum of Positive", "Square(n) Sum".
5. I ranked up to 7th kyu on codewars.
6. I joined a stream with 100 devs rufio and coded along in codewars.
7. I did it! I solved "Alphabetical Grid" on codewars with no help, no lookups!

**Thoughts**

1.  While completing the first codewars task I learned about some new techniques, firstly the Set() constructor, which creates an object that is a set of elements, can be primitives or object references.  Set checks equality and so each value is not duplicated if it already exists, so it can be good for merging two arrays if the elements need to be unique. Set accepts add, clear, delete methods. 
2. when using sort() if you leave it blank it will sort in ascending order, but as if they were strings, which means numbers like 10 will be sorted like 1, 10, 2, 3 etc to counteract this, we can add parameters to sort to specify how we want it to be processed. e.g. <br>

<code>(a,b) => a-b)</code> 

will sort the subject of sort with an arrow function in ascending format as if they were numbers.

3. I came up with a totally different method to solve "sum of positive" than the streamer but it still worked out, the coding style was much shorter though, almost a one liner.
4. I respond well to pressure, I will maybe try doing codewars on a timer in future since doing it before the streamer got a chance to explain seemed to really click for me.
5. I'd been stuck on alphabetical grid for the last 3 days on codewars, the problem was with what happens to the grid when you go beyond the first 26 characters of the alphabet, it needs to repeat again. Basically I solved the problem by a) taking a break from it. b) thinking really carefully about the math required to get the correct number and building a short if statement that screens for values > 26 of i

this was all it took:<br>
<code>if (i + j < 27) {                                  </code><br>
<code>     sumRef = i + j;                               </code><br>
<code>  } else if (i + j >= 27) {                        </code><br>
<code>    sumRef = i + j - 26 * Math.floor((i + j) / 26);</code><br>
<code>  }                                                </code><br>

**Link(s) to work**

1. https://github.com/firstcontributions/first-contributions
2. https://www.codewars.com/kata/5899642f6e1b25935d000161/train/javascript
3. https://www.codewars.com/kata/60a94f1443f8730025d1744b/solutions/javascript
4. https://github.com/TheWoodenMan/30-days-of-javascript-exercises/blob/main/codewars.js
_______________________________________________________________________

### Day 16: March 31, 2022

**Today's Progress**:
 
 1. Completed the "Introduction to Github" module on Microsoft Learn
 2. Attended https://www.twitch.tv/learnwithleon dev stream.
 3. installed gitbash and ubuntu wl, spent a good amount of time revising the terminal basic commands.

**Thoughts**
 
 1. I actually learned terminal CLI over 20 years ago with MS DOS 3.0, 3.22 6.22 Etc I've used linux before, ubunto, debian,
 raspbian and linuxmint. I also used knoppix before as a boot disk and UI so this is all pretty familiar to me.
 2. although the basics of navigating terminal is known to me, I appreciated the git terminal commands, status, init, commit, (esc : wq enter to submit) branch, checkout (branch), merge (branch)

**Link(s) to work**

 1. https://docs.microsoft.com/en-gb/learn/modules/introduction-to-github/
 
_______________________________________________________________________

### Day 17: April 1, 2022

**Today's Progress**:
 
 1. Installed Anki - a card based memorisation aid for helping with information retention esp on commands/syntax.
 2. Revised git/github terminal commands
 3. Continued Complete Javascript '22 looking at Destructoring arrays.
 
**Thoughts**

 1. Feel like I ran out of steam a bit over the last few days, despite getting the minimum time in, I dont think I made as much progress as I would like.
 2. I have to balance my time between coding learning and work demands to be honest, it's just the way it's going to be, on days when work is heavy i'll schedule revision instead of picking up on new information so I can commit to better retention.
 3. I found a pre-build card pack for anki and it looks pretty useful to me, lets see how it goes.
 
**Link(s) to work**

 1. https://kbroman.org/github_tutorial/pages/init.html
 2.
 
_______________________________________________________________________

### Day 18: April 2, 2022

**Today's Progressni 

1. Downloaded, installed & completed a set of anki cards on basic javascript knowledge.
2. Enrolled for the Odin Project
3. Installed Ubuntu to dual boot with windows so I can have a linux runtime environment.
 
 
**Thoughts**
 
1. The anki card system is really good for helping with command and theory retention, it challenges me to "explain" things I "just know" which will help me develop depth of knowledge in the subject.
2. The odin project has a lot of "mindset" style prep right at the start of it which is honestly excellent, many of the other learning sources I have focus only on the code/skills so I can tell this is going to add another dimension to my learning.
3. I used ubuntu before years ago and liked it generally despite how it lined up for gaming etc, for coding it seems to be much more suitable and I spent a few hours configuring vscode and installing supporting programs like gitcola etc.

**Link(s) to work**

1. https://ankiweb.net/shared/info/216021904
2. https://www.theodinproject.com/lessons/foundations-installation-overview

_______________________________________________________________________
### Day 19: April 3, 2022

**Today's Progress**:
 
 1. 💪 20 mins Anki practice ✔️
 2. Odin Project Introduction to Git started
 
 
**Thoughts**

 1. Another fairly light day, I have a backlog of videos to watch now on git/hub so hoping to get some of that done maybe tomorrow
 2. the git explanations go into way more depth than i've seen so far, I think it's worth looking at this properly now
 3. 04/04 - Man I was absolutely shattered yesterday, I'm just happy I managed to get at least some absolute basics done so I could keep up the momentum.
 
**Link(s) to work**

 1. https://www.theodinproject.com/paths/foundations/courses/foundations
 
_______________________________________________________________________
### Day 20: April 4, 2022

**Today's Progress**:
 
 1. Continued with and completed Odin Project Intro to Github.
 2. Started and working through HTML/CSS
 3. Started and finished the recipes project to make a simple website.
 
 
**Thoughts**

 1. I feel pretty comfortable with git commands in terminal now
 2. I covered HTML/CSS in freecodecamp but honestly wasnt 100% proficient in their use, looking forward to refinding that now.
 3. I'm pushing everything I do on odin to github by terminal commands, its a little tricky, e.g. after renaming the repo on github, I had to look up how to push to that repository from my lcoal. <code> git remote set-url origin git://<newurl></code> did the job.
 4. I realised that my earlier github commits weren't really very well described so i'm going to make sure the messaging fits from now.
 
 /* 7 Features of a good Git Commit Message:</br>

-Separate subject from body with a blank line</br>
-Limit the subject line to 50 characters</br>
-Capitalize the subject line</br>
-Do not end the subject line with a period</br>
-Use the imperative mood in the subject line</br>
-Wrap the body at 72 characters</br>
-Use the body to explain what and why vs. how*/

 5. I have a few recipes I can actually share and this is a really nice project that I can put something into (finally!)
 6. I found a much better way of displaying fractions in html <code>&frac12;</code> 
 7. I played around a bit with some javascript on the receipe site just to see how it would fit in. Had an idea to replace any 1/2 with &frac12; automatically by making a function that replaces that exact text with the super/subscript version. it's an interesting little problem, I may give it further thought.
 
**Link(s) to work**

 1. https://thewoodenman.github.io/odin-recipes/
 
_______________________________________________________________________
 ### Day 21: April 5, 2022

**Today's Progress**:
 
 1. Attended 100 Devs skills and marketing development session
 2. Fired through anki cards for the day
 3. continued Odin project section on CSS
 
**Thoughts**

 1. I actually spent several hours on the 100 devs twitch stream it was valuable advice but more career oriented, so although I didn't pick up any coding experience, I gained perspective in industry knowledge.
 2. I'm not great a CSS and looking forward to refining my skills here.

**Link(s) to work**

 1. https://www.theodinproject.com/lessons/foundations-css-foundations
 
_______________________________________________________________________
 ### Day 22: April 6, 2022

**Today's Progress**:
 
 1. Completd odin project css 
 2. Started reading css inspections
 
**Thoughts**

 1. CSS was difficult before, it's good to see a fairly logical explanation. 
 2. Anytime CSS doesn't work it's not broken, it's just doing what you told it and theres some issues you dont know about 


**Link(s) to work**

 1. https://github.com/TheWoodenMan/css-exercises
 
_______________________________________________________________________
 ### Day 23: April 7, 2022

**Today's Progress**:
 
 1. Anki Cards
 2. Ran through the documentation and exercises for chrome dev-tools
 3. completed the inspect html/css section of odin
 4. started the box model on odin
 
**Thoughts**

 1. Anki cards are taking a little longe to do each time, I need to factor that into my time management, they are getting more complex though too which is great. it's a good way to test and increase my knowledge.
 2. 
**Link(s) to work**

 1. 
 
_______________________________________________________________________
 ### Day 24: April 8, 2022

**Today's Progress**:
 
 1. anki cards, never skip
 2. ran through some basic command line tutorials on learnenough
 3. Watched "Learn how to learn" by Barbara Oakley which comes highly recommended by other tech students.
 
**Thoughts**

 1. focused mode vs diffuse mode for brain states learning is interesting dovetails well with pomodoro and explains why it works for me.
 2. Regular testing, use of flashcards (anki) to memorise. Use of recall rather than underlining - type out the code - no copy/pasting.
 3.
**Link(s) to work**

 1. https://www.learnenough.com/command-line-tutorial
 2. https://www.youtube.com/watch?v=vd2dtkMINIw
 
_______________________________________________________________________
 ### Day 25: April 9, 2022

**Today's Progress**:
 
 1. Started a learning tracker on github
 2. anki cards - javascript
 3. Started and finished flexboxfroggy to revise css flex
 
**Thoughts**

 1. I felt like I was starting to get a bit fragmented in my focus, I had started lots of new learning sources(there are a lot out there!) but hadn't made much solid progress. I took a little time to organise my studies a bit and have a learning tracker to complement the 100 days of code
 2. This means I'll be able to keep better track of what I'm actually working on and see my progress as I complete things and move on.
 3.  
**Link(s) to work**

 1. https://github.com/TheWoodenMan/My-Learning-Tracker/blob/master/README.md
 2. http://flexboxfroggy.com/
 
_______________________________________________________________________
 ### Day 26: April 10, 2022

**Today's Progress**:
 
 1. Anki cards
 2. Codewars Exercise
 3. 100 Devs Catch up Crew - Day 1
 4. Started Learning how to Learn on coursera
 
**Thoughts**

 1. I need to ask for help when stuck earlier. I got help with codewars from someone on discord and had typoed the function parameter which meant that even though I had code that works - I wasn't getting the output to validate vs the test. 
 2. 
**Link(s) to work**

 1. https://www.codewars.com/kata/5ab52526379d20736b00000e/javascript
 2. https://drive.google.com/file/d/1dW17kVIweEExBb3ux_ODw1F31WLVRlib/view
 3. https://www.coursera.org/learn/learning-how-to-learn/home/welcome


 
_______________________________________________________________________
 ### Day 27: April 11, 2022

**Today's Progress**:
 
 1. 20 minutes of anki cards
 2. Finished Week 1 of learning how to learn
 
**Thoughts**

 1. Learning how to learn is pretty intensive, but is clear this is very important stuff and will impact my learning approach fundamentally.
 2. That being the case - Everything else is on hold until this gets done. 
 3. I'll keep going with the javascript anki cards though to keep up the coding knowledge retention.
 
**Link(s) to work**

 1. https://www.coursera.org/learn/learning-how-to-learn/home/welcome
 
_______________________________________________________________________
 ### Day 28-31: April 12-15, 2022

**Today's Progress**:
 
 1. Learning how to learn Weeks 1-3
 2. Anki javascript cards
 3. Added six sigma project material to anki so I can learn that at the same time
 
**Thoughts**

 1. I've been working through this course in a pretty focused way each night while working during the day. Making good progress to be honest and scoring high on the assessments
 2. I haven't been able to do much coding but have kept up on the anki javascript cards to try to keep it as fresh as possible for when I go back. 
 3. I submitted the last 4 days as a block because i've been at work - but i've managed to at least update twitter every day even though I couldnt get to github.

**Link(s) to work**

 1. https://www.coursera.org/learn/learning-how-to-learn/home/welcome
 
_______________________________________________________________________
 ### Day 32: April 16, 2022

**Today's Progress**:
 
 1. Went back to Javascript complete course by jonas.io completed destructuring objects and started on the spread operator
 2. Started week 4 on "Learning how to Learn" and signed up for the honours course and final project.
 3. Anki cards being done every day, updated learning how to learn cards up to week 3 content.
 
**Thoughts**

 1. The final project is to create a learning resource about learning for others, I have a few work related ideas which might be useful.
 2. It's kind of apt that I'm scoring high on the learning course by using the very same techniques it teaches.
 3. Updating both github and twitter is kind of a pain, it would be good if I could automate twitter somehow.
 4. Alternatively updating github by mobile would be good, while working every day it's been difficult to get it done
 
**Link(s) to work**

 1. https://www.udemy.com/course/the-complete-javascript-course/learn/lecture/22648535#overview
 
_______________________________________________________________________
 ### Day 33: April 17, 2022

**Today's Progress**:
 
 1. Anki Cards
 2. Revision of string commands, Split, Substr, Splice, 
 3. Revision of JS/HTML commands, write, delete, innerHTML, `<string>` 
 4. Continue Learning to Learn
 5. Continue with complete javascript on udemy
 
**Thoughts**

 1. I had an idea that I would take notes of which anki cards I struggle with and rather than just memorising them more frequently, do small side exercises with them to really get them to stick.  Some of the ones I get mixed up are subtley similar to each other and I think that by just practicing I will be able to remember better.
**Link(s) to work**

 1. 
 
_______________________________________________________________________
 ### Day 34: April 18, 2022

**Today's Progress**:
 
 1. 30 days of javascript day 7 - functions exercise 1
 2. Anki cards
 3. short circuiting on jonas.io
 4. Refreshed my ssh key on github since it was glitching out for some reason
 
**Thoughts**

 1. I need to remember to commit my github log early so it doesn't time out, it's messing up my days order.
 2. I absolutely blasted through 30 days day 7, really fun, I obviously have a good grip on arrays, function and looping.
 3. I used the last example as an opportunity to learn more about objects and iteration using the Object keys and entries commands, really useful.
 4. 
**Link(s) to work**

 1. https://github.com/TheWoodenMan/30-Days-Of-JavaScript/blob/master/07_Day_Functions/07_day_functions.md
 2. https://attacomsian.com/blog/javascript-iterate-objects
 3. 
 
_______________________________________________________________________
 ### Day 35: April 19, 2022

**Today's Progress**:

 1. Completed "Learning how to Learn"
 2. Jonas.io - nullish coalescing operator
 3. Jonas.io - logical assignment operators 
 
**Thoughts**

 1. Learning how to learn is a fantastic course, it has given me so many effective learning techniques.
 2. I keep forgetting to save my github log and lose the previous days work.  I need to save it when I chance focus so I don't forget.
 3. 
**Link(s) to work**

 1. https://www.udemy.com/course/the-complete-javascript-course/learn/lecture/22648559#overview
 2. https://www.coursera.org/account/accomplishments/certificate/2H2D2QJPANF8
 3. 
 
_______________________________________________________________________
 ### Day 36: April 20, 2022

**Today's Progress**:
 
 1. worked trhough Odin Project html/css
 2. working through shaehowe site for html/css
 3. anki cards while on the train
 
**Thoughts**

 1. I travelled a lot today so didnt have as much time, but still fit in a solid hour and did my anki revision while travelling by android app.
**Link(s) to work**

 1. https://learn.shayhowe.com/html-css/
 2. https://www.theodinproject.com/lessons/foundations-the-box-model
 
_______________________________________________________________________ 
### Day 37: April 21, 2022

**Today's Progress**:
 
 1. Anki cards
 2. Finished 100devs Class 2 #catchupcrew
 3. shaehowe css/thml first 3 sections done
 
**Thoughts**

 1. I keep losing my update work to github crashes :(( need to commit more frequently
 2. I'm using the odin recipes page to practice CSS, I'll also be using this as an IRL receipe repo for my own records
 3. 
**Link(s) to work**

 1. https://www.youtube.com/watch?v=eCRbEILXXmE&t=4s
 2. https://learn.shayhowe.com/html-css/getting-to-know-html/
 
_______________________________________________________________________ 
### Day 38: April 22, 2022

**Today's Progress**:
 
 1. Completed the first 3 sections of the CAPM Project Management course
 2. Started and completed the code challenge on jonas.io javascript 2022
 3. 30 mins of anki cards
 
**Thoughts**

 1. Getting to be quite the pile of anki cards to work on!
 2. I'm developing my existing project management skills using CAPM training with pmi, it's helpful stuff and can be linked to coding quite easily.  I was surpised how much of the structure of PM matches actually. What they call chunk transfer in learning to learn.
 3. I chewed through the coding challenge, found rest/spread operator work easy now and have been able to destructure arrays/objects with a little referencing.  Short circuiting I didn't find intuitive but more practice with it would help that out I think.
**Link(s) to work**

 1. 
 
_______________________________________________________________________ 
### Day 39: April 23, 2022

**Today's Progress**:
 
 1. Section 4 of CAPM
 2. Anki cards
 3. Jonas.io - for of loops, enhanced obj literals, optional chaining, looping keys/values/entries, coding challenge
 4. Section 4-6 of shaehowe css site
 
**Thoughts**

 1. Today worked out more efficient overall. I need to set finish times more in advance like learning how to learn advised. 
 2. anki cards were a lot shorter today, I think thats a good sign.
 3. The recipe site is coming a long a bit, I have a rough idea of how I want it but for now it's just a sandbox for testing out css stuff.
**Link(s) to work**

 1. https://github.com/TheWoodenMan/jonasio
 2. https://www.udemy.com/course/the-complete-javascript-course/learn/lecture/22648589#notes
 3. https://www.udemy.com/course/capm-pmbok6/learn/lecture/8408314#overview
 4. https://learn.shayhowe.com/html-css/opening-the-box-model/
 5. https://thewoodenman.github.io/odin-recipes/
 
_______________________________________________________________________ 
### Day 40: April 24, 2022

**Today's Progress**:
 
 1. Anki Cards
 2. Started Functional Programming on freecodecamp
 
**Thoughts**

 1. A bit of a shorter day today but Got my practice in to keep up good habits.
**Link(s) to work**

 1. 
 
_______________________________________________________________________
### Day 41: April 25, 2022

**Today's Progress**:
 
 1. Anki Cards
 2. Section 5 of CAPM complete
 3. 71% of Functional Programming
 
**Thoughts**

 1. I got a lot of work done today and also very happy to finally learn about .map .replace and .filter properly.
 2. I also got more of a chance to work with .slice .splice and .concat
 3. Learned more about mutation and how to avoid it inside functions.
**Link(s) to work**

 1. 
 
_______________________________________________________________________ 
## Day 42: April 26, 2022

**Today's Progress**:
 
 1. Anki Cards
 2. Section 6 of CAPM
 3. 100% complete on functional programming!
 
**Thoughts**

 1. There were quite a few interesting new functions to learn in functional programming, I definitely improved my undersanding of .map .filter .reduce and .sort .every .some were totally new to me
 2. I managed to complete the currying part of the cource but still don't 100% understand it and will need to review. 
 3. CAPM is extremely straight forward with a few technical terms that will need to be learned but i'm confident with anki it will be great.

**Link(s) to work**

 1. 
 
_______________________________________________________________________ 
### Day 43: April 27, 2022

**Today's Progress**:
 
 1. Anki Cards JS/Learning how to learn/CAPM
 2. Sections 1-3 of the Agile guide
 3. Started freecodecamp Intermediate Algorithm Scripting
 
**Thoughts**

 1. Spent quite a bit more time on the project management side today.
 2. I've been trying to refactor my work and was happy with how it worked out.
 3. 
**Link(s) to work**

 1. https://github.com/TheWoodenMan/freecodecamp-exercises/blob/main/script.js
 
_______________________________________________________________________ 
### Day 44: April 28, 2022

**Today's Progress**:
 
 1. Anki
 2. Freecodecamp pushing on with algorithms
 3. Agile guide, finished part 3, started part 4 and entered 1-3 into Anki
 
**Thoughts**

 1. Sometimes with freecodecamp it gets quite difficult.
 2. I dont have full confidence in the syntax of ES6 array functions like map, replace, filter yet
 3. Recursion continues to kick my ass, I have yet to implement a single successful example.
 4. I knew agile before but the level of detail i'm going into now with CAPM and Agile guide is next level.
 5. 
**Link(s) to work**

 1. https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/intermediate-algorithm-scripting/seek-and-destroy
 2. https://github.com/TheWoodenMan/freecodecamp-exercises/blob/main/script.js
 3. 
 
_______________________________________________________________________ 
### Day 45: April 29, 2022

**Today's Progress**:
 
 1. Anki js/agile
 2. freecodecamp "wherefore art thou" algorithm problem
 3. Section 7 of CAPM nearly all of it.
 
**Thoughts**

 1. Project management CAPM has a lot of crossovers with the agile guide which has been really good for interleaving, I feel like i'm learning a lot of it
 2. I need to work on object iteration, I know for in loops and Object.keys/values/entries but struggled to iterate them to solve the problem, will try again tomorrow.
**Link(s) to work**

 1. 2. https://github.com/TheWoodenMan/freecodecamp-exercises/blob/main/script.js
 
_______________________________________________________________________
### Day 46: April 30, 2022

**Today's Progress**:
 
 1. Anki
 2. Jonas.io Overview of Sets Completed and working throuhg Maps
 3. CAPM Section 7 completd
 
**Thoughts**

 1. I much prefer doing the coding work and debugging compared to doing videos which I find a little too passive.
 2. CAPM is coming along well, an hour each day or to the next assignment, quiz or section end seems to be perfect pace for me.
**Link(s) to work**

 1. https://www.udemy.com/course/the-complete-javascript-course
 2. https://www.udemy.com/course/capm-pmbok6/
 
_______________________________________________________________________
### Day 47: May 1, 2022

**Today's Progress**:
 
 1. More detail on sets, including .add .delete .has .size - I NEED to practice these since sets keep coming up and I want to commit this to memory.
 2. Completed CAPM section 7
 3. Submitted my final project for Learning how to Learn.
 
**Thoughts**

 1. I actually put a lot of effort into learning how to learn, but submitted it at the last minute (typically).
 2. I was worried about the project but having reviewed a few other entries that were just lists - feel a bit better about it.
**Link(s) to work**

 1. [Enhancing your Karate Practice by Learning how to Learn](https://docs.google.com/document/d/1zH1XKFRXKj5DLPfCCGzqHCHzAMLH0n5xG6Kl4NQmM8U/ "Enhancing your Karate Practice by Learning how to Learn")
 
_______________________________________________________________________
### Day 48: May 2, 2022

**Today's Progress**:
 
 1. CAPM Section 8 up to the assignment
 2.  
**Thoughts**

 1. 
**Link(s) to work**

 1. 
 
_______________________________________________________________________
### Day 19: April 3, 2022

**Today's Progress**:
 
 1. https://github.com/TheWoodenMan/freecodecamp-exercises
 
**Thoughts**

 1. 
**Link(s) to work**

 1. 
 
_______________________________________________________________________
### Day 19: April 3, 2022

**Today's Progress**:
 
 1. https://github.com/TheWoodenMan/freecodecamp-exercises
 
**Thoughts**

 1. 
**Link(s) to work**

 1. 
 
_______________________________________________________________________


