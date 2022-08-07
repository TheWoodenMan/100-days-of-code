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

---

### Day 2: March 17, 2022

**Today's Progress**:

1. I completed 2 pages of the 30 days of JavaScript, primarily as revision but also because I've realised that different developers and tutors put different emphasis on coding fundamentals, or have different projects or exercises which will help me with knowledge retention. I can skip the parts I know and focus on the extra detail. the 30 days course is very comprehensive and as it's in written format, it's easy to digest quickly.
2. I completed the ES6 Section of basic Javascript - freecodecamp , learning more about the uses of const/var, arrow functions, default parameters, rest parameter, spread operator, destructuring assignment, Template literal, class syntax, getters and setters, export/import function, promise functions, resolving promises with result/catch,

**Thoughts**

There are a bunch of math/string options that haven't really been properly explored yet. it's worth knowing that in future so I can simply look them up if needed.

I'm currently alternating my learning between three main sources, **jonas.io Complete Javascript Bootcamp** which has already covered the fundamentals and is now project based which is good but it's quite carefully led, **freecodecamp** which tends to be heavily scripted, fairly technical and rigid - but very challenging. and **30 Days of Javascript** which is text based, but very well explained, the exercises at the end let you practice what you need to learn but it's fluid and free-form.

I've come to the conclusion that I learn less from freecodecamp than I do when im writing my own code examples. freecodecamp has good detail but it feels more like
"crossword puzzle" style challenges that need to be solved so you can pass to the next, I need practical application to really learn and remember. There is a lot of great content in there however and it's structured in a sensible, methodical way that builds up over time. I need to devise projects that implement the code structures I learned in freecodecamp JS ES6 - I feel like I have good awareness but not aptitude yet - I need more direct exhttps://stackoverflow.com/questions/31250174/css-flexbox-difference-between-align-items-and-align-content#:~:text=The%20align%2Ditems%20property%20applies,overridden%20for%20individual%20flex%20items.perience.

I much prefer working with visual studio code, it is intuitive and keeps me on the right path 99% of the time.

**Link(s) to work**

1. https://github.com/TheWoodenMan/30-Days-of-Javascript-Exercises
2. https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-javascript

---

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

---

### Day 4: March 19, 2022

**Today's Progress**:

1. Completed the regular expressions section of freecodecamp, this was quite difficult!
2. Finished the exercises at the end of day 3 for 30 days of JS which were quite easy - I'm getting good at functions!
3. Started debugging section of freecodecamp.

**Thoughts**

1. it's good to have worked through reg expressions in a methodical way, I understand the syntax now but maybe dont see how I could use this usefully yet.
2. the "restrict possible usernames" problem on freecodecamp is currently blowing my mind, and from the comments I can see Im not the only one. I am 99% done and determined not to look up spoilers! haha i did it!

<code>let username = "JackOfAllTrades";</code><br/>
<code>let userCheck = /^[a-z]+([a-z]+|[\d][\d]+)\d\*$/i; // Change this line</code></br>
<code>let result = userCheck.test(username);</code></br>

3. I have a little experience at debugging already from the jonas.io bootcamp and I quite enjoy it. Looking forward to seeing how freecodecamp recommend you do it.
4. practical applications of regex are more apparent now, restricting usernames and passwords for example, already in use all over the world. The ability to extract only the information you need, there are a few good excel projects i've worked on that would love the specificity of that function.
5. i'm getting curious about some of the various frameworks attached to JS, react.js and vue.js for example. I'm interested in how these can enhance the already quite fluid functionality.
6. I need to revise time operations, I still don't 100% understand the maths of it, unix time and formatting for example.

7. Repeating capture groups really kicked my ass to be honest, I found the syntax kind of unintuitive initially, but honestly it's completely logical, and whenever I looked up a solution it was always totall understandable. I will keep going on this and need to explore the exact definitions more to gain aptitude on it.

**Link(s) to work**

1. https://github.com/TheWoodenMan/30-Days-of-Javascript-Exercises
2. https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#regular-expressions

---

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
5. freecodecamp is like a dictionary-like step-by-step run through of Javascript fundamentals, but it doesn't really test applications. I need to flip back to project work to really learn some of this stuff in practice.
6. I gained a lot of confidence in working with arrays and objects todays, one of the problems in particular was very difficult but I managed to research my way out of it.
7. I seem to have a tendancy of overcomplicating challenges _slightly_ I sometimes mis-read the question and either add in features that aren't 100% needed, or just see the potential for those features and try to add them in as a bonus. I need to be better at sticking to the brief, so I'll be adding assignment objectives to my code to keep me focused on the end-goals so I don't waste any time.

**Link(s) to work**

1. https://github.com/TheWoodenMan/Bootcamp-Exercises
2. https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-data-structures

---

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

---

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

---

### Day 8: March 23, 2022

**Today's Progress**:

1. Completed the first 10 exercises of regexone
2. Completely finished the algorithm section of freecodecamp.

**Thoughts**

1. my regex comprehension is only going to get better if I find ways to either implement it more or use practice exercises to develop it.
2. Algorithms was a huge undertaking, I spent around 6 hours on this but stayed on it til it was done. Some of the challenges I solved easily in a few minutes. Other challenges I spent a few hours on trying out various techniques I already knew and reading up and trying new ones where i didn't.
3. It takes longer to do this way but I would rather stay on it instead of looking up the answer directly, both as a way to test my skills and to reinforce my ability to quickly work out how to do something.
4. I'm noticing that a lot of the "core" systems in Javascript often have shortcut commands that can abbreviate them quickly and easily, I will often reach for function building and for loops to iterate through arrays and solve problems as a default, but I need to diversify and learn more techniques.

**Link(s) to work**

---

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

---

### Day 10: March 25, 2022

**Today's Progress**:

1. Watched the explanation videos on .this functionality on Complete Javascript '22
2. Started Object Oriented Programming on freecodecamp.

**Thoughts**

1. "how javascript works" is incredibly dry, but it's also already proved very useful. I just need to break it up with exercises.
2. I totally forgot about the "persistence" challenge on codewars and need to get back to it.

**Link(s) to work**

---

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

1.https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#object-oriented-programming 2.https://github.com/TheWoodenMan/Bootcamp-Exercises 3.https://github.com/TheWoodenMan/30-Days-Of-JavaScript/blob/master/06_Day_Loops/06_day_loops.md

---

### Day 12: March 27, 2022

**Today's Progress**:

1. Made another attempt at codewars "persistance"
2. Revised for loops.

**Thoughts**

1. this is a tough one, I tried a new angle, made a little progress. I broke the problem down into steps and sucecssfully made a few functions to help.

- a function to get the length of any number</br>
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

---

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
<code> hexChar = Math.floor(Math.random() \* 255).toString(16);</code></br>
<code> output += hexChar}</code></br>
<code>return `#${output}`}</code></br>

4. I picked up an amazing little detail that has been causing bugs - if you empty a subArray for reuse - it resets all copies and instances of that array!! (edit - because of references staying the same when you use const to define an array, use let to create a new memory reference that is independant of the source array)
5. https://blog.greenroots.info/ways-to-empty-an-array-in-javascript-and-the-consequences Thanks to this blog link that explains it I managed to modify my code. The two ways I know to empty an array have different consequences, array.length = 0 mutates the original which references all instances of that array. array = []; only works if the array is defined using let and allows the array to be updated independantly from it's original reference, this solved the problem and gave me some valuable information.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/30-days-of-javascript-exercises
2.  https://github.com/TheWoodenMan/30-Days-Of-JavaScript/blob/master/06_Day_Loops/06_day_loops.md

---

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

---

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

1.  While completing the first codewars task I learned about some new techniques, firstly the Set() constructor, which creates an object that is a set of elements, can be primitives or object references. Set checks equality and so each value is not duplicated if it already exists, so it can be good for merging two arrays if the elements need to be unique. Set accepts add, clear, delete methods.
2.  when using sort() if you leave it blank it will sort in ascending order, but as if they were strings, which means numbers like 10 will be sorted like 1, 10, 2, 3 etc to counteract this, we can add parameters to sort to specify how we want it to be processed. e.g. <br>

<code>(a,b) => a-b)</code>

will sort the subject of sort with an arrow function in ascending format as if they were numbers.

3. I came up with a totally different method to solve "sum of positive" than the streamer but it still worked out, the coding style was much shorter though, almost a one liner.
4. I respond well to pressure, I will maybe try doing codewars on a timer in future since doing it before the streamer got a chance to explain seemed to really click for me.
5. I'd been stuck on alphabetical grid for the last 3 days on codewars, the problem was with what happens to the grid when you go beyond the first 26 characters of the alphabet, it needs to repeat again. Basically I solved the problem by a) taking a break from it. b) thinking really carefully about the math required to get the correct number and building a short if statement that screens for values > 26 of i

this was all it took:<br>
<code>if (i + j < 27) { </code><br>
<code> sumRef = i + j; </code><br>
<code> } else if (i + j >= 27) { </code><br>
<code> sumRef = i + j - 26 \* Math.floor((i + j) / 26);</code><br>
<code> } </code><br>

**Link(s) to work**

1. https://github.com/firstcontributions/first-contributions
2. https://www.codewars.com/kata/5899642f6e1b25935d000161/train/javascript
3. https://www.codewars.com/kata/60a94f1443f8730025d1744b/solutions/javascript
4. https://github.com/TheWoodenMan/30-days-of-javascript-exercises/blob/main/codewars.js

---

### Day 16: March 31, 2022

**Today's Progress**:

1.  Completed the "Introduction to Github" module on Microsoft Learn
2.  Attended https://www.twitch.tv/learnwithleon dev stream.
3.  installed gitbash and ubuntu wl, spent a good amount of time revising the terminal basic commands.

**Thoughts**

1.  I actually learned terminal CLI over 20 years ago with MS DOS 3.0, 3.22 6.22 Etc I've used linux before, ubunto, debian,
    raspbian and linuxmint. I also used knoppix before as a boot disk and UI so this is all pretty familiar to me.
2.  although the basics of navigating terminal is known to me, I appreciated the git terminal commands, status, init, commit, (esc : wq enter to submit) branch, checkout (branch), merge (branch)

**Link(s) to work**

1.  https://docs.microsoft.com/en-gb/learn/modules/introduction-to-github/

---

### Day 17: April 1, 2022

**Today's Progress**:

1.  Installed Anki - a card based memorisation aid for helping with information retention esp on commands/syntax.
2.  Revised git/github terminal commands
3.  Continued Complete Javascript '22 looking at Destructoring arrays.

**Thoughts**

1.  Feel like I ran out of steam a bit over the last few days, despite getting the minimum time in, I dont think I made as much progress as I would like.
2.  I have to balance my time between coding learning and work demands to be honest, it's just the way it's going to be, on days when work is heavy i'll schedule revision instead of picking up on new information so I can commit to better retention.
3.  I found a pre-build card pack for anki and it looks pretty useful to me, lets see how it goes.

**Link(s) to work**

1. https://kbroman.org/github_tutorial/pages/init.html
2.

---

### Day 18: April 2, 2022

\*\*Today's Progressni

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

---

### Day 19: April 3, 2022

**Today's Progress**:

1.  💪 20 mins Anki practice ✔️
2.  Odin Project Introduction to Git started

**Thoughts**

1.  Another fairly light day, I have a backlog of videos to watch now on git/hub so hoping to get some of that done maybe tomorrow
2.  the git explanations go into way more depth than i've seen so far, I think it's worth looking at this properly now
3.  04/04 - Man I was absolutely shattered yesterday, I'm just happy I managed to get at least some absolute basics done so I could keep up the momentum.

**Link(s) to work**

1.  https://www.theodinproject.com/paths/foundations/courses/foundations

---

### Day 20: April 4, 2022

**Today's Progress**:

1.  Continued with and completed Odin Project Intro to Github.
2.  Started and working through HTML/CSS
3.  Started and finished the recipes project to make a simple website.

**Thoughts**

1.  I feel pretty comfortable with git commands in terminal now
2.  I covered HTML/CSS in freecodecamp but honestly wasnt 100% proficient in their use, looking forward to refinding that now.
3.  I'm pushing everything I do on odin to github by terminal commands, its a little tricky, e.g. after renaming the repo on github, I had to look up how to push to that repository from my lcoal. <code> git remote set-url origin git://<newurl></code> did the job.
4.  I realised that my earlier github commits weren't really very well described so i'm going to make sure the messaging fits from now.

/\* 7 Features of a good Git Commit Message:</br>

-Separate subject from body with a blank line</br>
-Limit the subject line to 50 characters</br>
-Capitalize the subject line</br>
-Do not end the subject line with a period</br>
-Use the imperative mood in the subject line</br>
-Wrap the body at 72 characters</br>
-Use the body to explain what and why vs. how\*/

5.  I have a few recipes I can actually share and this is a really nice project that I can put something into (finally!)
6.  I found a much better way of displaying fractions in html <code>&frac12;</code>
7.  I played around a bit with some javascript on the receipe site just to see how it would fit in. Had an idea to replace any 1/2 with &frac12; automatically by making a function that replaces that exact text with the super/subscript version. it's an interesting little problem, I may give it further thought.

**Link(s) to work**

1.  https://thewoodenman.github.io/odin-recipes/

---

### Day 21: April 5, 2022

**Today's Progress**:

1.  Attended 100 Devs skills and marketing development session
2.  Fired through anki cards for the day
3.  continued Odin project section on CSS

**Thoughts**

1.  I actually spent several hours on the 100 devs twitch stream it was valuable advice but more career oriented, so although I didn't pick up any coding experience, I gained perspective in industry knowledge.
2.  I'm not great a CSS and looking forward to refining my skills here.

**Link(s) to work**

1.  https://www.theodinproject.com/lessons/foundations-css-foundations

---

### Day 22: April 6, 2022

**Today's Progress**:

1.  Completd odin project css
2.  Started reading css inspections

**Thoughts**

1.  CSS was difficult before, it's good to see a fairly logical explanation.
2.  Anytime CSS doesn't work it's not broken, it's just doing what you told it and theres some issues you dont know about

**Link(s) to work**

1.  https://github.com/TheWoodenMan/css-exercises

---

### Day 23: April 7, 2022

**Today's Progress**:

1.  Anki Cards
2.  Ran through the documentation and exercises for chrome dev-tools
3.  completed the inspect html/css section of odin
4.  started the box model on odin

**Thoughts**

1. Anki cards are taking a little longe to do each time, I need to factor that into my time management, they are getting more complex though too which is great. it's a good way to test and increase my knowledge.
2. **Link(s) to work**

3.

---

### Day 24: April 8, 2022

**Today's Progress**:

1.  anki cards, never skip
2.  ran through some basic command line tutorials on learnenough
3.  Watched "Learn how to learn" by Barbara Oakley which comes highly recommended by other tech students.

**Thoughts**

1.  focused mode vs diffuse mode for brain states learning is interesting dovetails well with pomodoro and explains why it works for me.
2.  Regular testing, use of flashcards (anki) to memorise. Use of recall rather than underlining - type out the code - no copy/pasting.
3.  **Link(s) to work**

4.  https://www.learnenough.com/command-line-tutorial
5.  https://www.youtube.com/watch?v=vd2dtkMINIw

---

### Day 25: April 9, 2022

**Today's Progress**:

1.  Started a learning tracker on github
2.  anki cards - javascript
3.  Started and finished flexboxfroggy to revise css flex

**Thoughts**

1.  I felt like I was starting to get a bit fragmented in my focus, I had started lots of new learning sources(there are a lot out there!) but hadn't made much solid progress. I took a little time to organise my studies a bit and have a learning tracker to complement the 100 days of code
2.  This means I'll be able to keep better track of what I'm actually working on and see my progress as I complete things and move on.
3.  **Link(s) to work**

4.  https://github.com/TheWoodenMan/My-Learning-Tracker/blob/master/README.md
5.  http://flexboxfroggy.com/

---

### Day 26: April 10, 2022

**Today's Progress**:

1.  Anki cards
2.  Codewars Exercise
3.  100 Devs Catch up Crew - Day 1
4.  Started Learning how to Learn on coursera

**Thoughts**

1. I need to ask for help when stuck earlier. I got help with codewars from someone on discord and had typoed the function parameter which meant that even though I had code that works - I wasn't getting the output to validate vs the test.
2. **Link(s) to work**

3. https://www.codewars.com/kata/5ab52526379d20736b00000e/javascript
4. https://drive.google.com/file/d/1dW17kVIweEExBb3ux_ODw1F31WLVRlib/view
5. https://www.coursera.org/learn/learning-how-to-learn/home/welcome

---

### Day 27: April 11, 2022

**Today's Progress**:

1.  20 minutes of anki cards
2.  Finished Week 1 of learning how to learn

**Thoughts**

1.  Learning how to learn is pretty intensive, but is clear this is very important stuff and will impact my learning approach fundamentally.
2.  That being the case - Everything else is on hold until this gets done.
3.  I'll keep going with the javascript anki cards though to keep up the coding knowledge retention.

**Link(s) to work**

1.  https://www.coursera.org/learn/learning-how-to-learn/home/welcome

---

### Day 28-31: April 12-15, 2022

**Today's Progress**:

1.  Learning how to learn Weeks 1-3
2.  Anki javascript cards
3.  Added six sigma project material to anki so I can learn that at the same time

**Thoughts**

1.  I've been working through this course in a pretty focused way each night while working during the day. Making good progress to be honest and scoring high on the assessments
2.  I haven't been able to do much coding but have kept up on the anki javascript cards to try to keep it as fresh as possible for when I go back.
3.  I submitted the last 4 days as a block because i've been at work - but i've managed to at least update twitter every day even though I couldnt get to github.

**Link(s) to work**

1.  https://www.coursera.org/learn/learning-how-to-learn/home/welcome

---

### Day 32: April 16, 2022

**Today's Progress**:

1.  Went back to Javascript complete course by jonas.io completed destructuring objects and started on the spread operator
2.  Started week 4 on "Learning how to Learn" and signed up for the honours course and final project.
3.  Anki cards being done every day, updated learning how to learn cards up to week 3 content.

**Thoughts**

1.  The final project is to create a learning resource about learning for others, I have a few work related ideas which might be useful.
2.  It's kind of apt that I'm scoring high on the learning course by using the very same techniques it teaches.
3.  Updating both github and twitter is kind of a pain, it would be good if I could automate twitter somehow.
4.  Alternatively updating github by mobile would be good, while working every day it's been difficult to get it done

**Link(s) to work**

1.  https://www.udemy.com/course/the-complete-javascript-course/learn/lecture/22648535#overview

---

### Day 33: April 17, 2022

**Today's Progress**:

1.  Anki Cards
2.  Revision of string commands, Split, Substr, Splice,
3.  Revision of JS/HTML commands, write, delete, innerHTML, `<string>`
4.  Continue Learning to Learn
5.  Continue with complete javascript on udemy

**Thoughts**

1. I had an idea that I would take notes of which anki cards I struggle with and rather than just memorising them more frequently, do small side exercises with them to really get them to stick. Some of the ones I get mixed up are subtley similar to each other and I think that by just practicing I will be able to remember better.
   **Link(s) to work**

1.

---

### Day 34: April 18, 2022

**Today's Progress**:

1.  30 days of javascript day 7 - functions exercise 1
2.  Anki cards
3.  short circuiting on jonas.io
4.  Refreshed my ssh key on github since it was glitching out for some reason

**Thoughts**

1.  I need to remember to commit my github log early so it doesn't time out, it's messing up my days order.
2.  I absolutely blasted through 30 days day 7, really fun, I obviously have a good grip on arrays, function and looping.
3.  I used the last example as an opportunity to learn more about objects and iteration using the Object keys and entries commands, really useful.
4.  **Link(s) to work**

5.  https://github.com/TheWoodenMan/30-Days-Of-JavaScript/blob/master/07_Day_Functions/07_day_functions.md
6.  https://attacomsian.com/blog/javascript-iterate-objects
7.

---

### Day 35: April 19, 2022

**Today's Progress**:

1.  Completed "Learning how to Learn"
2.  Jonas.io - nullish coalescing operator
3.  Jonas.io - logical assignment operators

**Thoughts**

1.  Learning how to learn is a fantastic course, it has given me so many effective learning techniques.
2.  I keep forgetting to save my github log and lose the previous days work. I need to save it when I chance focus so I don't forget.
3.  **Link(s) to work**

4.  https://www.udemy.com/course/the-complete-javascript-course/learn/lecture/22648559#overview
5.  https://www.coursera.org/account/accomplishments/certificate/2H2D2QJPANF8
6.

---

### Day 36: April 20, 2022

**Today's Progress**:

1.  worked trhough Odin Project html/css
2.  working through shaehowe site for html/css
3.  anki cards while on the train

**Thoughts**

1.  I travelled a lot today so didnt have as much time, but still fit in a solid hour and did my anki revision while travelling by android app.
    **Link(s) to work**

1.  https://learn.shayhowe.com/html-css/
1.  https://www.theodinproject.com/lessons/foundations-the-box-model

---

### Day 37: April 21, 2022

**Today's Progress**:

1.  Anki cards
2.  Finished 100devs Class 2 #catchupcrew
3.  shaehowe css/thml first 3 sections done

**Thoughts**

1.  I keep losing my update work to github crashes :(( need to commit more frequently
2.  I'm using the odin recipes page to practice CSS, I'll also be using this as an IRL receipe repo for my own records
3.  **Link(s) to work**

4.  https://www.youtube.com/watch?v=eCRbEILXXmE&t=4s
5.  https://learn.shayhowe.com/html-css/getting-to-know-html/

---

### Day 38: April 22, 2022

**Today's Progress**:

1.  Completed the first 3 sections of the CAPM Project Management course
2.  Started and completed the code challenge on jonas.io javascript 2022
3.  30 mins of anki cards

**Thoughts**

1.  Getting to be quite the pile of anki cards to work on!
2.  I'm developing my existing project management skills using CAPM training with pmi, it's helpful stuff and can be linked to coding quite easily. I was surpised how much of the structure of PM matches actually. What they call chunk transfer in learning to learn.
3.  I chewed through the coding challenge, found rest/spread operator work easy now and have been able to destructure arrays/objects with a little referencing. Short circuiting I didn't find intuitive but more practice with it would help that out I think.
    **Link(s) to work**

4.

---

### Day 39: April 23, 2022

**Today's Progress**:

1.  Section 4 of CAPM
2.  Anki cards
3.  Jonas.io - for of loops, enhanced obj literals, optional chaining, looping keys/values/entries, coding challenge
4.  Section 4-6 of shaehowe css site

**Thoughts**

1.  Today worked out more efficient overall. I need to set finish times more in advance like learning how to learn advised.
2.  anki cards were a lot shorter today, I think thats a good sign.
3.  The recipe site is coming a long a bit, I have a rough idea of how I want it but for now it's just a sandbox for testing out css stuff.
    **Link(s) to work**

4.  https://github.com/TheWoodenMan/jonasio
5.  https://www.udemy.com/course/the-complete-javascript-course/learn/lecture/22648589#notes
6.  https://www.udemy.com/course/capm-pmbok6/learn/lecture/8408314#overview
7.  https://learn.shayhowe.com/html-css/opening-the-box-model/
8.  https://thewoodenman.github.io/odin-recipes/

---

### Day 40: April 24, 2022

**Today's Progress**:

1.  Anki Cards
2.  Started Functional Programming on freecodecamp

**Thoughts**

1. A bit of a shorter day today but Got my practice in to keep up good habits.
   **Link(s) to work**

1.

---

### Day 41: April 25, 2022

**Today's Progress**:

1.  Anki Cards
2.  Section 5 of CAPM complete
3.  71% of Functional Programming

**Thoughts**

1.  I got a lot of work done today and also very happy to finally learn about .map .replace and .filter properly.
2.  I also got more of a chance to work with .slice .splice and .concat
3.  Learned more about mutation and how to avoid it inside functions.
    **Link(s) to work**

4.

---

## Day 42: April 26, 2022

**Today's Progress**:

1.  Anki Cards
2.  Section 6 of CAPM
3.  100% complete on functional programming!

**Thoughts**

1.  There were quite a few interesting new functions to learn in functional programming, I definitely improved my undersanding of .map .filter .reduce and .sort .every .some were totally new to me
2.  I managed to complete the currying part of the cource but still don't 100% understand it and will need to review.
3.  CAPM is extremely straight forward with a few technical terms that will need to be learned but i'm confident with anki it will be great.

**Link(s) to work**

1.

---

### Day 43: April 27, 2022

**Today's Progress**:

1.  Anki Cards JS/Learning how to learn/CAPM
2.  Sections 1-3 of the Agile guide
3.  Started freecodecamp Intermediate Algorithm Scripting

**Thoughts**

1.  Spent quite a bit more time on the project management side today.
2.  I've been trying to refactor my work and was happy with how it worked out.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/freecodecamp-exercises/blob/main/script.js

---

### Day 44: April 28, 2022

**Today's Progress**:

1.  Anki
2.  Freecodecamp pushing on with algorithms
3.  Agile guide, finished part 3, started part 4 and entered 1-3 into Anki

**Thoughts**

1.  Sometimes with freecodecamp it gets quite difficult.
2.  I dont have full confidence in the syntax of ES6 array functions like map, replace, filter yet
3.  Recursion continues to kick my ass, I have yet to implement a single successful example.
4.  I knew agile before but the level of detail i'm going into now with CAPM and Agile guide is next level.

**Link(s) to work**

1.  https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/intermediate-algorithm-scripting/seek-and-destroy
2.  https://github.com/TheWoodenMan/freecodecamp-exercises/blob/main/script.js
3.

---

### Day 45: April 29, 2022

**Today's Progress**:

1.  Anki js/agile
2.  freecodecamp "wherefore art thou" algorithm problem
3.  Section 7 of CAPM nearly all of it.

**Thoughts**

1.  Project management CAPM has a lot of crossovers with the agile guide which has been really good for interleaving, I feel like i'm learning a lot of it
2.  I need to work on object iteration, I know for in loops and Object.keys/values/entries but struggled to iterate them to solve the problem, will try again tomorrow.

**Link(s) to work**

1.  2. https://github.com/TheWoodenMan/freecodecamp-exercises/blob/main/script.js

---

### Day 46: April 30, 2022

**Today's Progress**:

1.  Anki
2.  Jonas.io Overview of Sets Completed and working throuhg Maps
3.  CAPM Section 7 completd

**Thoughts**

1.  I much prefer doing the coding work and debugging compared to doing videos which I find a little too passive.
2.  CAPM is coming along well, an hour each day or to the next assignment, quiz or section end seems to be perfect pace for me.

**Link(s) to work**

1.  https://www.udemy.com/course/the-complete-javascript-course
2.  https://www.udemy.com/course/capm-pmbok6/

---

### Day 47: May 1, 2022

**Today's Progress**:

1.  More detail on sets, including .add .delete .has .size - I NEED to practice these since sets keep coming up and I want to commit this to memory.
2.  Completed CAPM section 7
3.  Submitted my final project for Learning how to Learn.

**Thoughts**

1.  I actually put a lot of effort into learning how to learn, but submitted it at the last minute (typically).
2.  I was worried about the project but having reviewed a few other entries that were just lists - feel a bit better about it.

**Link(s) to work**

1.  [Enhancing your Karate Practice by Learning how to Learn](https://docs.google.com/document/d/1zH1XKFRXKj5DLPfCCGzqHCHzAMLH0n5xG6Kl4NQmM8U/ "Enhancing your Karate Practice by Learning how to Learn")

---

### Day 48: May 2, 2022

**Today's Progress**:

1.  CAPM Section 8 up to the assignment
2.  Freecodecamp - Made a little progress on "Wherefore art thou?"
3.  **Thoughts**

4.  Ultimately had to look up the solution for wherefore art thou, I was getting nowhere and felt like my learning was roadblocked.
5.  So to try to get the most out of this example this is what I missed in pseudocode:
6.  <code>Object.keys(source);</code> - this gave the "key" for the listed object.
7.  <code>collection.filter((obj) =></code> - this iterated over the array of objects applying a logical check to each element (obj)
8.  <code>sourceKeys.every((key) =></code> - this is the main component of the check, only returning "true" if every element meets the logic.
9.  <code>obj.hasOwnProperty(key) && obj[key] === source[key]</code> - the logical check, does the object contain the element (the keys from the source) AND do the values match?
    **Link(s) to work**

10. https://bobbyhadz.com/blog/javascript-split-by-capital-letter#:~:text=Split%20a%20String%20on%20Capital%20Letters%20in%20JavaScript%20%23,an%20array%20of%20the%20substrings.
11. https://github.com/TheWoodenMan/freecodecamp-exercises

---

### Day 49: May 3, 2022

**Today's Progress**:

1.  Anki
2.  Pushed through Freecodecamp
3.  Started https://learnlayout.com/ to 8/19
4.  CAPM S8 Assignment done.

**Thoughts**

1.  I wrote up my notes to Day 49 then lost them to a crash :/
2.  Need to save as soon as written and update more.
    **Link(s) to work**

3.

---

### Day 50: May 4, 2022

**Today's Progress**:

1.  Anki
2.  Finished Learn Layout
3.  CAPM - finished Section 8 :)
4.

**Thoughts**

1.  I've been busy with work so really only had time to keep the learning going with review.
2.  I'm doing around half a CAPM section per day at the minute which means I will clear the course in around another 2 weeks which is ideal.
3.  I need to get back to technical learning again, too much PM and the CSS stuff has been all theoretical, need a weekend project!
    **Link(s) to work**

4.  https://www.udemy.com/course/capm-pmbok6/learn/lecture/8408908#overview
5.

---

### Day 51: May 5, 2022

**Today's Progress**:

1.  Anki: JS/Agile
2.  Back to shaehowe, picking up from lesson 7
3.  CAPM - finished Section 8 :)
4.  CSS - Practiced applying to odin-receipes site.

**Thoughts**

1.  I've been busy with work so really only had time to keep the learning going with review.
2.  I'm doing around half a CAPM section per day at the minute which means I will clear the course in around another 2 weeks which is ideal.
3.  I like working on the receipe site and really want to get on to look at things like bootstrap and tailwind because I am currenlty kinda bad at CSS!
    **Link(s) to work**

4.  https://www.udemy.com/course/capm-pmbok6/learn/lecture/8408908#overview
5.  https://learn.shayhowe.com/html-css/setting-backgrounds-and-gradients/

---

### Day 52: May 6, 2022

**Today's Progress**:

1.  Anki: JS/CAPM, agile
2.  CAPM - Started Section 9 and halfway through.

**Thoughts**

1.  A lighter day today generally.
2.  Had a problem with anki sync, but think it's because windows didn't autosync it.
3.  Started refining the CAPM anki deck
    **Link(s) to work**

4.  https://www.udemy.com/course/capm-pmbok6/learn/lecture/8408908#overview
5.

---

### Day 53: May 7, 2022

**Today's Progress**:

1.  Anki: JS/CAPM/Learning how to learn
2.  CAPM Finished Section 9 and the quiz.
3.  Reconfigured my ubuntu audio drivers.
4.  Shaehoew - finished reading the 12 sections
5.  100Devs - class 3

**Thoughts**

1.  Ate my frogs and did CAPM section 9 first thing
2.  Need to make sure I go back over power types and leadership vs management since I only got 13/30 on the end of section test. :/
3.  I think looking stuff up on stack exchange for javascrip helped me out a lot with fixing the ubuntu crackles that were driving me crazy!
4.  I really like the positivity and tone of the 100devs videos, it's always helpful and motivational.
    **Link(s) to work**

5.  https://www.udemy.com/course/capm-pmbok6/learn/lecture/8408908#overview
6.  https://askubuntu.com/questions/1398966/crackling-sound-about-every-second-on-headphones-steelseries-when-audio-starts
7.  https://www.youtube.com/watch?v=rdWM6kUImjE

---

### Day 54: May 8, 2022

**Today's Progress**:

2.  CAPM Started Section 10
3.  Reinstalled my ubuntu keyboard drivers to reduce latency
4.  100Devs - class 4
5.  CSS Homework for 100devs
6.  Anki html/css added a few cards

**Thoughts**

1.  I need to start reading the pmbok alongside the CAPM course because it covers things the videos don't mention.
2.  I feel a lot better about CSS having tested myself on the 100devs content.

**Link(s) to work**

1.  https://www.youtube.com/watch?v=Q1Obtn29twk
2.  https://github.com/TheWoodenMan/100Devs

---

### Day 55: May 9, 2022

**Today's Progress**:

1.  Typing Test
2.  Keybr
3.  pushing FCC Int Algorithms

**Thoughts**

1.  I managed 77 wpm top speed but my mistakes are too high when I type too fast.
2.  my wpm drops to 55 when you take into account the errors. (typing test)
3.  Need to work on accuracy and get more practice
4.  Im pushing on FCC and it's great :) deepened my understanding of .forEach() , .join() , .split() and .replace()

**Link(s) to work**

1.  https://www.keybr.com/
2.  https://www.typingtest.com/
3.  https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/intermediate-algorithm-scripting/dna-pairing

---

### Day 56: May 10, 2022

**Today's Progress**:

1.  Keybr ✅
2.  Anki ✅
3.  100devs class 5 ✅
4.  100devs class 5 homework ✅

**Thoughts**

1.  I managed 90 wpm top speed and got my accuracy up to 95%!
2.  Average was around 70
3.  Class 5 was CSS layouts using float and honestly that all makes so much sense now!!
4.  Im going to go back to codewars for a bit from tomorrow to see if I can push up

**Link(s) to work**

1.  https://www.keybr.com/
2.  https://github.com/TheWoodenMan/100Devs

---

### Day 57: May 11, 2022

**Today's Progress**:

1.  Keybr ✅
2.  Typing Test✅
3.  Anki ✅
4.  ShaeHowe Responsive Web Design ✅
5.  100devs class 6 ✅
6.

**Thoughts**

1.  I'm better at Keybr rather than typing test because there are no captital letter or punctuation.
2.  also, typing test ends the test when you click "backspace" and I DEFINITELY self correct a lot more than I realised before.
3.  Average speed on typing test was 77, 85% accuracy and adjusted to 65
4.  Responsive web design has 3 main areas - flexible design, media queries and Flexible media.

**Link(s) to work**

1.  https://www.keybr.com/
2.  https://github.com/TheWoodenMan/100Devs
3.  https://learn.shayhowe.com/advanced-html-css/responsive-web-design/
4.  https://alistapart.com/article/creating-intrinsic-ratios-for-video/ - How to make a video scale to size.

---

### Day 58: May 12, 2022

**Today's Progress**:

1.  Keybr ✅
2.  Anki ✅
3.  Reading ShaeHowe CSS Advanced-Performance Organisation.✅
4.  I found a great overview of css-flexbox on stackoverflow.
    **Thoughts**

5.  I'm going to ease off the keybr for a bit, happy to sit in the 60-70 wpm bracket.
6.  more than anything, I need to improve my accuracy because i'm fast but make a lot of mistakes.
7.  Anki Cards - Reviewed HTML/CSS,
8.  It's hard to keep focused on the reading stuff but I'm pushing through.
9.  Read all of CSS Advanced and Anki-carded it, took around an hour and a half.

**Link(s) to work**

1.  https://www.keybr.com/
2.  https://learn.shayhowe.com/advanced-html-css/performance-organization/
3.  https://stackoverflow.com/questions/31250174/css-flexbox-difference-between-align-items-and-align-content#:~:text=The%20align%2Ditems%20property%20applies,overridden%20for%20individual%20flex%20items.

---

### Day 59: May 13, 2022

**Today's Progress**:

1.  Flexbox Froggy
2.  Anki

**Thoughts**

1.  I did flexbox frog before (and grid garden), but this time i'm also adding the info to anki cards for review.

**Link(s) to work**

1.  http://flexboxfroggy.com/

---

### Day 60: May 14, 2022

**Today's Progress**:

1.  Anki
2.  Css-tricks

**Thoughts**

1.  I just realised i've hit css-tricks a few times already in my studies because it's a popular google search for flexbox.
2.  This time running through i'm going to add it all to anki.
3.  I've never really been able to get flexbox working til now..! Wegnt back to my recipe site and flexing with the best of them
4.  Finished css-tricks first pass, but theres still a lot of detail in there. Need to apply even more of this to really chunk it.
5.

**Link(s) to work**

1.  https://www.smashingmagazine.com/2011/12/an-introduction-to-object-oriented-css-oocss/
2.  https://css-tricks.com/snippets/css/a-guide-to-flexbox/
3.  https://github.com/TheWoodenMan/odin-recipes

---

### Day 61: May 15, 2022

**Today's Progress**:

1.  Anki: Agile/CSS
2.  100 Devs: Class 07 2/3 complete

**Thoughts**

1.  I picked good sleep hygiene over finishing the 100devs class which is great because usually it's the opposite.
2.  100 Devs class 07 is all about networking. I have a good amount of connections on twitter already so I'll try some outreach.
3.

**Link(s) to work**

1.

**Plan for tomorrow**

1.  Finish class 07 minimum

---

### Day 62: May 16, 2022

**Today's Progress**:

1.  Anki: CAPM/HTML/CSS 44 cards
2.  100 Devs: class 07 - Finished

**Thoughts**

1.  Self care - When the yawning starts - I need to stop :)

**Link(s) to work**

1.  https://www.youtube.com/watch?v=k8r3B0JGMt4

**Plan for tomorrow**

1. just anki, I have a full schedule.

---

### Day 63: May 17, 2022

**Today's Progress**:

1.  Anki cards: CAPM
2.  Pushed through 1.5 hours of CAPM

**Thoughts**

1.  Currently working through CAPM integrating project management section - this one touches every process group in the project so it's a huge section.
2.  Pushed on hard and completed assignment 9 which was about change control management.

**Link(s) to work**

1.  https://www.udemy.com/course/capm-pmbok6/learn/lecture/12789517#notes

**Plan for tomorrow**

1.  Another busy day but I will try and squeeze more CAPM in before work starts
2.  I want to try the coursework for class 08 100devs tomorrow.

---

### Day 64: May 18, 2022

**Today's Progress**:

1.  Anki: CSS/HTML 66 cards
2.  CAPM: Finished Section 10 and quiz

**Thoughts**

1.  A lighter day since I had a full day of work.

**Link(s) to work**

1.  https://www.udemy.com/course/capm-pmbok6/learn/lecture/8409126#overview

**Plan for tomorrow**

1.  Anki work on PMBOK guide
2.  Try and start class 08 100devs

---

### Day 65: May 19, 2022

**Today's Progress**:

1.  Pushed through part 4 of the PMBOK guide which is on project integration management.
2.  Attended Class 35 of 100Devs

**Thoughts**

1.  The 100Devs class is way beyond me in theory but I was able to follow along anyway.
2.  I learned about the nature of webAPIs and the DOM as well as an explanation of promises.
3.  Async/await was also covered, but think it's a little beyond me for now.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

---

### Day 66: May 20, 2022

**Today's Progress**:

1.  Anki Cards for HTML/CSS

**Thoughts**

1.  That was all I managed, mainly because I had a full day of calls and karate instruction.

**Link(s) to work**

1.

**Plan for tomorrow**

1.  Class 08 100Devs

---

### Day 67: May 21, 2022

**Today's Progress**:

1.  Anki
2.  Class 08

**Thoughts**

1.  Got a lot more done today, wrote a lot of CSS and coded along,
2.  my typing accuracy really improved after using keybr, going to try and fit some typing in tomorrow again.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/100Devshttps://github.com/TheWoodenMan/100Devs

**Plan for tomorrow**

1. Watch independence day
2. keybr.com
3. 15 minutes of pain

---

### Day 68: May 22, 2022

**Today's Progress**:

1.  Completed Class 08 homework of 100 Devs
2.  Watched Independence Day

**Thoughts**

1.  Next 5 days were actually very tough because I was travelling constantly throughout.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/100Devs

**Plan for tomorrow**

1.  Do anki for 5 days and somehow keep it going

---

### Day 69-73 : May 23-May 27 , 2022

**Today's Progress**:

1.  Did anki every day..
2.  Managed to push CAPM on day 71 section 11
3.

**Thoughts**

1.  I have to be realistic that when travelling around i'm not going to get much done since I work early til late every day and am usually with other people.
2.  I don't get any downtime, except on public transport and a few mins before sleep - thats the time to push anki and thats how I fit it all in.

**Link(s) to work**

1.  https://ankiweb.net/decks/

**Plan for tomorrow**

1.  I plan to finish the homework for class 08 over the next few days
2.  I also plan to start class 09
3.  I'm pushing hard on CAPM generally and want to get it finished, but not too quickly - I need to retain the knowledge.

---

### Day 74: May 28, 2022

**Today's Progress**:

1.  Pushed CAPM section 11
2.  Worked on typing on keybr.com
3.  Created a WBS for CAPM exercises
4.

**Thoughts**

1.  I'm going to keep going with the typing practice, being able to see my mistakes in real time is really helping me to see where i'm going wrong.
2.  I've worked up to 80 wpm with 97% accuracy :)
3.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

---

### Day 75: May 29, 2022

**Today's Progress**:

1.  Installation and Update of foundryvtt
2.  practice with ssh, filezilla and ubuntu updates
3.  CSS/Media Queries for class 08 assignment 100Devs

**Thoughts**

1.  Media queries starting to make sense, site looks quite good too!
2.  I was quite happy that I was able to confidently debug and fix the foundry issues.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/100Devs

**Plan for tomorrow**

1. Lots of Project work planned as well as a PMI webinar
2. Try and finish class 08 homework

---

### Day 76: May 30, 2022

**Today's Progress**:

1.  pushed CAPM section 11
2.  Finished Class 08 100Devs homework
3.  Finished class 09 100Devs
4.  Attended PMI UK/PT EVM Webinar (Training/Networking)
5.  keybr typing

**Thoughts**

1.  What a great day of self-awareness/training!!
2.  I achieved so much, to be honest what was different was in the scheduling (and in not travelling)
3.  The class 08 layouts had been beating me up a little but I realised what I was doing wrong, I was really happy with the fake bbc site I had to make, proud of it - it looked goood!
4.  I probably spent a bit too much time on class 08 homework but I really didn't want to go forward without working out what had been going wrong - I had to manually re-set the height of a div/section because as the screen size reduced it caused that element to wrap - which caused it to overlap another element. Forcing that element to be a bigger size that fit all the content solved the problem
5.  I networked a LOT at the PMI event and made a few great connections with some interesting people :)
6.  I felt a little awkward talking about myself beecause I actually had no idea how to explain who I was and what I did to project managers. (since my primary is Operations)

**Link(s) to work**

1.  ![image](https://user-images.githubusercontent.com/85075266/171071546-e89a7fce-6caf-4e27-ab3c-96a3f0c38a24.png)
2.  https://github.com/TheWoodenMan/100Devs

**Plan for tomorrow**

1.  Guess I'm pushing class 10 :)
2.  keep up keyb practice
3.  Push on with CAPM section 11 - 1 hour in the morning.

---

### Day 77: May 14, 2022

**Today's Progress**:

1. Class 10 100Devs
2.

**Thoughts**

1.  Class 10 Finished, I have a bunch of layouts to push on with!
2.  I'm going to park the CAPM training until I have at least half the layouts done

**Link(s) to work**

1.  https://www.youtube.com/watch?v=WftjV2L7oyk

**Plan for tomorrow**

1. Push through with html/css layouts as much as I can do.

---

### Day 78: June 1, 2022

**Today's Progress**:

1.  Finished layout 4 - Level Ground
2.  Started Layout 5 - source wireframe

**Thoughts**

1.  I put a lot of work into layout 4, maybe too much? I need to work on trading off speed vs quality
2.  I started layout 5 which was much faster, but when I went back to look at layout 4, I noticed a bunch of things that annoyed me.
3.  I fixed most of the things, main thing I missed is that text was overflowing when the device was in landscape - I need to resize sites in a variety of ways, not just left to right - to make sure they're looking great for every user.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/100Devs
2.  ![carrylogs](https://user-images.githubusercontent.com/85075266/171522123-689f3f92-0d92-43d8-aa8c-2b2f2d976d71.gif)

**Plan for tomorrow**

1.  I need to push on and finish layout 5 and maybe start layout 6, if I have time I'll push section 11 of CAPM

---

### Day 79: June 2, 2022

**Today's Progress**:

1.  CAPM Section 12 - Schedule Management 1/2 Way through
2.  Finished layout 4
3.  Started layout 5

**Thoughts**

1.  I enjoy doing the layouts and it's getting easier!
2.  I'm probably spending too much time on these and could go ahead with a rougher version

**Link(s) to work**

1.  https://github.com/TheWoodenMan/100Devs
2.  ![debug-css](https://user-images.githubusercontent.com/85075266/171994536-fda1cae1-74f3-45d2-bffe-3ba41168db28.gif)

**Plan for tomorrow**

1. Finish layout 5
2. Start layout 6
3. Think about class 11

---

### Day 80: June 3, 2022

**Today's Progress**:

1.  Finished layout 5
2.  Started Layout 6
3.  Signed up to stack overflow and answered a few questions :)

**Thoughts**

1.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/100Devs
2.  ![sourcegif](https://user-images.githubusercontent.com/85075266/171994585-c6f262f7-fe44-478d-910c-570756152385.gif)

**Plan for tomorrow**

1. Continue layout 6
2. must do class 11
3.

---

### Day 81: June 4, 2022

**Today's Progress**:

1.  90% done on the html/css for layout 6
2.  Watched Class 11 - Flexbox

**Thoughts**

1.  The cuisine layout looks pretty good, definitely happy to be working with a more visual/photographic design.
2.  It was a long site with a lot of complications but I learned a lot from putting it together.
3.  I think media queries are going to be kind of tricky to handle on this one because of all the media.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/100Devs
2.  ![image](https://user-images.githubusercontent.com/85075266/172025911-04a9bdc9-e20f-4fb1-a9a9-01476f25246f.png)
3.  https://www.youtube.com/watch?v=qEj0pXGVwjY

**Plan for tomorrow**

1.  Finish restaurant layout
2.  start salon layout - try to do it all in flexbox
3.  start javascript crash course

---

### Day 82: June 5, 2022

**Today's Progress**:

1.  Flexbox Zombies Chapters 1-3
2.  Traversy Media JS Crash Course for Beginners
3.  Continuing with layout 6 - media queries

**Thoughts**

1.  Pushing on with javascript, a lot of this is revision and I hope to push on quickly.
2.  I already did quite a bit of basic javascript on freecodecamp, jonas.io and codewars.
3.  I'm going to do the last layout in flexbox just to get the practice. I actually feel more comfortable with floats than I do with flexbox!
4.  Caught up with anki a bit, there were some JS cards as well as HTML
5.  media queries and photos are quite a bit more difficult to handle together, need to explore this more to find better solutions.

**Link(s) to work**

1.  https://mastery.games/flexboxzombies/ Chapters 1-3
2.  https://www.youtube.com/watch?v=hdI2bqOjy3c

**Plan for tomorrow**

1. I'm going to be travelling all day tomorrow but will still have some time in hotel tomorrow night to push a bit of work out.
2. will do the hair salon layout with flexbox tomorrow if possible

---

### Day 83: June 6, 2022

**Today's Progress**:

1.  Big Anki Day with over 60 cards coming up
2.  Flexbox Zombies ch 4 - align-self
3.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1. https://www.youtube.com/watch?v=hdI2bqOjy3c

---

### Day 84: June 7, 2022

**Today's Progress**:

1.  Layout 6 More media queries
2.  Flexbox zombies - Ch 5

**Thoughts**

1.  Hard to code on the side while working constantly at the minute
2.  Happy to squeeze a little coding in at night :)
3.  Flexbox zombies got hard real quick haha. I'm going to push a class per day to let the info settle in.
4.  Media queries for Layout 6 is quite tough, I'm probably going to push ahead with layout 7 in the meantime and double back when I get inspiration.

**Link(s) to work**

1. https://mastery.games/flexboxzombies/chapter/5/level/23
2. https://twm-7layouts-layout-6.glitch.me
3. https://github.com/TheWoodenMan/100Devs

**Plan for tomorrow**

1.  Probably do anki only, I have a full day of meetings scheduled.

---

### Day 85: June 8, 2022

**Today's Progress**:

1.  Only Anki

**Thoughts**

1.  Difficult to fit in any real coding while working full time on deployment, but I can at least do anki on the breaks. :)

**Link(s) to work**

**Plan for tomorrow**

1. Survive travelling from Portugal to UK :')

---

### Day 86: June 9, 2022

**Today's Progress**:

1.  Finished layout 6 media queries
2.  Anki for Javascript/css/html

**Thoughts**

1.  layout 6 is looking 90% done now, Got to resist being a perfectionist now and move on to the next one.

**Link(s) to work**

1. https://twm-7layouts-layout-6.glitch.me

**Plan for tomorrow**

1. start layout 7
2. more flexbox zombies if time

---

### Day 87: June 10, 2022

**Today's Progress**:

1.  Started layout 7
2.  Anki catchup

**Thoughts**

1.  I'm using flexbox more now so getting good practice in, so far it's 100% the best way to make a working nav
2.  layout 7 is probably the most challenging yet, lots of images to use and a few tricky css hacks needed like rotate text and styling circles for buttons.

**Link(s) to work**

1. https://github.com/TheWoodenMan/100Devs
2. ![image](https://user-images.githubusercontent.com/85075266/173164354-4c220750-8788-4998-8494-d01d98aae944.png)

**Plan for tomorrow**

1. Watch Class 12 \*\*\*
2. Continue Layout 7
3. Flexbox Zombies Ch 6.
4. Anki

---

### Day 88: June 11, 2022

**Today's Progress**:

1.  Flexbox Zombies Ch 6 done.
2.  Class 12 100Devs - Javascript
3.  Worked on Layout 7 more
4.  Anki - 19 HTML/CSS 11 JS

**Thoughts**

1.  I'm trying to space out the flexbox zombies stuff a bit, one of the things I did wrong with freecodecamp was to binge through the content, clear the tests and then not really have a solid understanding because I didn't remember. Doing one per day should be different.
2.  I already have quite a bit of anki dedicated to flexbox, next step I think is just using it for real-deal examples.
3.  Class 12 was good, largely revision with the exception of focus on the DOM stuff, which I have seen before but not really practiced as much as I need to.
4.  Looking forward to javascript homework :)

**Link(s) to work**

1. https://www.youtube.com/watch?v=_A20kVsaqIk
2.

**Plan for tomorrow**

1. Write out the background picker and add a few event listeners.
2. Update the weekday checker update the dom regardless of the case sensitivity of what got typed
3.

---

### Day 89: June 12, 2022

**Today's Progress**:

1.  Read js variables + tasks
2.  Read js functions + tasks
3.  type out the class 12 JS again/delete and again

**Thoughts**

1.  Basic javascript is essentially revision and I am learning a lot through interleaving, but also the approach is different with a bigger focus on applications, so different things are focused on.

**Link(s) to work**

1. https://javascript.info/variables
2. https://github.com/TheWoodenMan/100Devs

**Plan for tomorrow**

1. class 13
2. flexbox zombies ch.7

---

### Day 90: June 13, 2022

**Today's Progress**:

1.  Flexbox Zombies - Ch.7 - Flex-basis
2.  Worked on starfinder character creation aid for races/classes/themes

**Thoughts**

1.  I can see straight away this side-project could become a monster if I don't contain the scope of it.
2.  It's super fun to be able to visualise the utility possible - then go implement it immediately :)
3.  I've been looking into fair use and copywrite generally because a lot of the assets are either from paizo rulebooks or googled assets online. It's for personal use/learning and I don't intend to publish so I should be ok.

**Link(s) to work**

1. https://mastery.games/flexboxzombies/
2. https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON

**Plan for tomorrow**

1.

---

### Day 91: June 14, 2022

**Today's Progress**:

1.  Continued with the starfinder character creation project

**Thoughts**

1.  It's going well, a few niggles but debugging picked it up as well as an accidental click
2.  The problem I had was that I overlooked the slight naming differences between some of the classes android/android(s) for example. that and I needed to be more discrete in the differences between thumbnail refs and info-section refs.

**Link(s) to work**

![Peek 2022-06-15 03-21](https://user-images.githubusercontent.com/85075266/173724242-0b31c9a3-b90e-4982-8d77-f267a64daa70.gif)

**Plan for tomorrow**

1. javascript.info reading/tasks
2. continue content work
3. flexbox zombies ch 8 if time

---

### Day 92: June 15, 2022

**Today's Progress**:

1.  Worked to bring sf-character-choice-tool to a first draft

**Thoughts**

1.  I've learned so much with this project, handling iframes, managing overflow, git ssh and the effect sudo has on it, how to correct mass-duplicated errors in html and css usind ctrl+D and basic recurring patterns. More flexbox, practice with queryselector/all practice with eventlisteners. my first homemade UI/UX, content, copywrite, prioritising stucture first over content/art. community/fair use. User feedback etc etc.
2.  It's a huge list and when people say "you will learn more if you do a project" I can now see what they mean.
3.  I brought the project to a basic, workable level, I still have a few things to do but I need to go back to javascript.info and push for class 14 now.
4.  To-Do for character choice tool: media queries for mobile with collapsable menu for selectors, content/art for alien archives I/II, classes/themes, tidy up the iframe definitively.

**Link(s) to work**

1. https://thewoodenman.github.io/sf-character-choice-tool/
2. https://twitter.com/Andynwood79/status/1537250341124726784

**Plan for tomorrow**

1. javascript.info

---

### Day 93: June 16, 2022

**Today's Progress**:

1. Caught up on study
2. Javascript.info - function expressions
3. javascript.info - arrow functions
4. thejsway - loops

**Thoughts**

1.  This is largely revision but it's valuable.
2.  I had to put the project work to one side, it's too tempting to start work on it!

**Link(s) to work**

1. https://javascript.info/function-expressions
2. https://javascript.info/arrow-functions-basics
3. https://github.com/TheWoodenMan/the-js-way-exercises

**Plan for tomorrow**

1. do the exercises for the js way.
2. try to push for class 14

---

### Day 94: June 17, 2022

**Today's Progress**:

1. Lots of exercises today
2. The JS way all exercisees from yesterdays
3. fizzbuzz and odd/evens - use of modulus.
4. Over 100 anki cards

**Thoughts**

1.  I had let anki build up over the last few days so had a traffic jam to do, I think i'd better start doing them in the morning rather than the evening.
2.  I repeated a lot of the exercises a few times, deleting and retyping. Just to get the spaced repetition in.

**Link(s) to work**

1. https://github.com/TheWoodenMan/the-js-way-exercises
2. https://github.com/TheWoodenMan/100Devs

**Plan for tomorrow**

---

### Day 95: June 18, 2022

**Today's Progress**:

1.  100 Devs Class 14
2.  exercises for Class 14
3.  Delete and retype

**Thoughts**

1.  deleting and retyping totally blind is honestly amazing, I picked up on so many obvious mistakes I was making. Not copy/pasting as well is a key point.
2.  Im more confident now on querySelector and ClassList DOM operations
3.  The mistakes I was making are easy to solve, missing ""s or typos on variables. I started a "debug checklist" to just remind of of the obvious things to check before pulling my hair out.

**Link(s) to work**

1. https://github.com/TheWoodenMan/100Devs

**Plan for tomorrow**

1. Push class 15
2. Delete and retype again
3. More anki
4. Revisit old layouts and see if I can make them tidyer or interactive.

### Day 96: June 19, 2022

**Today's Progress**:

1. FreeCodeCamp - Algorithms - missing letters
2. Worked on my portfolio!

**Thoughts**

1. FCC Algorithms are rightly, difficult. I'm still stuck on this one but at least I made a good attempt.
2. Worked on my portfolio

**Link(s) to work**

1. https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/intermediate-algorithm-scripting/missing-letters

**Plan for tomorrow**

1. Javascript.info tasks - redo them again and submit
2. Pick one business area from my local - apply a template to a fictional business and upload it.
3. Anki as usual.
4. Outreach to a few people who might want a website built for them.

### Day 97: June 20, 2022

**Today's Progress**:

1.  Updated and submitted the js.info exercises
2.  I went through a directory of local businesses and categorised them.
3.  Made contact with a client interested in web development :)
4.  Edited and activated a responsive website for a driving school with content and copy.
5.  Refreshed a previous layout I had for a Gym with new content.
6.  Uploaded to netlify and hooked up github repos for each one.
7.  Updated my portfolio with the new layouts.
8.  Flexbox Zombies - Ch 8.

**Thoughts**

1.  Overall a very productive day, I did a lot of heavy lifting on my portfolio.
2.  I also managed to attend the 100devs technical intervieweing stream.
3.  The number one local business in my area - Driving Schools, then - Web Developers! (ha!) after that it's Cleaners, Computer Repairs, Electricians, Security, Builders, Roofers and other tradesmen. that being the case, I decided to write up a driving school website for my portfolio and next will add one for mobile cleaners and finally generic tradesmen site.

**Link(s) to work**

**Plan for tomorrow**

1.  Create mock ups for a mobile cleaning company and tradesman company (electricians)
2.  Update my portfolio with these and add them in.
3.  Look at deleting and re-doing the javascript exercises again
4.  Push for Class 16

### Day 98: June 21, 2022

**Today's Progress**:

1.  Started AND Finished a responsive site for a mobile cleaning company
2.  Completed and uploaded to github javascript.info tasks
3.  Updated my Portfolio.
4.  Submitted SSL certs for my site and set up domain forwarding.
5.  Got minecraft working on the raspberry pi :)))
6.  Read documentation on review carousels and payment gateways.
7.  Updated profile on freelancer.com and researched available contracts.
8.  Delete and repeat for 2 javascript exercises.

**Thoughts**

1.  I'm pretty sure i'm not the only one who hates fiddling around with SSL certs
2.  I'm getting pretty quick at putting sites together
3.  I wasn't as smooth at the javascript as I liked, mixing up queryselectors and elementbyID, need to do more practice still.

**Link(s) to work**

**Plan for tomorrow**

1.  Push on to Class 16
2.  Put the shout out on twitter to hook up for Coffee Chats! (be brave!)
3.  Complete a site for a bar with payment gateway and event booking form.
4.  Update one of the other sites with a review carousel
5.  If I can't 100% do the above, I need to at least get the documentation together.

### Day 99: June 22, 2022

**Today's Progress**:

1.  Researched SEO
2.  Built a new site for a bar in Leeds
3.  100Devs - Class 16
4.  Set up calendly for coffee chats

**Thoughts**

1. I like building websites! the bar website was great to build if a little fiddly, I struggled at first with the custom CSS shapes, but use of margin-top: -6em; sorted out the issues with image borders.
2. Many businesses on freelancer want payment gateways, and through my own research I can see that many commercial websites have review carousels and google maps api integration - Its a little out of my tech range atm but I need these skills.

**Link(s) to work**

1. https://ahrefs.com/blog/seo-basics/

**Plan for tomorrow**

1. opening hours, google maps and event booking form for bar website. (paypal deposit?)
2. coffee chats..
3. Bring it on again homework.

### Day 100: June 24, 2022

**Today's Progress**:

1.  FCC Pushed through 5 algorithms
2.  Reading - the js way sections 1 - 5 (revision)
3.  Typed out angry parent again, but with switch function instead
4.  Learned about chmod in linux

**Thoughts**

1.  I've been stuck on the missing character algo on FCC for weeks now, the problem I had was that I am stubborn and don't want to give up - honestly this is not helpful and I need to get over it.
2.  I was able to research the problem and found that it needed some JS commands I had never heard of yet - so this would have been literally impossible to bust through - imagine If i'd looked it up sooner!
3.  CharAt and CharCodeat functions convert strings to ASCII 128 character code and back again, this means you can process letters as numbers in series - which is ultimately what was needed to solve the problem.
4.  Chmod caused a whole heap of trouble during configuration of my minecraft server. it can be configured by number 0 to 7 or letter R recursive, x execute, r read, w write and typically uses a - or + to add or remove the perms.

**Link(s) to work**

**Plan for tomorrow**

1.  Finish reading the js way 1-5
2.  Start reading eloquent javascript
3.  Anki

### Day 101: June 25, 2022

**Today's Progress**:

1.  Started with a huge anki dump, over 100 cards
2.  Read a little about kubernetes, choco, npm and yarn.
3.  Finished reading the js way 1-5 which was mainly revision.
4.  Finished subprimes on FCC

**Thoughts**

1. I need to start doing anki more daily so that it doesn't build up, I set an alarm at the end of the day but I forget - I'll change the time to midnight and see if that helps.
2. I really like functional programming, it's like playing with lego technics. Need to remember to send all arguments into the formula, always end in a return and don't change anything

**Link(s) to work**

**Plan for tomorrow**

1. Continue reading eloquent javascript
2. Take a crack at the next FCC problem
3. Watch traversy media course on git/github

### Day 102: June 26, 2022

**Today's Progress**:

1. Read chapter 1 of eloquent javascript
2. FCC attempting smallest commons

**Thoughts**

1.  I thought I'd solved smallest commons, giving the first number that is divisible by both elements, but I didn't read the question properly - it wants the number thats divisible by all elements between the two numbers (including the two numbers)
2.  I need to read the question better, in fact it would have been caught by writing out the pseudocode from the brief - I need to remember to do that each time.

**Link(s) to work**

1.  https://eloquentjavascript.net/01_values.html
2.  https://github.com/TheWoodenMan/freecodecamp-exercises
3.  https://www.youtube.com/watch?v=SWYqp7iY_Tc

**Plan for tomorrow**

1.  Read eloquent javascript ch.2
2.  go back to some of the layours and tidy up a bit.
3.  look at adding pdf support to the lounge bar side (menus)
4.  Keep pushing freecode camp
5.  do a few more codecademy exercises

### Day 103: June 27, 2022

**Today's Progress**:

1. Read eloquent javascript chapter 2
2. Updated and finished my bar website
3. Read the documentation for google maps api and implemented it in practice
4. Read the documentation for gdocs pdf api and implemented it in practice.

**Thoughts**

1. Eloquent javascript is a hard read and mostly revision, but there are some details that are coming out of it that are new to me, so it's worth it.
2. You can use continue/break outside of a switch statement (e.g. in an if conditional or for loop)
3. I really liked how the bar site came together and was proud to share it in the community :)

**Link(s) to work**

1.  https://eloquentjavascript.net/02_program_structure.html
2.  https://bizzicks-bar-grill-portfolio.netlify.app/

**Plan for tomorrow**

1.  I have a full day of work tomorrow so may struggle to fit a lot in.
2.  Minimum I will do anki.
3.  I will try and fit in ch.3 of eloquent javascript.
4.  Flexbox zombies continues.

### Day 104: June 28, 2022

**Today's Progress**:

1.  Finished reading Eloquent Javascript Ch.3
2.  Read about the call stack
3.  Joined a project with another dev to make a clicker game

**Thoughts**

1.  The biggest hurdle to starting the project was working out how to collaborate, setting things up with git/github and
    making sure that our local copies were the same.
2.  The directory structure kept corrupting but we were able to fix it with a bit of experimentation.

**Link(s) to work**

1.  https://eloquentjavascript.net/03_functions.html
2.  https://github.com/JoeSangine/GravityClicker
3.  https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/

**Plan for tomorrow**

1.  Contribute to Gravity Clicker
2.  Flexbox Zombies
3.  anki
4.  review starfinder project and do a little content work on it.

### Day 105: June 29, 2022

**Today's Progress**:

1.  Reading through git from the bottom up.
2.  Did a bit of organisational work on GravityClicker
3.  Passed the streamroller algorithm on freecodecamp

**Thoughts**

1.  Git from the bottom up is kind of incomprehensible to me on the first pass, there's a lot of tech references, and I understand like 40% of it. I need to look into blobs, hashes and trees in particular.
2.  I wasn't able to add a huge amount of coding to GravityClicker today, I'm waiting for feedback from the project lead - however I was able to organise the features into a series of issues on github so we can assign work next time we speak.
3.  Freecodecamp algo was hard, I had a crack and got like 80% of the way there, my solution used foreach since i'm trying to gain familiarity in that but the hint said I should use a loop. I knew to use recursion and got that right - but I missed out on the use of the rest operator which pushed every element in the string not just the first one. All clear and learned my lesson from last time - don't struggle - look it up.

**Link(s) to work**

1.  https://jwiegley.github.io/git-from-the-bottom-up/

**Plan for tomorrow**

1.  It's time for super sunday - 9 hours of review - lets go!

### Day 106: June 30, 2022

**Today's Progress**:

1.  Watched first half of 100Devs super review
2.  Did a bunch of work on the group project, GravityClicker
3.  Pushed 3 algorithms on FCC

**Thoughts**

1.  The super review is definitely revision but still picking up details on the second pass.
2.  I did a lot of work on Gravity Clicker today including adding in random rolls for an asteroid to appear, making it disappear on click and add it's mass to the black hole.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/freecodecamp-exercises
2.  https://github.com/JoeSangine/GravityClicker

**Plan for tomorrow**

1.

### Day 107: July 1, 2022

**Today's Progress**:

1.  Wrestled with addTogether algorithm on FCC
2.  got in my anki practice

**Thoughts**

1.  A day of work, karate practice and running PF2e meant I got basically the minimum coding done, been a little while since I had a day like this but got to keep pushing.
2.  The FCC algorithm is a tough one and involves currying which I don't know enough about tbh, I pushed ab it on my own but tomorrow i'll get a hint and see if that helps more.

**Link(s) to work**

1.  https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/intermediate-algorithm-scripting/arguments-optional

**Plan for tomorrow**

1.  Finish Super review
2.  Start reading class 19
3.  solve addTogether FCC algorithm
4.  Flagged for revision - rest operator

### Day 108: July 2, 2022

**Today's Progress**:

1.  Finished Super Review 💪
2.  Flexbox Zombies Ch.9 🧟
3.  Worked on GravityClicker 🪐
4.  Finished thejsway ch6. - Objects. 📥
5.  Started working on an auto form filler program. 📝
6.  Anki to finish 👍

**Thoughts**

1.  The super review was a grind but great for spaced repetition and recall.
2.  I've mostly been playing around today, it's been fun!

**Link(s) to work**

1. https://github.com/TheWoodenMan/100Devs
2. https://mastery.games/flexboxzombies/
3. https://github.com/JoeSangine/GravityClicker/tree/Gravity-Clicker
4. https://github.com/thejsway/thejsway/blob/master/manuscript/chapter06.md

**Plan for tomorrow**

1.  watch class 19
2.  have another crack at FCC
3.  Push on with sf character picking - it's a grind but get some of it done

### Day 109: July 3, 2022

**Today's Progress**:

1.  Completed my contract/proposal autofiller program. 📝
2.  Class 19 #100Devs. ✊
3.  Pushed a little to the sf project, it's a grind. 🌟
4.  Completed 8th Kyu codewars 💻
5.  Updated my portfolio with autofiller program and added cute CSS animations!

**Thoughts**

1.  Researching more css animations is pretty fun, i'm about to mod my portfolio to have flip cards.
2.  The array work from 100devs is revision but i'm using it as an opportunity to practice more .foreach and arrow functions instead of older styles.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/codewars-exercises
2.

**Plan for tomorrow**

1.  Codewars 8th Kyu
2.  Read jsway ch7 https://github.com/thejsway/thejsway/blob/master/manuscript/chapter07.md
3.  Read js.info array methods https://javascript.info/array-methods
4.  Do another 4-5 sections of sf character choice
5.  Flexbox Zombies Ch.10?
6.  Don't forget to stretch https://simpleprogrammer.com/ergonomic-stretches-for-programmers/

### Day 110: July 4, 2022

**Today's Progress**:

1.  Read Eloquent Javascript Ch.4 📖
2.  Started the exercises at the end of Eloquent Javascript 💻
3.  Push Codewars 8th Kyu 🥋
4.  Cracked the Make a Person object method algorithm challenge on #freecodecamp - getting close to the end! ⛰️

**Thoughts**

1.  Travelling today so it's harder to fit in the coding, I'm reading instead. (read eloquent javascript in manchester airport!)
2.  I managed to crack the FCC I was stuck on after being stuck (haha) on a flight from Manchester to Porto. I have no doubt that reading the section on objects in eloquent javascript just before helped me out a bunch.

**Link(s) to work**

1.  https://eloquentjavascript.net/04_data.html
2.  https://github.com/TheWoodenMan/freecodecamp-exercises

**Plan for tomorrow**

1.

### Day 111: July 5, 2022

**Today's Progress**:

1.  Freecodecamp: Palindromes - first Try! 💪
2.  Freecodecamp: Roman Numeras - Tricky 🍃
3.  Freecodecamp: Caesars cipher - Ave! Straight-forward 👋
4.  Freecodecamp: Telephone number validator ☎️
    This regex was a beast, regex101.com helped a TON
    and had to add in conditionals to handle the parenthesis
5.  Cash Register - Hit the buffers, it threw me down the stairs
    and I had to scrap my code and start again, will try again tomorrow 👊
    My first run-in with floating point errors. I am off by 1 penny!

**Thoughts**

1.  I am genuinely quite pleased that I managed to basically blast through the first 3 projects on here without too much trouble.
2.  Regex is still kind of mystical to me but at least I know I can reach for regex101 if I need to work it out.
3.  The cash register problem is a tricky one and the floating point error threw me a total curveball (first time I encountered it) I had to scrap everything and start again.

**Link(s) to work**

1.

**Plan for tomorrow**

1. Take another crack at FCC Cash Register
2. Codewars 8th Kyu
3. Continue javascript.info and jsway reading.

### Day 112: July 6, 2022

**Today's Progress**:

1.  Finished FCC Cash Register and thus the Cert 🎊🌟👍
2.  Reading: the JS Way Ch.7 Arrays (revision) 📖
3.  Codewars 8th Kyu - powers of 2 ✅
4.  Reading: javascript.info Array Methods 🧮
5.  Started: FCC Front End Libraries - Bootstrap 50%

**Thoughts**

1.  The cash register challenge was rough and I hit a bunch of snags, need to remember about floating point and use parseInt/Float and toFixed() toPrecision() as needed if I spot it coming up again in future.
2.  It's taken me a few months to get to the end of the FCC course but it's honestly been great and doing it alongside 100Devs is a great example of interleaving, I
    feel like I am adding depth and better proficiency by going over it again.
3.  Bootstrap is way easier than I thought, and I even recognise it from some of the site templates I've used in the past. Can't wait to use it in practice!

**Link(s) to work**

1.  https://www.freecodecamp.org/certification/fccd85c66c0-d317-4621-823d-4871a7ad3ba8/javascript-algorithms-and-data-structures
2.  https://github.com/TheWoodenMan/codewars-exercises

**Plan for tomorrow**

1.  Class 21 #100Devs
2.  Push on with FCC Bootstrap.
3.  Javascript 30 day 4
4.  Think about Traversy React

### Day 113: July 7, 2022

**Today's Progress**:

1.  FCC Bootstrap - Completed. 👢
2.  FCC jQuery - Completed. ❓
3.  #100Devs Class 19 - Arrays Lets go! ⤴️
4.  Working through Javascript 30 _slowly_ 🐢

**Thoughts**

1.  I can see why most people don't bother with jQuery, it's basically like a primitive version of some of JavaScript's DOM functions with a sprinkle of CSS
2.  Bootstrap was a lot easier than I thought it would be and recognised some of the syntax from templates i've used.
3.  I need to progress to more difficult array functions, some of the more easy ones are just too well known, I need to be able to iterate from behind an object
    or with a calculation before sorting.
4.  .sort() used in the JS30 context kicked my ass, going to go back over this video, _slowly_ and

**Link(s) to work**

1.

**Plan for tomorrow**

1.  Try and finish javascript 30
2.  Fit in some coding even though I have a full day

### Day 114: July 8, 2022

**Today's Progress**:

1.  Updated portfolio with project management details
2.  Error checked google API on lounge bar site
3.  Started travesy react udemy course

**Thoughts**

1.  I had a lighter coding day because work was pretty full and I was runing pathfinder2e
2.  The google maps API requires an account and subscription - I think it's still possible to configure without it
    but it's throwing errors, so i've added a placeholder for now.

**Link(s) to work**

1.

**Plan for tomorrow**

1.  Push class 21 for 100 devs
2.  Tackle Javascript30 including .sort() and adding to anki
3.  take a look at gravity clicker
4.  FCC Sass if time.

### Day 115: July 9, 2022

**Today's Progress**:

1.  Big anki drop, around 100 cards 📇
2.  Spotted a few bugs in my portfolio (always test people!) and fixed them along with improving layout. 🧯
3.  Listened in to a a live stream on twitter with Shawn Charles about tech recruiting, processess and the market in general 🤝
4.  100 Devs Class 21 ✅
5.  FCC Sass 1/2 way 💁‍♂️
6.  Codewars 8th kyu 🎱

**Thoughts**

1.  For revision, .sort() .filter() .map() <---- Delete/Repeat these
2.  Codewars 8th kyu is a little easy, i'm supposed to do one a day but might push through a bunch or move to 7th kyu

**Link(s) to work**

1.

**Plan for tomorrow**

1.  FCC Finish Sass, start React
2.  #100Devs - continue with Class 21/22 homework
3.

### Day 116: July 10, 2022

**Today's Progress**:

1.  Finished FCC Sass 💁‍♂️
2.  Autofill project added feature to print to pdf 🖨️
3.  javascript.info array methods tasks 🧮
4.  Tidied up autofill on github to allow other #100Devs to join 🎒(dm me 🤙)
5.  Anki to finish ⭐

**Thoughts**

1.  I decided to open up the autofill project to try to see if I could help a few other devs
    and maybe solve some of the problems I've struggled with. Happy to implement printing today!
2.  I'm going a little slower than i'd like but i'm making sure I know array methods well
    before pushing on to objects.
3.  I only did the sass/bootstrap and jquery stuff a few days ago, but it's already almost out
    of my mind - thankfully I added it all to anki so I could review it properly. - still I will
    need a project of some sort before this stuff becomes permanent.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/contract-to-html-autofiller
2.  https://github.com/TheWoodenMan/eloquent-js-info-the-js-way-exercises
3.

**Plan for tomorrow**

1.  Finish javascript.info tasks
2.  Think about Class 22
3.  push autofiller again.
4.  Start jsway tasks

### Day 117: July 11, 2022

**Today's Progress**:

1.  Pushed on with javascript.info tasks ☑️
2.  Learned about the fisher-yates algo for sorting values. 🧮
3.  Anki 40 cards 📇
4.  Pushed half an hour of project management studies, been a while 📈

**Thoughts**

1.  Delete repeated on reduce and sort to get them both right
2.  the fisher-yates algo took some doing, the main sticking point was off by one errors and
    randomising a number between 2 numbers rather than from 1 or 0
3.  To randomise a number between min and max - Math.floor(Math.random() \* (max - min) + min )

**Link(s) to work**

1.

**Plan for tomorrow**

1.  Codewars
2.  Anki
3.

### Day 118: July 12, 2022

**Today's Progress**:

1.  Finished JSway and javascript.info tasks ✅
2.  Class 22 #100Devs 👓
3.  Intro to Git 🔬
4.  Codewars 8th Kyu x1

**Thoughts**

1.  I need more practice on objects in particular, I can get to the right answer generally but it's not 100% fluid yet.
2.  Good review of constructor functions on 100Devs, first time i've heard it explained and felt like I understood it.
3.  Checked in on gravity clicker and it looks like the project lead is testing new features so I'll check in with them first before picking up any new issues 👍
4.  I already did intro to github, so I have finally reached the point where I first found 100Devs!

**Link(s) to work**

1.

**Plan for tomorrow**

1.  Codewars
2.  Anki
3.  Look at videos for Class 23
4.  Remember flexbox zombies? - Let's finish
5.  JSX on FCC? start possibly
6.  Document issues for gravity clicker

### Day 119: July 13, 2022

**Today's Progress**:

1.  My Plan got shelved to work on a site. ❌
2.  Spent all day working on a great website for a client 👀
3.  Anki 📇
4.  Back to regular service tomorrow 📻

**Thoughts**

1.  Had to ditch my learning for the day but it was worth it to work on the site, fully responsive and extremely happy with it. Based on a template - but took a lot of work to set up regardless.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/cex-pt-franchising

**Plan for tomorrow**

1.  Codewars
2.  Anki
3.  Look at videos for Class 23
4.  Remember flexbox zombies? - Let's finish
5.  JSX on FCC? start possibly
6.  Document issues for gravity clicker

### Day 120: July 14, 2022

**Today's Progress**:

1. Wrestled with my new site but got nowhere ⚠️
2. Tried to implement language toggle functionality between different languages. 🐠
3. The template i'm working with strongly resists modding ⛔
4. Rolled it all back via git, but lost some sideline work that I should have branched 💥
5. Finished the first draft translation anyway 🥉
6. Attempted a 6th Kyu kata and got nowhere 👊
7. Got 30 anki cards done. ✅

**Thoughts**

1.  Even though there was a lot of failure today, there was a lot of learning too. I explored toggle switches, langugage conversion apis, jQuery and studied the code of the template I'm using. I also learned the value (the hard way) of creating experimental branches for working on new features, issues or bugs. I need to commit less to main.
2.  I need a web development checklist that includes testing - quality control is important and I'm missing things
    occasionally which is kind of annoying (like the media queries on my portofolio)

**Link(s) to work**

1.

**Plan for tomorrow**

1.  Codewars
2.  Anki
3.  Class 23 videos

### Day 121: July 15, 2022

**Today's Progress**:

1.  Fixed media queries for the flipcards on my porfolio
2.  Github Tutorial For Beginners
3.  Anki
4.  Codewars 8th kyu

**Thoughts**

1.  a lighter day because I had work and ran pathfinder.
2.  getting ready for a big day tomorrow.
3.  I need to switch to using terminal for git commands for good practice
4.  The media queries bug showed me that I need to do more testing on sites before release, I thought it was ok but in practice there were issues - I only found out by accident!

**Link(s) to work**

1.  https://www.codewars.com/kata/551b4501ac0447318f0009cd/javascript
2.  https://github.com/TheWoodenMan/codewars-exercises

**Plan for tomorrow**

1.  Codewars
2.  Anki
3.  Objects the basics
4.

### Day 122: July 16, 2022

**Today's Progress**:

1.  Watched Object Oriented Javascript by @moshhamedani 🐦
2.  Read intro to Github 📖
3.  Made a stopwatch app using OOP and functional programming ⏱️
4.  Made the stopwatch from scratch, no templates - but it needs testing/debugging 📋✏️
    https://thewoodenman.github.io/basic-stopwatch/
5.  Pushed a codewars.

**Thoughts**

1.  Making the stopwatch was tough, I really wanted to make it using objects since I need the practice there.
    But as I made it, I realised my initial design wasn't the most efficient way to do it, so I switched it up and used functional programming to make more sense of it.
2.  Things I got tripped up on: use of .this for programming calling methods from within the object - I got stuck on this for a few hours and there wasn't a huge amount of easy to read documentation on the internet about it - until I picked out a stack overflow that explained a bit about .this and scope - basically declaring a variable of `const self = this;` in the private variables solved the issue, since the functions Couldn't call outside of their own scope and the calls couldn't see the other methods outside of their own block.
3.  the next thing I ran into was unix time conversion issues. The problem was that the date grabs were in date format and werent compatible with miliseconds. Everything worked right up until I had to "pause" the count and do a second "lap", the program was forgetting it's place and starting from 0 again each time, I had to trace through until I found the problem - I had been deducting the difference from the "end" time when instead I should have been adding it to the start time - that basically solved it.

**Link(s) to work**

1.  https://thewoodenman.github.io/basic-stopwatch/
2.  https://youtu.be/PFmuCDHHpwk
3.  https://youtu.be/0fKg7e37bQE​

**Plan for tomorrow**

1.  Codewars
2.  Anki
3.  https://javascript.info/ Whole Chapter - Objects: the basics

### Day 123: July 17, 2022

**Today's Progress**:

1.  Worked on a Client Web Project 📋🖊️
2.  CSS toggle switch for a dual-language website. 🇬🇧/🇵🇹
3.  Modified html5up js and jQuery to accept different states..! ☕
4.  The footer is still broken, but I'll try again 2m! 👢
5.  50-60 Anki cards 📇

**Thoughts**

1.  Working on this project has been excellent but also quite technical and stressful. When I realised what was needed as a result of the language toggle switch - I realised it was a daunting task and nearly choked.
2.  I kept pushing though and had to pick over the jQuery and js files in the html5up template in quite close detail, fixing and modifying the code to support both languages without fully breaking it.

**Link(s) to work**

1.

**Plan for tomorrow**

1.  Codewars
2.  Anki
3.  Pillars of OOP
4.  Start 100Devs calculator
5.  Class

### Day 124: July 18, 2022

**Today's Progress**:

1.  Class 23 #100Devs 🤝
2.  Anki 📇
3.  8th kyu codewars 🦀

**Thoughts**

1.  https://javascript.info/ Whole Chapter - Objects: the basics 🍎
2.  100Devs - Calculator Project - Spent a few hours on it. 🧮

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 125: July 19, 2022

**Today's Progress**:

- Finished http://javascript.info - objects the basics.
- Pushed an 8th kyu codewars
- Started #100Devs Calculator app, got it looking nice on css and clicking on button press 👍

**Thoughts**

1. Calculator app looks great, but tbh it's not hooked up yet and theres a LOT of work to do to make it work.
2. I need to just blast through a few of the 8th kyu codewars, they're pretty easy.

**Link(s) to work**

1.  https://github.com/TheWoodenMan/100devs-calculator

**Plan for tomorrow**

1.  Push on with class 24 if time
2.  Anki
3.  Codewars 8th kyu

### Day 126: July 20, 2022

**Today's Progress**:

1.  Picked up a new client for a podcast website 🎧
2.  Used @figma for the first time to make a nice wireframe it's great 📄✏️
3.  Codewars 8th Kyu 👊
4.  Flexbox Zombies Ch. 10 🧟

**Thoughts**

1.  I like building websites :)
2.  Figma is great, really useful for planning out those home made html/css sites with no template.
3.  After showing my client the figma, they had some requests which was really useful to do before getting started on the code and makes it much easier in the long run.

**Link(s) to work**

1.

**Plan for tomorrow**

1.  Push class 24

### Day 127: July 21, 2022

**Today's Progress**:

1.  Class 24 - Done ✅
2.  Drafted my proposal for my client with contract 👀
3.  #100Devs - Fresh Return - Dropped in #CatchUpCrew 🏃
4.  Codewars 8th Kyu

**Thoughts**

1.  Great to see Leon back on form and 100Devs is popping once more after the break 🥇
2.  I struggled a bit with the agreement and proposal and a bit of impostor syndrome set it, it feels a little... Mean? to be so formal in setting up business agreements. But tbh I probably need to value my time a bit more and realise that actually - this document will allow me to relax and do better work.

**Link(s) to work**

1.

**Plan for tomorrow**

1.  Tomorrow is a travel day so it's going to be difficult to fit anything in, so anything I can manage is a bonus.

### Day 128: July 22, 2022

**Today's Progress**:

    1.  Anki on the metro, maybe 20 cards 🚋
    2.  Pushing on with Class 25/26 tasks ✅
    3.  Worked on my buffer profile. 🐃
    4.  Fixed footer bug for client website 🐛
    5.  Fixed up the buttons on the #100devs Calculator 🧮
        (While I was travelling)
    6.  Finished it when I got home! 💯 Just needs media queries
    https://calcy-386-basic-calculator.netlify.app/

**Thoughts**

1.  Initially I found the calculator project quite daunting but breaking it up into small pieces and doing them bit by bit made it much more manageable.
    I'm pretty sure the code is rough and to be honest it needs refactoring desperately - but it works and for decimal points too.

**Link(s) to work**

1.  https://calcy-386-basic-calculator.netlify.app/

**Plan for tomorrow**

1.  Class 25
2.  Portfolio review etc
3.  Finish the js video I have outstanding
4.  Push on to APIs

### Day 129: July 23, 2022

**Today's Progress**:

1.  Read a blog about tailwind 🐦
2.  Typing practice on keybr.com 86 wpm peak, but tbh I float around 70 mostly ⌨️
3.  Tweaked media queries on the calc app, just giving it a little care before I abandon it 💌
4.  Javascript30 Array Cardio 🏋️‍♂️
5.  Wrote a blog post about self development 📝
6.  Four Pillars of OOP Revision 🏗️
7.  #100Devs Class 26 🎢
8.  Codewars/Anki 📎

**Thoughts**

1.  Got a lot done today, still quite tired from travelling.
2.  Loving the possibilities with APIs
3.  Javascript Array Cardio was quite tough and the instructor breezes through it quite quickly, i'm going to need to do it again.
4.  I want to tidy up the calc app a bit before I send it off, maybe give it some tlc.
5.  I need to remember to branch on git before modifying a working release.

**Link(s) to work**

1.  https://phpprotips.com/the-pros-and-cons-of-tailwindcss
2.  https://courses.wesbos.com/account/access/62c6193f88db94aff300b5d5/view/194130346
3.  https://medium.com/@hamzzza.ahmed95/four-pillars-of-object-oriented-programming-oop-e8d7822aa219

**Plan for tomorrow**

1.  Calc app - update it to include a running total
2.  API Homework, lets get started
3.  Codewars/Anki - never skip

### Day 130: July 24, 2022

**Today's Progress**:

1.  Anki - 60 Cards 🗃️
2.  Started Waifu-Selecta API Game 👀
3.  Learned about Sass 💁‍♂️ from @tutorialstchr
4.  Fun with APIs - Made 2 basic sites. ✅
5.  Cocktail Club Website started 🍸
6.  #100Devs - Class 27 💪
    https://cocktail-club-marina-del-rey.netlify.app/

**Thoughts**

1.  APIs are amazing!
2.  I need to get some practice on localstorage, but understand how it works now at least.

**Link(s) to work**

1.  https://www.tutorialsteacher.com/Sass
2.  https://waifu-selecta.netlify.app/
3.  https://cocktail-club-marina-del-rey.netlify.app/

**Plan for tomorrow**

1.  Add ingredients/instructions to the cocktail API site.
2.  Find a 3rd API site idea
3.  Continue professional checklist
4.  NASA API media queries
5.  Add API to portfolio

### Day 131: July 25, 2022

**Today's Progress**:

1.  Practiced localStorage on one of the APIs 📬
2.  Learned that you can pass objects back and forth to localstorage with JSON methods. 🛳️
3.  Cocktail Club API app updated to show ingredients and title. 🍸
4.  Fixed Calcy 386 app to remove eval() and update a subdisplay with calculation 🧮
5.  Checked in with @joesagine chatting projects and OOP 👾
6.  Updated my portfolio 📝

**Thoughts**

1.  Added a bit of depth to two applications today, I think I have a bit of a bias towards just getting them done and on the road, but
    not to really stick to them and make them really good afterwards.
2.  Priority on getting eval() out and function() due to security concerns - Always have to take responsibility for users in projects.

**Link(s) to work**

1.  https://cocktail-club-marina-del-rey.netlify.app/
2.

**Plan for tomorrow**

1.  Push on with the last API project.
2.  More codewars

### Day 132: July 26, 2022

**Today's Progress**:

1.  Codewars 8th kyu - 5x completed 🥋
2.  1x 7th Kyu done too. 🥉
3.  Cards API - Read up on the API 📖
4.  Made a snap game! :flower_playing_cards 🎴
    https://snapeasy.netlify.app/

**Thoughts**

1.  The card api was hard work to be honest and lots of bugs - but it got done
2.  Learned more about localstorage and APIs as well as doing some solid work with setTimer and clearTimer

**Link(s) to work**

1.  https://snapeasy.netlify.app/

**Plan for tomorrow**

1.  Class 28
2.  Professional Checklist
3.  Take a look at FCC JSX?
4.  Do a little CAPM

### Day 133: July 27, 2022

**Today's Progress**:

1.  Bugfixes on snapeasy API game 🐛
2.  Class 28 #100Devs #CatchUpCrew More API fun 🐲
3.  Updated documentation for many of my github projects 📋
4.  Responded to feedback on snapeasy to fix bugs and improve UI 📣

**Thoughts**

1.  Intro to JS - Codecademy

**Link(s) to work**

1.  https://www.youtube.com/watch?v=G7XJRLaq2Cw&list=PLBf-QcbaigsJysJ-KFZvLGJvvW-3sfk1S&index=27
2.  https://github.com/TheWoodenMan

**Plan for tomorrow**

1.

### Day 134: July 28, 2022

**Today's Progress**:

1.  Intro to JS - Codecademy 💻
2.  Variables/Conditionals/Functions/Scope Done ✅
3.  FCC - JSX/React - 43% 🏰
4.  Codewars 8th Kyu did 5x 👍
5.  Codewars - reached 6th Kyu! 💯
6.  #100Devs - Class 30 - OOP 🐙

**Thoughts**

1.  React is HARD, I swear none of this stuff is going to make sense until I actually use it in a project.
2.  I've been pushing on codewars, 8th kyu is easy so i'm challenging to one-line the answers. I can do 5+ per day.

**Link(s) to work**

1.  https://www.freecodecamp.org/learn/front-end-development-libraries/react/create-a-stateful-component

**Plan for tomorrow**

1.  Survive and do a little :')

### Day 135: July 29, 2022

**Today's Progress**:

1.  Got an hour of anki in

**Thoughts**

1.  Really full day of work, karate and then ran DnD, Friday is always my lightest coding day.

**Link(s) to work**

1.  OwO

**Plan for tomorrow**

### Day 136: July 30, 2022

**Today's Progress**:

1.  Push through Intro to JS on Codecademny 🌄
2.  Functions/Scope/Arrays/Loops/Iterators/Objects 🚚
3.  Class 29 #100Devs 🥅👍

**Thoughts**

1.  The intro to JS is a great super-review for JS, 98% of it I know already but there were a few details especially on objects,
    that I must have missed on the first pass.
2.  If I can fit in anki/codewars every day that will really help with my consistency.

**Link(s) to work**

1.  https://www.youtube.com/watch?v=EOjUT746oLs

**Plan for tomorrow**

1.  Push on with intro to JS - finish him!
2.  professional checklist - get it done
3.  Work on local client prospecting?

### Day 137: July 31, 2022

**Today's Progress**:

1.  Intro to JS - Objects/Advanced Objects 🧊
2.  Finished @codecademy Intro to JS 💪
3.  Codewars - 7th Kyu 🪵
4.  Started Eloquent JS Ch.6 Objects 🎱
5.  Tuned in for @mayanwolfe stream 🐺
6.  Installed Java IDE and experimented a bit ☕

**Plan for tomorrow**

1.  Finish Flexbox Zombies

### Day 138: August 1, 2022

**Today's Progress**:

1.  thejsway Ch. 9 Read/Done ✅
2.  3x Codewars 7th Kyu 🥋
3.  OOP by Mosh on Youtube 🧊
4.  Flexbox Zombies Ch.11 🧟
5.  Codecademy Learn Java - variables ☕;

### Day 139: August 2, 2022

**Today's Progress**:

1.  3x Codewars 7th Kyu 🥋
2.  #100Devs Class 31

### Day 14-: August 3, 2022

**Today's Progress**:

1. 60 Anki Cards

**Thoughts**

1.  Light learning day due to work deployments

### Day 141: August 4, 2022

**Today's Progress**:

1.  40 Anki Cards
2.  Rewatched #100Devs Class 131 on Polymorphism
3.  Got user feedback for some of my API apps.

**Thoughts**

1.  The user feedback was especially useful, with the snap game - after the snap game when they won they thought
    the computer had so I need to make it more obvious that it's you that won.
2.  The feedback on the CeX franchising website was very good and I need to push it forward to client.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 142: August 5, 2022

**Today's Progress**:

1.  Anki 48x 🗃️
2.  Codewars 8th Kyu x2 ✋
3.  Codewars 7th Kyu 🥋
4.  Flexbox Zombies Ch12 Done and Finished 🧟

**Thoughts**

1. Flexbox zombies was an excellent way to practice spaced repetition on flexbox.  
   I'm glad I didn't race through it and took my time with it.

**Link(s) to work**

1.  https://mastery.games/flexboxzombies/chapter/12/level/13

**Plan for tomorrow**

1.  Build tic tac toe
2.  try and start java algos
3.  Play with classes
4.  Class 32

### Day 143: August 6, 2022

**Today's Progress**:

1.  6th Kyu codewars x1 🥋
2.  Browsed the Gitlab Handbook 📖
3.  Updated my snap game API based on user feedback 🎴
4.  Went through the first few algorithms on structy 📊
5.  #100Devs Class 32 🖥️
6.  CAPM training with network schedule analysis 📈

**Thoughts**

1.

**Link(s) to work**

1.
2. https://about.gitlab.com/handbook/

**Plan for tomorrow**

1.

### Day 143: August 7, 2022

**Today's Progress**:

1.  Optimised my portfolio for SEO 👀
2.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.

### Day 143: August 6, 2022

**Today's Progress**:

1.

**Thoughts**

1.

**Link(s) to work**

1.

**Plan for tomorrow**

1.
