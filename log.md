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

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 4: August 20, 2020

**Today's Progress**: Worked on conceptualizing the grid game project by breaking it down into its components, like the grid generator. Reviewed the concept of dictionaries.

**Thoughts**: This was a lot of fun. Perhaps it's because I've had a few more lessons since the first time I worked on this project (in first semester last academic year), but I've got a few ideas about different ways to implement this that could *possibly* lead to greater optimization. Also, apart from learning to code, the goal is to make a fun game. If it's complex and whatnot but sucks on the User-end, it's kind of rubbish as a game. Looking forward to continue working on it!

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 5: August 21, 2020

**Today's Progress**: Now able to display the grid in an extremely simple format. I've decided to use a list instead of a dictionary for the grid content just because it seems most convenient based on what I know now and for what I'd like to do with the grid.

**Thoughts**: This was a lot of strategizing. I had to review my old code because I hit a minor roadblock I remembered hitting last year. It was really convenient to have code to refer to, so I'm keeping old versions of my new one for that reason. After I've made some more progress, I'll start looking into how similar games have been implemented. Really pumped to continue working and figure out how to go about updating the grid during the game. Sidenote: I'm aware this is all really basic, but I'm happy to be learning with the incremental progress.

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 6: August 22, 2020

**Today's Progress**: Figured out how to generate the grid from the list of its contents. The grid looks alright with M,N,K = 10 at maximum.

**Thoughts**: At a later point, I'll see if I can make the grid look alright with greater values for M,N,K, although I don't know that anyone would want to play the game with greater values considering how basic the formatting is. I wonder if I can add colour and style it too. AND make it more interactive so the User need not enter the coordinates individually -- they just need to click on the cell. Style isn't the priority right now, but that would be really cool.

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 7: August 24, 2020

**Today's Progress**: Sorted out the search for potential matches. I've got some understanding of the logic behind checking for adjacent matches (and the adj matches of those), just got to figure out the implementation.

**Thoughts**: Missed a day because I had to prioritize other work. But I'm getting back on track, and am really pumped to figure this out more in the coming days. Time to experiment!

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 8: August 25, 2020

**Today's Progress**: Continued working on implementation of adjacent match checking. Decided to split it into separate functions for convenience and readability. 

**Thoughts**: There's a lot I've still got to figure out. Need to sort out the iter_match and adj_match functions so that I can then find a way to update the contents based on those checks (plus where to put error message to User about insufficient no. of adj matches). From there, I've got to figure out how to then update the displayed grid, considering the "gravity". 

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 9: August 26, 2020

**Today's Progress**: Focused on strategy today. Although it's not apparent in the code itself as yet, I've mapped out how the functions interact. I've also updated some of the existing functions like scorekeeper, grid_gen, and play.

**Thoughts**: I'm content with my progress for today, because I've now got more clarity. It's pretty cool how things can kinda make more sense once they've been coded, probably because it's no longer just in my head. Super excited to continue this tomorrow!

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 10: August 27, 2020

**Today's Progress**: Continued working on the code, based on what I sorted out yesterday. I've cleaned it up, as well, so now it's more readable and it's easier to understand.

**Thoughts**: While I know having comments is good for documentation, I realize that I can sometimes go a bit overboard. This defeats the purpose of having comments in the first place, because too many comments (especially ones for parts of the code that are pretty self-explanatory) can make the code unreadable. So, I'm glad that's something I sorted out today.

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 11: August 28, 2020

**Today's Progress**: Debugged the adj_match function using a few test cases. So far, going well. 

**Thoughts**: Can I just say how good it feels to figure out what's wrong with the code *and* fix it? It does. Yeah, that's pretty much it for today. I'mma try out more test cases tomorrow.

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 12: August 29, 2020

**Today's Progress**: The flow of today's session went: tried other test cases -> discovered an issue I needed to account for -> accounted for it -> now have new issue I need to account for. Oh, and I've also brushed up on the concept of sets.

**Thoughts**: Today was equal parts fun and frustrating. It's amusing to go from thinking I've covered all bases to discovering there are bases I'd not even considered previously. But, I'm learning and that's what keeps it interesting.

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 13: August 30, 2020

**Today's Progress**: I spent the hour debugging the adj_check function. While I was able to make it accurately return the adjacent matches of the selected cell; however, I'm still figuring out how to get it to return the adj matches of the adj matches of the selected cell. 

**Thoughts**: It's a bit challenging, because this was the main roadblock that I'd hit last year when I first worked on this project. So, it's a lot of fun, but yeah, challenging. I think that I'll have to dedicate more than an hour and a half to meet my projected deadline (no pressure, although it would be cool to also branch out into other applications of Python). 

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 14: August 31, 2020

**Today's Progress**: Sorted out adj_check and now it returns all adjacent matches. Also, figured out how to keep the game in play while updating the displayed grid each round. 

**Thoughts**: Today's progress was good. I might need to check my code against other test cases, but it's good for now. My priority is to figure out how to implement the "gravity" feature, which is essentially the grid adapting to the updates (deletion of empty cols, shifting of cells into empty ones, etc.). 

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 15: September 1, 2020

**Today's Progress**: Sorted out the score function and started working out how to implement the "gravity" feature. 

**Thoughts**: Today's progress was good, too. The score function works well and the grid_update function works to at least 1 row level. Need to improve this so that it accounts for all necessary row levels.

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 16: September 2, 2020

**Today's Progress**: Changed things up today, due to certain constraints, by working on the final assignment in Course 7 of the IBM Data Science Professional Certificate.

**Thoughts**: Today was alright, I'm learning more about data visualization so that's awesome. I'm looking to apply whatever I learn in this specialization program to my own projects. Not sure if this will be possible in the remaining days I've got, considering some of the projects I initially had in mind. But I'll for sure look into it, because it would be great to do so.

### Day 17: September 3, 2020

**Today's Progress**: Continued working on my final assignments for the data science courses. Learned a little about different approaches to clustering data.

**Thoughts**: Today was fun, because I learned that you can calculate dissimilarity in data, which is really cool! I also continued learning about data visualization. It's taking me a while to grasp the concepts, but it's great to be learning something new.

### Day 18: September 4, 2020

**Today's Progress**: Created a new repo for my assignments in data sciences courses. Continued working on said courses, as well as strategizing for progress on the grid game.

**Thoughts**: It was dope to learn about projects here on GitHub, considering I'm very new to using it. I'm removing the projected end date from the grid game plan because I've realized that there's more I can do with it, even if I don't do everything all at once or even within the year. But it would be a good start.

### Day 19: September 5, 2020

**Today's Progress**: I reviewed some previous lab activities that I've done for some data science courses.

**Thoughts**: This is such a noob-y thing, but I also learned how to create folders in GitHub, and it is so convenient -- except, of course, for the fact that you can't create empty ones. Overall, a pretty decent session of revision. I've still got some pending assignments, so I'll probably continue working on those tomorrow.

### Day 20: September 6, 2020

**Today's Progress**: I continued reviewing previous lessons today, as well as strategizing for some of my pending assignments.

**Thoughts**: Tomorrow, I'm going to see if I can finish one such assignment. I'll also be planning my capstone project, which is exciting! It's a little nerve-wracking, because I'll really have to pull together a lot of the lessons I've learned and am learning. But, I enjoy a good challenge so this should be a lot of fun.

### Day 21: September 7, 2020

**Today's Progress**: Continued reviewing previous lessons and continued debugging the grid_update function. I've also started planning my capstone project which will, for the time being, be quite basic but will ideally have potential for significant optimization later on.

**Thoughts**: It's taking some time for me to debug the grid_update function. I'm wondering if I should just scrap the function and redo it from scratch. Perhaps I'm looking at it the wrong way. But for whatever it's worth, it's a fun challenge and I'm enjoying figuring it out, even though it seems to be taking _way_ longer than it should.

**Link to work**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 22: September 8, 2020

**Today's Progress**: Continued working on one of my final assignments. Amazingly, it took me two hours to debug some code for one of the items and it ended up being just 3 lines long. 

**Thoughts**: Today wasn't eventful, but I would say it was productive. It was frustating but also amusing, because of how simple it actually was. But overall, I'm just glad that I've made some progress on my assignments. My next semester's starting in 2 days, so it's going to be interesting how everything meshes.

### Day 23: September 9, 2020

**Today's Progress**: Continued working on one of my final assignments. It's taking me a really long time to debug my code for one of the items, so that's something I'll likely redo from scratch tomorrow. 

**Thoughts**: Today wasn't as productive as I'd hoped it to be. I essentially spent the bulk of my time trying to debug some code, which is now quite long for what's being asked. I can definitely do it, just need to make sure I achieve my goal of completing this assignment by this weekend since my classes start this week.

### Day 24: September 10, 2020

**Today's Progress**: Finally debugged that item from yesterday. It works! It works! 

**Thoughts**: Today was fun. I mean, it was stressful because I had started from scratch and was suddenly looking at an empty cell. But the more I worked on it, the more I understood about how to go about it. All in all, today was productive!

### Day 25: September 11, 2020

**Today's Progress**: So close to completing one of my datasci courses! Currently, working on the last item of the final assignment.

**Thoughts**: Goal is to accomplish this course by this weekend, so that I can move on to the next one. It's a fairly time-sensitive program, so even though the deadlines of the program itself aren't fixed, my personal timeline requires I get cracking on the next one soon. Super duper looking forward to completing my assignment, especially because I've learned a lot so far. In the words of Dory: Just keep swimming, just keep swimming. 

### Day 26: September 12, 2020

**Today's Progress**: Finally finished one of my datasci courses!! It took a while, so yay.

**Thoughts**: Okay, so now I've got to accomplish my next assignment and work out how I'm going to implement my capstone project. Pretty good work today!

### Day 27: September 13, 2020

**Today's Progress**: Started working on my capstone project. Created the repo for it. Will update as I progress.

**Thoughts**: It's a little daunting to actually work on a small project outside of my regular academics, but it is also exciting! It's taken me months to get this far in my learning and I'm looking forward to seeing it through.

**Link to work**: [Capstone Project](https://github.com/flinksey/Coursera_Capstone)

### Day 28: September 14, 2020

**Today's Progress**: Continued reviewing lessons and working on one of my final assignments. That aside, goal for this week is to find a decent dataset to use for my capstone project.

**Thoughts**: I've been getting busier with uni course work, so I've to allocate my time better to stay on top of all of my projects and assignments.

### Day 29: September 15, 2020

**Today's Progress**: Continued working on my final assignment for Course 8 of the IBM Data Science Professional Certificate program. 

**Thoughts**: I'm getting a better handle on my time commitments, and should finish this assignment by the weekend.

### Day 30: September 16, 2020

**Today's Progress**: Continued working on my assignment. 

**Thoughts**: It's finally crunch time. I've got to make sure that _both_ my assignment and capstone project are completed next week, to make sure that I stay on track with everything. It's nerve-wracking and challenging, but pretty exciting too.

### Day 31: September 17, 2020

**Today's Progress**: Continued working on my assignment. Found a few datasets that I might be able to use for my project.

**Thoughts**: Rearranged blocks in my timeline to account for changes in schedule. Will outline insights tomorrow.

### Day 32: September 18, 2020

**Today's Progress**: Continued working on my assignment. Strategized my capstone project.

**Thoughts**: Today was not as eventful on this front, as I've had to prioritize my coursework for university. It's likely that I won't have much time next week, either, although I'll definitely make some once I get a few other assignments out of the way.

### Day 33: September 19, 2020

**Today's Progress**: Continued working on capstone project. Decided to look for a different dataset, as the one I'd initially planned on using didn't have some of the variables I wanted to look into.

**Thoughts**: Decent progress today! I'm still not 100% sure how I'll work with the data or what I even hope to find, but it's definitely fun figuring it all out.

**Link to work**: [Capstone Project](https://github.com/flinksey/Coursera_Capstone)

### Day 34: September 20, 2020

**Today's Progress**: Continued working on capstone project. Outlined objectives and continued reviewing techniques from past lessons.

**Thoughts**: Incremental progress, but I think that my workflow will be a bit smoother now that I've got some clarity about immediate next steps. Speaking of steps, the next one has to do with getting a deeper understanding of the data. Tomorrow, I need to finally decide which variables will help determine severity of the car accidents and then look into cleaning the data.

**Link to work**: [Capstone Project](https://github.com/flinksey/Coursera_Capstone)

### Day 35: September 21, 2020

**Today's Progress**: Continued reviewing lessons. Also, went through this repo by hangtwenty to supplement previous lessons: https://github.com/hangtwenty/dive-into-machine-learning

**Thoughts**: Was quite busy today, because of some class requirements. Unfortunately, I was not able to do everything I'd planned. Tomorrow, I'll have a bit more time to do some more work for my capstone project.

### Day 36: September 22, 2020

**Today's Progress**: Today was a bit different. Since I'll likely not be able to actually write code for my capstone project until this weekend, I thought I'd check out freeCodeCamp's material for people wanting to learn Python. I've started with their Data Analysis with Python Certification modules.  

**Thoughts**: Last week was hectic and this week, as it turns out, will also be hectic. So, I decided to push my capstone project a bit so I could get some things in order for university, as my classes are my current priority. I'm very grateful to be working with such wonderful people in my teams, and especially to be surrounded by really supportive people like my family. It's a bit sappy, but I would not be able to make half the progress I'm making or do the things that I'm doing without their support and guidance. 

**Link**: [freeCodeCamp's Data Analysis with Python module](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-course/)

### Day 37: September 23, 2020

**Today's Progress**: Continued with FreeCodeCamp's module on Data Analysis. Went through some practice problems available [here](https://github.com/ine-rmotr-curriculum/FreeCodeCamp-Pandas-Real-Life-Example) on GitHub. Decided to work on them on Google Colab for once, instead of on Jupyter Notebook. I know the answers are right there, but I wanted to work on them with some datasets I found online and see what else I could do. Wasn't sure about copyright stuff (something I'll have to add to my list of things to do), so I'm keeping this one private for now. I'll probably get to work on some notes for my python_learnspace repo soon, though.

**Thoughts**: One of the challenges I've got with my capstone project is just the block in terms of deciding which variables to focus on. I'd completely forgotten that it's totally possible for me to play around with the data and see how the variables affect each other--for those that do, at least. Now, I'm a lot more excited about working on my project this weekend!

### Day 38: September 24, 2020

**Today's Progress**: Today, I went back to my grid_game! I learned about Pygame, which is a bunch of Python modules that enables you to build games using Python. Working on two main things with the grid_game: (1) Functionality (i.e. gravity feature is still a work-in-progress) and (2) User Experience. Super, super excited to keep improving it!!

**Thoughts**: I've been working on some simulations this week for my lab class, and it got me thinking about my grid_game. I figure that there were several things about it that would make it inconvenient for someone to actually play the game for fun. It's no good building a game, however simple, if it does not satisfy the end-objective of entertainment for the User. So, after I figure out how to fix the gravity thing, I'll focus on User Experience.

**Link**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 39: September 25, 2020

**Today's Progress**: So, I essentially spent about an hour and a half trying to debug the grid_update function to finally get the gravity feature working. It's still not working the way it should, so that's something still in progress. 

**Thoughts**: Considering the time constraints I've got, I figure that I'll switch things up tomorrow and focus on my capstone project. I'll still bounce around ideas for this, but ultimately I have to figure out what the heck I'm going to do with the project. As a sidenote, I'm not yet sure how I'll incorporate Pygame, so it's currently a point of exploration.

**Link to Grid Game as is**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 40: September 26, 2020

**Today's Progress**: Figured out a couple of possible approaches to fixing the grid_update function. Also, discovered another bug. Might actually have to redo several functions.  

**Thoughts**: I keep getting stuck here, so I think that I should leave it for a day or two to focus on research so that I can come back to it with fresh ideas. Also, I should really get to work on the project. It won't make itself.

**Link to Grid Game as is**: [Grid Game](https://github.com/flinksey/Grid-Game)

### Day 41: September 27, 2020

**Today's Progress**: Finally decided on using the shared dataset provided by the IBM Data Science program instructors, partly because of some constraints that I've got to work around. Worked on the first two steps of the Cross-Industry Standard Process for Data Mining (CRISP-DM), which is the framework that was elaborated on throughout the certificate program. Some references about CRISP-DM: https://towardsdatascience.com/crisp-dm-methodology-leader-in-data-mining-and-big-data-467efd3d3781, https://www.datascience-pm.com/crisp-dm-2/

**Thoughts**: I've decided that I'm going back to the 8th course, which is all about machine learning in Python. I realized that it was counterproductive that I was looking at just my task at hand without branching out and looking at existing supervised machine learning models, which would significantly speed up the process of developing this project. Also, I'm just really happy that I'm no longer so confused and disoriented and can actually get to work on the project. 

### Day 42: September 28, 2020

**Today's Progress**: Worked on analyzing the dataset to figure out what attributes might be helpful for the objective of training the model to determine severity rating.

**Thoughts**: It's kind of freaky how there's a counter that estimates the number of fatalities of road users per day, month, and year. I mean, once this quarantine becomes better managed (fingers-crossed) I'm still going outside and whatnot. But this puts things into perspective.

**Link**: https://github.com/flinksey/Coursera_Capstone/blob/master/C9_Capstone.ipynb

### Day 43: September 29, 2020

**Today's Progress**: Continued working on the Data section of my capstone notebook. Went back to the Machine Learning course (8th in the 9-course program) and figured that I'm building a supervised ML classification model, which helps because now I know what methods to look into. 

**Thoughts**: Didn't do much coding today because of time constraints, which sucks. But I did get to learn some methods that might be more helpful for my project. Excited to go back to the data. I'm realizing that the Understanding Data step takes a lot of time, because this is the jumping off point for developing the solution as it's where we define what sort of data is required and where to look for it.

**Link**: https://github.com/flinksey/Coursera_Capstone/blob/master/C9_Capstone.ipynb

### Day 44: October 2, 2020

**Today's Progress**: Learned more about classification, particularly the K-Nearest Neighbours algorithm.  

**Thoughts**: It's cool to learn about the KNN algorithm because I remember that one of the challenges we had during the Shopee Code League would have been pretty fun to solve using it. On a different note, to address why I skipped a few days, it's because I'm prioritizing my uni coursework and sometimes it takes a while to go through, because I'm learning the fundamentals of concepts that are highly critical in the electronics engineering field. Either way, it's cool to be able to learn all these different things! 

### Day 45: October 3, 2020

**Today's Progress**: Went kind of backwards (since I went to KNN first) and explored regression. 

**Thoughts**: Learning about regression and its applications is fun! It's cool, because it's a bit of a level of abstraction and I got to go into some of the math behind it. Simple Linear Regression made me think of Local Linear Approximation, which was something we did exercises on last year so that was nice.

### Day 46: October 4, 2020

**Today's Progress**: Continued with non-linear regression today. 

**Thoughts**: It was actually a bit more straightforward than it originally seemed before I did the labs, so that was cool! I also recently checked out MIT's course on deep learning, which was also cool. 

### Day 47: October 7, 2020

**Today's Progress**: Completed a lab on an introduction to decision trees. 

**Thoughts**: It was fun doing this lab, because one of the practice items was to figure out how to determine the accuracy of the model without using sklearn. Although it was only a few lines of code, I appreciate sklearn a little bit more now that I see the difference it makes for efficiency (in terms of coding). I've also started reading about the different distance metrics used in machine learning. It's cool how this goes beyond Euclidean distance, because up until recently, I hadn't realized just how many different metrics or types of metrics there were for accuracy and for distance. 

### Day 48: October 9, 2020

**Today's Progress**: Worked on a final assignment on classification.

**Thoughts**: It was cool to figure out how to build an accurate model for different algorithms (i.e. KNN, Decision Trees, etc.). The goal is to complete the assignment over the weekend. It's a little stressful to work on this challenge, considering that it's not the focus of my major (which is my number 1 priority) and that my workload has become a bit more demanding. So, a bit worried about managing everything, but it's a work-in-progress!
