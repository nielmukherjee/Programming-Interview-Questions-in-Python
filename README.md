# Leetcode-Solutions (Work in Progress)
After doing over 120+ questions from EPI, CTCI and leetcode combined, I've hand selected questions I believe every software engineer needs to complete in preparation for the Big N whiteboarding interviews. These are questions, I believe will give the most bang for your buck and investment on time. Worthy of adding to your arsenal to fight the coding gods! 

Each question has its own unique 'gotcha' that you should learn. You want to take each question to the most optimal solution in-order to fully maximize what you can learn from it. Some questions are onion questions, with multiple solutions to the problem, its also important to know them all. For example, do it both recursive and iteratively or BFS and DFS. 

# Mindset approach to Whiteboard interviews
Attempting to pass whiteboard interviews is a daunting task. No one is born natural to it. That is why I'd like to set a tone and mindset when I approach almost anything that I am unfamiliar with. Here are a few quick tips that can get you started.

#### Prepare to fail
You will fail. Accept it. However, DO NOT ALLOW it to dictate your future actions. There is only one effective way to deal with failure. That is to learn from it. Learn as much as you can from the choices you have made. In this case, that means, learn what you can from each question, encounter and process. 

Even if you are prepared, you will have bad days and good days. Things that are out of your control will affect the decisions that other people make. Maybe they had a bad day too. The only thing that can land you the dream job is to try and to try many times. Increasing the chance of being hired with each session and use each session to improve upon what you already know. Only way is moving forward.

This is why this will lead up to my next point.

#### Play to learn, not play to win
Yes you want that Big N job, we all want it. However, you cannot get that job unless you start shifting your objective from "winning" to "learning". "Winning" should never be your first objective, your first objective is to "learn". Why? For some, if "winning" was their first objective, they run into starter paralysis aka. fear. Afraid to lose. When "winning" or "losing" becomes your first priority, you become blinded from how the process can take you there. For others, people try to cheat the game by memorizing instead of ultimately learning which is by far more fundamentally sound for the lifespan of your career. Don't get me wrong, having a goal to win is important, but remember, its just a long term goal, not an obstacle.

# How should you practice for whiteboard coding questions
### There are infinite amount of questions but only a finite amount of methods to the solution
Remember, there are limitless amount of questions someone can ask you, but that is because you can word it differently here and there but the process to get to the solution is similar if not the same as the next. That is why one should focus on learning patterns instead of trying to memorize or see as many questions. You must prepare for the inevitable scenario that you will have to solve a question you have never heard of it. In-order to tackle this, you must be able to identify patterns in the questions with previous questions you have faced and apply those solutions for this scenario. That is why you should focus on learning the coding patterns and techniques.

### Planning vs. implementation
Everyone has different levels of thinking. When I first started, I had trouble even thinking about the how and what DS and Algo to use. After a while, I was able to get optimized theorical solutions but I was lacking in the implementation department. When it came time to write code, I would stumble a lot. Trying to put my words and thought process into code was difficult for me. 

It will be different for you, but I 100% recommend, make sure you run through your 'theorical' solution a few times with a couple edge cases. Ascending, descending, empty list, duplicates, even, odd etc... I've had tons of scenarios where I would implement my solution to find out I forgot an important missing piece. 

So read the question twice, three times, make sure you don't miss anything and PLAN! Make sure you spend ATLEAST 10 minutes before you write any code, DRAW IT OUT, TALK IT OUT. I had to draw pictures, my techinique was to draw it and follow with the drawing as I coded. It was the only way I was able to get consistent results. For some questions, I had to use real world objects because I could relate to them easily to find edge cases. Like questions that deal with swapping, I would immediately visualize a theater row of seats. If the question also wanted to pair things together, I would think of boyfriend/girlfriends all randomly seated and your job was to pair the couples together. I know it's wierd, but it worked for me. Find your method, test a few ways and make sure it works for you. 

### Figure out how you currently think
It is important that you struggle with questions. This struggling will allow you to see why your current way of thinking is incorrect. This way, when the solution is given to you, you can figure out the difference between the ideal and your method. You must be open to new approaches and methods that are foreign to you. When I first started, I approached problems radically different than I do know. My past solutions were very wonky and unconcise. Multiple problems with the use of the language, structure, dead complex code and naming of variables/functions. It made it very hard for someone else to read. I have since refined my code to be as dumb proof as I can do while being very simple. Take the time to refine your solutions by comparing what others have done.

### Learn how to dilute the question

### Repetition

### Use encapsulation

### Train with 10x the gravity

# Resources for your journey
- Elements of Programming Interviews
- Cracking the Coding Interview
- https://leetcode.com/
- Head first into Design Patterns
- https://www.pramp.com/
- https://interviewing.io/

# Bottom-Up and Top-Down Approaches
Usually solutions will take either one of these approaches. Depending on the question, either or will be easier than the other. In interviews however, both approaches are fine. I rarely get asked to implement a specific approach, instead this is more or less the interviewee's choice of preference. I advise exploring and getting a 'feel' with the pros and cons of either approach. There isn't a very good way of explaining when to use one over the other. You just sort of 'know' based on how familiar you are to the implementation.

# Tackling Recursion

# Tackling Dynamic Programming
Dynamic programming is using previously calculated information to calculate the next solution. To do this, one must allocate extra space to save sub-answers. This extra space is usually in two forms, either a one-dimensional array or a two-dimensional array, for interviewing purposes, it shouldn't need to go any further. Now the last portion you need to figure out is, what makes a sub-answer? Then you have to ask, what is the sub-problem? Then you have to think in terms of divide and conquer, what is the smallest problem set I could use, that when combining other small problem sets create another 'summation' of other problem sets. This will require a 'feel' of how solutions with dynamic programming work. There isn't a very good way to explain this other than the way I just described, so just dive in.

# Question List

### Basics
I intentionally mixed these together. Some questions, if I were to categoized them to their respective data structures would give out too much about the question. These I believe one should start with.
- #1. Two Sum
- #141. Linked List Cycle
- #7. Reverse Integer
- #29. Divide Two Integers
- #404. Sum of Left Leaves
- #367. Valid Perfect Square
- #402. Remove K Digits
- #46. Permutations

### How you structure your code
These questions are fairly straight forward, no trick questions or gotchas here. You should try to improve and shave the excess fat off your code when trying to solve this. If an interviewer asks you one of these questions, it is to test your ability to write 'clean' code, not how you utalize DS or Algos.
- #36. Valid Sudoku
- #289. Game of Life

### Intro to dynamic programming
Dynamic programming is a mystery to some people, this is why I split this into its own separate category so you can focus purely on how you can use it to your advantage.
- #198. House Robber
- #221. Maximal Square
- #5. Longest Palindromic Substring

## Deeper into the weeds
Below, I've tried to select questions I think will give you a different perspective of the category that one may not have been exposed with during their studies.

### BFS and DFS
- #200. Number of Islands

### Recursion
- Facebook Possible Patterns

### Hash Tables
- #138. Copy List With Random Pointer

### Linked lists

### Heaps

### Sorting
- #215. Kth Largest Element in an Array	

### Graphs
- Uber's Location Question

### Deeper with dynamic programming
- #139. Word Break
- #516. Longest Palindromic Subsequence

### Combine more than one data structure
You may start these questions once the above questions have been completed. These set of questions test your ability to combine more than one data structure together to create an efficent solution. A must do, as it will greatly strengthen your ability to establish relationships between data structures.
- #146. LRU Cache
- #355. Design Twitter
- Word Popularity

### Design
- Design a Rubix Cube
- Design a parking lot

### Twist
- Google's sorting couples

### How you think
These questions can be diffcult if you use the wrong data structure or set of logic, but is quite easy once you focus on 'how' the solution is built. Try to use a simple test case but focus purely on the lowest denominator solution. What's makes a trapped rain water? Or what makes a zig zag a zig zag?
- #42. Trapping Rain Water
- #6. ZigZag Conversion
