# The Mythical Man-Month - 44
## Essays on Software Engineering
### by Fredrick P. Brooks, Jr.

## 3 / 4. The Surgical Team / Aristocracy Democracy, and System Design
### These studies revealed individual differences between high and low performers, often by an order of magnitude - Sackman, Erikson, and Grant

How do you effectively allocate sub tasks to teammates to truly build large systems on a meaningful schedule? This is the problem chapter begins with. A study was done to measure a group of experienced programmers. "The ratios between best and worst performances averaged about 10:1 on productivity measurements and an amazing 5:1 on program speed... In short the $20,000/year programmer may well be 10 times as productive as the $10,000/year one." (page 30) 

A solution is give, to remove those who are the absolute best at there role. "The conclusion is simple: if a 200 man project has 25 managers who are the most competent and experienced programmers, fire the 175 troops and put the managers back to programming" (page 30) I initially was shocked to read this, but I looked forward to the author diving into his explanation of his 'solution.' He suggests that common consensus states a 'small team' consists of 10 or less people. With a team the size of 200 you will need multiple levels of management, support in finance personnel, space, secretaries, and machine operators. 

However, the author also states that the original 200-men team was not large enough to build the really large systems by brute-force methods. He give a real world example, "Consider OS/360, for example. At the peak over 1000 people were working on it - programmers, writers, machine operators, clerks, secretaries, managers, support groups, and so on. From 1963 1966 probably 5000 man-years went into its design, construction, and documentation." (page 31) In comparison our 200 man team would have taken 25 years to have brought the product to its present stage, if men and months traded evenly.

This brings more detail to our problem, now we see that the problem with a small, sharp team concept is that it is too slow for really big systems. Suggest that we take a team of ten people and assign them a project similar to the OS/360 project. With many many assumptions and extra false bounds put on the real OS/360 team and on our hypothetical team, they can do the same 5000 man year job in 10 years. This time frame is too long, how do we know that the design will be interesting in 10 plus years? How do we know that it won't be passed by rapidly developing software technology?

Harlan Mills suggests a creative solution. He proposes that each segment of a large job is given its own team, that team be organized like a surgical team rather than a hog-butchering team. This analogy means that instead of each member of the team take their own piece of the problem until it is finished, a single 'surgeon' does the cutting and the others give him every support that will enhance his effectiveness and productivity. I believe this solution offers many pros. Specifically, I like the concept of less minds but more hands being involving in the designing and construction. 

The surgeon in this analogy is called the 'chief programmer.' He is responsible for a slew of things. He must define the functional and performance specifications, code, test, and write the documentation. "He needs great talent, ten years experience, and considerable systems and application knowledge, whether in applied mathematics, business data handling, or whatever." (page 32) The surgeon / chief programmer needs to be the best of the best.

The copilot is the alter ego of the surgeon. They need to be able to do any part of the surgeon's job, but is overall less experienced. "The surgeon tries his ideas on his but is not bound by his advice. The copilot often represents his team in discussions of function and interface with other teams. He knows all of the code intimately. He researches alternative design strategies. He obviously serves as insurances against disaster to the surgeon. He may even write code but he is not responsible for any part of the code." (page 32) I believe this to be the best type of insurance, both to protect from unbearable workload for the surgeon, isolation on the surgeon's part, and God forbid disaster to the surgeon. I specifically like the part of the copilot's job that they are in place for the surgeon to bounce ideas and concepts off of.

Other roles such as the administrator, the editor, the two secretaries, the program clerk, the toolsmith, the tester, and the language lawyer are also vital roles that make up this process.  

"The purpose of a programming system is to make a computer easy to use. To do this, it furnishes languages and various facilities that are in fact programs invoked and controlled by language feature. But these facilities are bought at a price: the external description of a programming system is ten to twenty times as large as the external description of the computer system itself." This concept is very interesting to me. I am very interested in the insights provided in chapters 3 and 4 about this concept.