# Practices of An Agile Developer, Working in the Real World   *By Venkat Subramaniam and Andy Hunt*

## Chapter 1: Agile Software Development
* Software development is more like surfing, it's a dynamic, every changing environment.
* Your software project depends on the skills, training and competence of all the developers on the team.
* Software is never really **done** as long as people continue to use it.
* You want to tackle small problems while they are still small, explore the unknown before you invest too much in it, and **be prepared to admit you got it all wrong as soon as you discover the truth**.
* Agile development uses feedback to make constant adjustment in a highly collaborative environment.

#### The Agile manifesto
1. Individuals and interactions over processes and tools.
2. Working software over comprehensive documentation.
3. Customer collaboration over contract negotiation.
4. Responding to change over following a plan.

> While there is value in the items on the right, we value the items on the left more.
---
---
## Chapter 2: Begining Agility
> *He who chooses the beginning of a road chooses the place it leads to.*
* Software development dosen't happen in a chart, an IDE, or a design tool; it happens in your head.
* A professional attitude focuses on positive outcomes for the project and the team.
---
### 1. Work for Outcome
* In an agile team, the focus is on outcomes. You want to focus on fixing the problem, instead of affixing the blame. *Blame dosen't fix bugs*.
* If you go to an agile team member with a complaint, you'll hear *"Ok what can I do to help you with this?*.
* *Blame dosen't fix bugs* Instead of pointing fingers, point to possible solutions. It's the positive outcomes that counts.
---
### 2: Quick fixes become Quicksand
* Beware of land mines.
* Isolation is dangerous; don't let your developers write code in complete isolation.
* Use unit tests(executable Documentation).
* Don't fall for the quick hack. Invest the energy to keep code clean & out in the open.
* Fix the problem not the symptom.
---
### 3. Criticize Ideas, not people.
* No accusation, no judgement, just a simple clarification.
* Negativity kills innovation - negative comments & attitudes kills innovation.
* Focus on solving problems rather than trying to prove whose idea is better.
* Design( and life, for that matter) is full of compromises. A winning team is the one that realizes this fact.
* Take pride in arriving at a solution rather than proving whose idea is better.

> You don't have to be great to get started, but you have to get started to be great - Les brown.  
> It is the mark of an educated mind to be able to entertain a thought without accepting it.
---
### 4. Damn the Torpedoes, Go Ahead.
* Sometimes the best plans fails in the absence of courage. Despite the dangers - the real & metaphorical torpedoes - you need to charge ahead and do what's right.
* *Do what's right* - be honest, and have the courage to communicate the truth. It may be difficult at times; that's why it takes courage.
---
---
## Chapter 3: Feeding Agility
> Even if you are on the right track, you will get run over if you just sit there - Will Rogers.
* Being in the software profession is a bit like being on a threadmil - you have to keep up with the pace, or you'll be thrown off. It's up to you to keep up with change.
* Investing in keeping yourself up to date is a great start, but you also need to make an effort to Invest in your Team.
---
### 5. Keep up with change
> There is nothing permanent except change - Heraclitus.
1. Learn Iteratively and incrementally
2. Get the latest buzz - Tech Blogs, Pragmatic programmer.com
3. Attend local user groups.
4. Attend workshops or conferences
5. Read voracioiusly - Find good books on software development and non-technical topics.

You don't have to become an expert at everything, but stay aware of where the industry is headed, and plan your career and projects accordingly.

---
### 6. Invest in your team
* On a team, it's not enough if you personally know a lot.
* Find areas where you, or someone in your team who is knowledgeable, can help the rest of the team come up to speed.
* Each week, ask one member of your team to lead the discussion.

> Raise the bar for you & your team - use brown-bag sessions to increase everyone's knowledge and skills and help bring people together. Get the team excited about technologies or techniques that will benefit your project.
---
### 7. Know when to unlearn.
* Given the change is so constant and pervasive, does it make any sense to keep applying the same techniques and tools you've always used?

* Expensive mental models aren't discarded lightly
    > Old habits are hard to break and even harder to notice.  
    > The first step to unlearning is to realize that you're using an outdated approach.  
    > The other part is letting go

Learn the new; unlearn the old - when learning a new technology unlearn any old habits that might hold you back. After all, there's much more to a car than just a horseless carriage.   

---
### 8. Question until you understand
* Ask why?. Don't go with assumptions.
Keep asking why - Don't just accept what you're told at face value. Keep questioning until you understand the root of the issue.
---
### 9. Feel the Rhythm
* Tackle tasks before they bunch up - It's easier to tackle common recurring tasks when you maintain steady, repetable intervals between events.
----
### 10. Let customers make decisions.
* Developers, managers, or business analysts shouldn't make business-critical decisions. Present details to business owners in a language they can understand, and let them make the decision.
* **Decide what you shouldn't decide**.
---
### 11. Let design Guide, Not dictate.
* Design should be only as detailed as needed to implement.
* Design and all the code that implements them, will constantly evolve.
* There are 2 levels of design: Strategic and tactical.
    - Up-front design is strategic. You typically do that when you don't yet have a deep understanding of the requirements. It should express a general strategry but not delve into precise details.
    - A good strategic design should act as a map that will point you in the right direction.
* How can you tell whether a design is good or even adequate?
    - If small changes in the requirements remain easy to implement, then it's a good design.
    - A good design is a map; let it evolve. Design points you in the right direction. It's not the territory itself; it shouldn't dictate the specific route. Don't let the design(or the designer) hold you hostage.
    - A good design is accurate, but not precise. That is, what it says should be correct, but it shouldn't go far as to include details that might change or that are uncertain. **It's an intent, not a recipe**.
---
### 12. Justify Technology use
* The less code you write, the less you have to maintain.
* Don't build what you can download.
* **Choose technology based on need**. Determine your need first, and then evaluate the use of technologies for those specific problems. Ask critical questions about the use of any technology, and answer them genuinely.
---
### 13. Keep it Releasable
* Anytime you are unprepared is the perfect time for the enemy to strike.
* Checked-in code is always ready for action.
* When working in a team, you have to be sensitive to the changes you make, constantly keeping in mind that you affect and influence the state of the system and the productivity of the whole team.
* There's a simple workflow to follow to make sure you don't check in broken code.
    - Run your local tests.
    - Check out the latest source.
    - Check in.
* Version the database schema, the external files, and so on, as well as the API's that reference it, so that all related changes can be tested.
* **Keep your project releasable at all times.** Ensure that the project is always compilable, runnable, tested, and ready to deploy at a moment's notice.
* **Don't render the system unreleasable & irreversible as well.**
---
### 14. Integrate Early, Integrate Often.
* As you let a subsystem grow, unintegrated, you're exposing yourself to greater & greater risk.
* Code Integration is a major source of risk. To mitigate the risk, start integration early & continue to do it regularly.
* Never accept big-bang integration.
---
### 15. Automate Deployment Early.
* **Deploy your application automatically from the start.** Use that deployment to install the application on arbitrary machines with different configurations to test dependencies. 
* QA should test the deployment as well as your application.
---
### 16. Get Frequent feedback using Demos.
* **Requirements are as fluid as ink.**
* The success in software development is based on how close you end up to your customer's expectation.
* Develop in plain sight. Keep your application in sight(and in the customers mind) during development. Bring customers together and proactively seek their feedback using demos every week or two.
* If it's not stable, don't show it.
---
### 17. Use short Iterations, Release in Increments.
* Iterative development is where you carry out the various task of development - analysis, design, implementation, testing, and seeking feedback--in small, repetitive cycles, called iterations. The end of an iteration marks a milestone.
* **Show me a detailed long-term plan, and I'll show you a project that's doomed.**
* The idea of tackling a large project by taking small steps is key to an agile approach.
* Large leaps increase your risk; small steps help you maintain your balance.
* Release your application soon, because it might not even be relevant later.
* **Develop in increments.** Release your product with minimal, yet usable, chunks of functionality. Within the development of each increment, use an iterative cycle of one to four weeks or so.
---
### 18. Fixed prices are broken promises.
* A fixed price guarntees a broken promise.
* **Estimate based on real work.** Let the team actually work on the current project, with the current client, to get realistic estimates. Give the client control over their features and budget.
---
### 19. Put Angels on Your shoulders.
* Code changes rapidly. Every time your finger hits the keyboard, the code has changed. Agility is all about managing change, and the code is the one thing that probably changes the most.
* To constantly make sure everything is ok, you need automated unit tests. With unit tests in place, acting as regression tests, you're now free to refactor the code base at will.
* Reasons to get started with unit testing
    - Unit testing provides instant feedback.
    - Unit testing makes your code robust.
    - Unit testing can be helpful design tool.
    - Unit testing can act as probes when solving problems.
    - Unit tests are reliable documentation.
    - Unit tests are a learning aid.
* **Use automated unit tests.** Good unit tests warn you about problems immediately. Don't make any design or code changes without solid unit tests in place.
---
### 20. Use It Before You Build It
* Write tests before writing code.
* By Writing the tests first, you're looking at your code from the perspective of a user of the code.
* Figure out what is the minimum amount of effort required to implement a given feature successfully.
* Use Test Driven Development as a design tool. It will lead you to a more pragmatic and simpler design.
---
### 21: Different Makes a Difference
* If something is different, odds are it will make a difference.
* Run unit tests on each supported platform and environment combination using CI tools. Actively find problems before they find you.
---
### 22. Automate acceptance testing
* Create tests for core business logic.
* Have your customers verify these tests in isolation, and exercise them automatically as part of your general test runs.
---
### 23. Measure Real progress.
* Time sheets rarely represent the reality of work completed.
* Try to determine how much work you have left instead of trying to calculate some bogus percentage of "doneness".
* **Measure how much work is left** - Don't kid yourself or your team with irrelevant metrics. Measure the backlog of work to do.
* Keep the road ahead very visible by using a backlog.
* Focus on functionality, not the calendar.
---
### 24. Listen to users
* Whether it's a bug in the product, a bug in the documentation, or a bug in our understanding of the user community, it's still the team's problem, not the user's.
* We go to great lenghts to get feedback from code using unit tests and such, but it's all too easy to ignore the feeback from users.
* You need to listen to them, Even if they sound stupid.
* Every complaint holds a truth- find the truth, and fix the real problem.
---
---

## Chapter 6 - Agile coding.
> Any fool can make things bigger, more complex, and more violent. It takes a touch of genius--and a lot of courage--to move in the opposite direction. - John Dryden.
* **A short-cut helps you only postpone a problem instead of solving it.** It may come back to haunt you, and the rest of your team, as the schedule pressure mounts.
* It's better to be clear than clever as you program intently and expressively.
* **Commenting is used to compensate for poor code.**

### 25. Program Intently and Expressively.
* What good is a piece of code if no one can understand how it works.
* You Should always choose readability over convenience.
* Write code to be clear, not clever. Express your intentions clearly to the reader of the code. Unreadable code isn't clever.
> **The PIE Principe** - Code you write must clearly communicate your intent and must be expressive. By doing so, your code will be readable and understandable. By doing so, your code will be readable and understandable. Since your code is not confusing, you will also avoid some potential erros. Program Intently and Expressively.

---
### 26. Communicate in code.
* **Don't comment to cover up**.
* Code will always be read many more times than written, so the little extra effort that is required to document your code when writing it will pay you back handsomely in the end.
* You need to document your code in two ways.
    - Using the code itself.
    - Using comments to communicate noncode issues.
* For each method in the class, you might want to mention some of the following
    - Purpose: Why does this method exist?
    - Requirements (pre-conditions): What inputs do we need, and what state must the object be in, for this method to work?
    - Promises (post-conditions): What state is the object in, and what values are returned on successful completion of this method?
    - Exceptions: What can go wrong, and what exceptions may be thrown?
* **Comment to communicate.** - Document code using well-chosen, meaningful names. Use comments to describe its purpose and constraints. Don't use commenting as a substitue for good code.
---
### 27. Actively Evaluate Trade-Offs.
