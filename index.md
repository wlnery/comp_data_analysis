---
# Do not edit the text between these lines!
layout: default
---
<img src="comp_data_analysis/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>

# EX09: Data Analysis for Continuous Improvement
My PID Number: 730742394

### Part 1.1: Creative Ideation
1. The course should spend less time on the basics and more time of larger conceptual ideas like nodes because it will be more helpful for the large amount of students who come in with a rough understanding of code/technology/logic but lack the deeper technical understanding
2. The course should introduce a couple more handwritten memory diagram assignments on Gradescope because it would greater prepare the students for the test material
3. The course should begin in a more intensive way (similar to point 1) because it will give students more time working on the more advanced concepts prior to the drop deadline, which allows for better planning and potentially garners more interest in the beginning of the course
4. The course should have a class day dedicated to exploring all the ways python, or programming overall, can contribute to one's career or personal life, as well as exploring guidance on career choices given this strange and rapidly changing environment of software engineering. This would better prepare (and maybe "hook in" the interest of) students who are using COMP 110 as an exploratory gateway into technology.
5. The course should utilize more small scale repetition for the very basics in the beginning. For example, while more comprehensive projects like ex03_wordle are useful and exciting to develop, having an assignment that is literally just "create dictionary 10 times, populate them all separately, use X, Y, Z different transforms on them, and document every single line", would have been immensely helpful to me, as a student that learns simple concepts best when I just repeat them over and over again in their simplest form. 

### Part 1.2: Identifying Missing Data

1. Idea without sufficient data to analyze: My idea that is the least directly connected to the data would be #4. There is no real data that measures interest in career guidance.

2. Suggestion for how to collect data to support this idea in the future: For a numeric scale-based option, we could add in questions like, "I would find a class focused on software engineering career pathways and guidance (rate 1-10)," or, "I am experiencing confusion about my future and career path." Alternatively, we could have a multiple choice question in which students could select experiences they would find interesting, including: guest speakers in the industry, presentations on interesting projects (maybe from UNC grads?), a class on how to approach AI (is it staying? Will anyone have a job in 5 years? All the existential unanswerable questions!), etc. Lastly, we could simply just add an open ended question: "What experiences could we add to this class that would be interesting?", and maybe some people would echo my suggestion, although that is a lot harder to quantify.  

### Part 1.3: Choosing My Analysis

1. Idea to analyze with available data: I think either idea #2 or #5 have sufficient data to analyze and build a case from. They both explore concepts that are quantifiable and are focussed on difficulty of the course content which is surveyed in columns such as: difficulty, understanding, and X_effective.

2. This idea is more valuable than the others brainstormed because: I think idea #5 is the most valuable and interesting to do further research on. I can analyze the degree of difficulty students experience based on experience level and since this survey was given prior to the course delving into slightly more conceptual topics, the data will be directly reflecting the struggle (or lack of) students face with foundational concepts. 

### Part 1.4: Analysis
 <br><br>
Within my analysis I created a number of graphs to represent the data. I mainly focused on quantifying the difficulty of the class and relating that to the experience level of the student. I also explored how understanding was correlated with the frequency by which students created their own example code (practicing repetition) and how they rated the benefit of the programming exercises. 
<br><br>
<br><br>

**Difficulty by Prior Programming Experience**
<img src="/comp_data_analysis/static/imgs/image.png" alt="Difficulty by Prior Programming Experience" width="600"/>
<br><br> 
This box plot shows a steady decline in perceived difficulty as the students' experience increases, supporting my claim for more targeted exercises for students less skilled in programming.
<br><br> 
<br><br>

**Difficulty Scores for only Students with <1 Month Experience**
<img src="/comp_data_analysis/static/imgs/image-1.png" alt="Difficulty Scores for only Students with less than one month experience" width="600"/>
<br><br> 
This histogram shows a breakdown of perceived difficulty only within students with less than a month of programming experience. The bulk of students are rating the class at a level 5, which, while not incredibly hard, does suggest they are struggling to some degree.
<br><br> 
<br><br>

**Average Difficulty: Low Experience vs All Students**
<img src="/comp_data_analysis/static/imgs/image-2.png" alt="Average Difficulty: Low Experience vs All Students" width="600"/>
<br><br> 
This histogram directly compares students with little to no experience and the rest of the class, showing that the students with no experience have a harder time than the entire rest of the class averaged.
<br><br> 
<br><br>

**Understanding by Frequency of Creating Own Examples**
<img src="/comp_data_analysis/static/imgs/image-3.png" alt="Understanding by Frequency of Creating Own Examples" width="600"/>
<br><br> 
This line plot shows the steady increase of students' understanding with the more they create their own code examples as a study technique. This suggests that this sort of repetition and creativity may yield higher comprehension levels.
<br><br> 
<br><br>

**Understanding vs Programming Effectiveness**
<img src="/comp_data_analysis/static/imgs/image-4.png" alt="Understanding vs Programming Effectiveness" width="600"/>
<br><br> 
Finally, this bar plot shows a link between students' understanding and their perceived effectiveness of the programming exercises. This shows that students who find the programming exercises more helpful generally feel that they understand the content on a deeper level.
<br><br> 
<br><br>

### Part 1.5: Conclusion
 
I believe my data confirms my idea, that more repetition on the basic concepts would benefit students, particularly those new to programming. We can see there is a noticeable increase in difficulty, as experience decreases. While this is unsurprising, I think it is most helpful to cater to these students who have no real programming experience since this is only an intro class. It's also interesting to note that the students' perceived understanding of the course material generally went up as their perceived benefit from the programming assignments did too. While this could just be correlated to the motivation a student has for the topic, I think there is something to be said for the benefit of these assignments. We see a similar curve as well on the "Understanding by Frequency of Creating Own Examples" graph, which demonstrates that as students create more of their own examples of the code concepts, they gain a better understanding of the overall material. All things considered, I think the case can certainly be made that a greater degree of repetition, particularly self guided repetition, would yield better understanding levels, especially with new programmers. 
 
This data analysis could definitely be refined. For example, comparing classes who were taught with different teaching styles, one more repetitive and one more exploratory, would be interesting data. It's important to note that more experienced students would be negatively impacted here, as it would decrease the amount of time given to more advanced concepts. It would be difficult to balance this with allowing enough time to properly explore more conceptual issues, such as recursion. However, I think smaller, more frequent assignments in the beginning of the semester could mitigate this. 