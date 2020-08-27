# 100 Days Of Code - Log

### Day 0: August 16, 2020 

**Today's Progress**: After shifting frantically between tabs to decide which website to use, I eventually settled on HackerRank and solved a few practice problems for Python proficiency.

**Thoughts:** I've never really coded for anything outside of academic work so, although I have taken a course on programming w/ Python, I wanted to sort of do a reset and start from the fundamentals. My goal is to turn programming into a habit, because I've got a lot of ideas that I want to actualize from the developer end and because I genuinely just think it's fun. I chose HackerRank mostly because I already had an account and, based on some reviews, it seems like a decent starting point for beginners.

**Link to work:** [HackerRank Profile](https://www.hackerrank.com/ramonasraj)

### Day 1: August 17, 2020

**Today's Progress**: Learned about list comprehensions and solved a related practice problem on HackerRank (Python)

**Thoughts**: As it turns out, it's not a good idea to code while sleep-deprived. It took me way too long to figure out the logic behind the problem, but I did learn a relatively new concept, so totally worth it!

**Link to work**: [HackerRank Profile](https://www.hackerrank.com/ramonasraj)

### Day 2: August 18, 2020

**Today's Progress**: Experimented with different approaches for "Find the Runner-Up Score" problem on HackerRank (Python)

**Thoughts**: I had some knowledge of built-in functions I could use to make things easier, but I wanted to first see how I could possibly implement it using as few built-in functions as possible. This experiment became a 1-hr replay of the ValueError: ls.remove(x): x not in list. So, yay for consistency, I guess. But I did get to concept-check lists, loops, and functions, so that was good! 

**Link to work**: [HackerRank Profile](https://www.hackerrank.com/ramonasraj)

### Day 3: August 19, 2020

**Today's Progress**: Revisited old software project, which was a grid game similar to Candy Crush (clearing of matched adjacent cells). Started it from scratch with my own modificationa (will be updating this as I make more progress). There's barely any code as yet, because I spent a good amount of time reviewing the past project to understand how I implemented it before. 

**Thoughts**: Remembered how much fun it was to work on this project and I wanted to see if I could create a better version (optimized) of it from scratch. I really like learning through projects because they're basically like loads of practice problems grouped into something bigger and more complex. Super excited to make progress on this!

**Link to work**: [Grid Game](https://github.com/flinksey/game_time)

### Day 4: August 20, 2020

**Today's Progress**: Worked on conceptualizing the grid game project by breaking it down into its components, like the grid generator. Reviewed the concept of dictionaries.

**Thoughts**: This was a lot of fun. Perhaps it's because I've had a few more lessons since the first time I worked on this project (in first semester last academic year), but I've got a few ideas about different ways to implement this that could *possibly* lead to greater optimization. Also, apart from learning to code, the goal is to make a fun game. If it's complex and whatnot but sucks on the User-end, it's kind of rubbish as a game. Looking forward to continue working on it!

**Link to work**: [Grid Game](https://github.com/flinksey/game_time)

### Day 5: August 21, 2020

**Today's Progress**: Now able to display the grid in an extremely simple format. I've decided to use a list instead of a dictionary for the grid content just because it seems most convenient based on what I know now and for what I'd like to do with the grid.

**Thoughts**: This was a lot of strategizing. I had to review my old code because I hit a minor roadblock I remembered hitting last year. It was really convenient to have code to refer to, so I'm keeping old versions of my new one for that reason. After I've made some more progress, I'll start looking into how similar games have been implemented. Really pumped to continue working and figure out how to go about updating the grid during the game. Sidenote: I'm aware this is all really basic, but I'm happy to be learning with the incremental progress.

**Link to work**: [Grid Game](https://github.com/flinksey/game_time)

### Day 6: August 22, 2020

**Today's Progress**: Figured out how to generate the grid from the list of its contents. The grid looks alright with M,N,K = 10 at maximum.

**Thoughts**: At a later point, I'll see if I can make the grid look alright with greater values for M,N,K, although I don't know that anyone would want to play the game with greater values considering how basic the formatting is. I wonder if I can add colour and style it too. AND make it more interactive so the User need not enter the coordinates individually -- they just need to click on the cell. Style isn't the priority right now, but that would be really cool.

**Link to work**: [Grid Game](https://github.com/flinksey/game_time)

### Day 7: August 24, 2020

**Today's Progress**: Sorted out the search for potential matches. I've got some understanding of the logic behind checking for adjacent matches (and the adj matches of those), just got to figure out the implementation.

**Thoughts**: Missed a day because I had to prioritize other work. But I'm getting back on track, and am really pumped to figure this out more in the coming days. Time to experiment!

**Link to work**: [Grid Game](https://github.com/flinksey/game_time)

### Day 8: August 25, 2020

**Today's Progress**: Continued working on implementation of adjacent match checking. Decided to split it into separate functions for convenience and readability. 

**Thoughts**: There's a lot I've still got to figure out. Need to sort out the iter_match and adj_match functions so that I can then find a way to update the contents based on those checks (plus where to put error message to User about insufficient no. of adj matches). From there, I've got to figure out how to then update the displayed grid, considering the "gravity". 

**Link to work**: [Grid Game](https://github.com/flinksey/game_time)

### Day 9: August 26, 2020

**Today's Progress**: Focused on strategy today. Although it's not apparent in the code itself as yet, I've mapped out how the functions interact. I've also updated some of the existing functions like scorekeeper, grid_gen, and play.

**Thoughts**: I'm content with my progress for today, because I've now got more clarity. It's pretty cool how things can kinda make more sense once they've been coded, probably because it's no longer just in my head. Super excited to continue this tomorrow!

**Link to work**: [Grid Game](https://github.com/flinksey/game_time)

### Day 10: August 27, 2020

**Today's Progress**: Continued working on the code, based on what I sorted out yesterday. I've cleaned it up, as well, so now it's more readable and it's easier to understand.

**Thoughts**: While I know having comments is good for documentation, I realize that I can sometimes go a bit overboard. This defeats the purpose of having comments in the first place, because too many comments (especially ones for parts of the code that are pretty self-explanatory) can make the code unreadable. So, I'm glad that's something I sorted out today.

**Link to work**: [Grid Game](https://github.com/flinksey/game_time)
